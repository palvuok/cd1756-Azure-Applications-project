# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 



**Comparative Analysis: Azure Virtual Machines vs. Azure App Service**

**Azure Virtual Machines (VMs)** 
**Advantages**:
1.	Full Control: Azure VMs offer complete control over the operating system, software installations, and configurations, making them ideal for scenarios requiring specific setups or unsupported software.
2.	Customizability: VMs are perfect for custom configurations, allowing for tailored environments to meet unique application requirements.
3.	Isolation: Dedicated environments ensure enhanced security and performance, providing a robust solution for sensitive applications.
**Disadvantages**:
1.	Management Overhead: VMs require regular updates, security patches, and ongoing maintenance, which can be resource-intensive.
2.	Complexity: Setting up and managing VMs can be complex, demanding a higher level of expertise and time investment.
3.	Cost: VMs can be more expensive, particularly when they are idle, as they incur costs regardless of usage.

**Azure App Service**
**Advantages**:
1.	Managed Service: Azure App Service handles infrastructure management, scaling, patching, and maintenance, significantly reducing operational burdens.
2.	Ease of Use: Simplifies the deployment and management process, making it accessible even for teams with limited technical expertise.
3.	Scalability: Built-in scaling features allow for seamless adjustment to varying traffic loads, ensuring optimal performance.
4.	Cost-Effective: More economical for applications with variable usage patterns, as costs are aligned with actual usage.
**Disadvantages**:
1.	Limited Control: Offers less control over the underlying infrastructure, which may be a limitation for applications requiring specific configurations.
2.	Compatibility: May not support all required software or configurations, potentially restricting certain application functionalities. 

**Decision Rationale**:
•	For this project, Azure App Service was chosen due to its ease of use, managed infrastructure, and scalability. This choice facilitates a streamlined deployment process and minimizes management overhead, allowing me to concentrate on application development and deployment. 

**Impact on Application and Infrastructure**:
Application Requirements and Infrastructure Control: Deploying the application on a Virtual Machine (VM) would provide extensive control over the infrastructure, enabling custom configurations and installations necessary for specific application requirements. This includes custom software, specific versions of dependencies, or advanced networking configurations. However, this approach demands significant management and maintenance of the underlying infrastructure.
Conversely, deploying the application using Azure App Service offers a managed environment with built-in scaling, monitoring, and security features. This reduces operational overhead and allows the development team to focus more on the application code rather than infrastructure management. However, it may have limitations in terms of custom configurations compared to a VM. 

**Additional Considerations**:
Scalability: Azure App Service provides superior scalability options, making it easier to handle variable traffic loads compared to a VM.
Maintenance: Utilizing Azure App Service reduces the need for manual updates and server maintenance, which is advantageous for smaller teams or projects with limited operational resources.
Compliance and Security: If the application has specific compliance or security requirements, deploying on a VM might offer more flexibility to implement custom security measures.



