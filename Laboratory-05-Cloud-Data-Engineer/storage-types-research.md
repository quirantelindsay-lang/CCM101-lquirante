# Types of Cloud Storage Research

## Comparison Table

| Storage Type | Description (How does it store data?) | Primary Use Case (What is it best used for?) | Cloud Provider Example |
| :--- | :--- | :--- | :--- |
| **Block Storage** | Stores data in raw, fixed-sized blocks managed by the server's operating system as a hard drive. | Best for operating systems, databases, and enterprise applications requiring low-latency access. | AWS EBS (Elastic Block Store) |
| **File Storage** | Stores data in a hierarchical file structure (files and folders) accessible over a network. | Best for shared network drives, centralized file sharing, and content management systems. | AWS EFS (Elastic File System) |
| **Object Storage** | Stores data as discrete objects containing the data itself, metadata, and a unique identifier in a flat namespace. | Best for storing massive amounts of unstructured data like images, videos, backups, and logs. | AWS S3 (Simple Storage Service) |

## Why Object Storage is the Best Choice
Object Storage is the ideal solution for the photo-sharing application because it is specifically designed to handle massive amounts of unstructured data like user-uploaded images. Unlike Block or File storage, it uses a highly scalable flat structure that allows for virtually infinite storage capacity without performance degradation. Additionally, it natively supports web-based access via APIs, making it seamless to integrate with a modern web application framework.
