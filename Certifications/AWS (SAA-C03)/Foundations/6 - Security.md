When you build applications on AWS, managing security and compliance is a shared responsibility between AWS and you. To depict this shared responsibility, AWS created the shared responsibility model (see the following diagram). The distinction of responsibility is commonly referred to as security “of” the cloud compared to security “in” the cloud.

![[Capture d’écran 2023-05-12 à 12.01.54.png]]

### Customer responsibility
Customers, or anyone building on the cloud, are responsible for security in the cloud. When using any AWS service, you’re responsible for properly configuring the service and your applications, in addition to ensuring that your data is secure.

Your level of responsibility depends on the AWS service. Some services require you to perform all the necessary security configuration and management tasks, while other more abstracted services require you to only manage the data and control access to your resources.

Due to the varying levels of effort, customers must consider which AWS services they use and review the level of responsibility required to secure each service. They must also review how the shared security model aligns with the security standards in their IT environment, in addition to any applicable laws and regulations.

A key concept is that customers maintain complete control of their data and are responsible for managing the security related to their content.

This short summary of cloud security introduces core concepts only. Browse the **[Security Learning page](https://aws.amazon.com/security/security-learning/?pg=cloudessentials)** to learn more about key topics, areas of research, and training opportunities for cloud security on AWS.

### AWS responsibility
Being responsible for security of the cloud means that AWS protects and secures the infrastructure that runs the services offered in the AWS Cloud. AWS is responsible for:
-   Protecting and securing AWS Regions, Availability Zones, and data centers, down to the physical security of the buildings
-   Managing the hardware, software, and networking components that run AWS services, such as the physical servers, host operating systems, virtualization layers, and AWS networking components.