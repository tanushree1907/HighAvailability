
# Study of High Availability Approaches in Public Cloud Environment 

In today's digital era, ensuring uninterrupted access to critical applications and services is essential for organizations, especially in the rapidly evolving telecommunications sector. With telecom operators migrating core network functions to public cloud infrastructures, achieving high availability (HA) has become crucial for maintaining customer trust and operational efficiency.

This project focuses on studying and implementing various high-availability strategies within a cloud environment, leveraging Google Cloud's robust infrastructure. The objective was to enhance application redundancy, minimize downtime, and ensure seamless service delivery during network disruptions.

Key components of the project included:

1. Cloud Infrastructure Setup: Creation and configuration of critical network components and compute instances, organized into primary and failover instance groups.
2. Failover Policy Implementation: Development of a failover mechanism to ensure uninterrupted service during disruptions.
3. Failover Testing: Evaluation of three failover techniques—load balancer configuration, alias IP failover, and route modification.

The project assessed the performance of these techniques by analyzing average latency and efficiency across all scenarios. The findings emphasized the importance of automation in achieving application resilience and optimizing network reliability.

This study provides valuable insights into the effectiveness of different failover mechanisms in reducing service downtime, contributing to the development of robust, high-availability solutions in public cloud environments.


## Acknowledgements

 I extend my heartfelt gratitude to all who supported me in completing this project.
I sincerely thank Hardik Bavishi for granting me the opportunity to work on this project as part of his team at Jio Platforms Limited, and Gaurav Sharma for his dedicated guidance and invaluable insights throughout the project.
Special thanks to Kapil M Malviya, Medha Surendran, and Kundrapu Abhinav Sadwik for their expertise and constant encouragement, and to Sunita Autade for her unwavering support and belief in my abilities.
This project would not have been possible without their collective contributions, for which I am deeply grateful.


## References

Google Cloud SDK (gcloud CLI) Documentation:
• Google Cloud SDK: https://cloud.google.com/sdk/docs
• gcloud CLI Overview: https://cloud.google.com/sdk/gcloud/reference
Google Compute Engine Documentation:
• Overview of Google Compute Engine: https://cloud.google.com/compute/docs
• Managed Instance Groups: https://cloud.google.com/compute/docs/instance-
groups/manage-instance-groups
• Load Balancing Documentation: https://cloud.google.com/load-balancing/docs
Google Cloud Networking Documentation:
• VPC Documentation: https://cloud.google.com/vpc/docs
• Firewall Rules: https://cloud.google.com/vpc/docs/firewalls 
Google Cloud Monitoring Documentation:
• Monitoring and Logging: https://cloud.google.com/monitoring/docs
Microsoft Azure Documentation:
• Azure Overview: https://docs.microsoft.com/en-us/azure/
• Azure Virtual Machines: https://docs.microsoft.com/en-us/azure/virtual-machines/
• Azure Load Balancer: https://docs.microsoft.com/en-us/azure/load-balancer/
• Azure Resource Manager: https://docs.microsoft.com/en-us/azure/azure-resource-manager/
Cloud Architecture and Best Practices:
• Google Cloud Best Practices: https://cloud.google.com/docs/architecture
• Azure Architecture Centre: https://docs.microsoft.com/en-us/azure/architecture/