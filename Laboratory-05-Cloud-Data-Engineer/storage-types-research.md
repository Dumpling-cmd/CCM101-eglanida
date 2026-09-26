# Cloud Storage Types Research

**Name:** Edmund Glanida

**Course and Section:** BSIT 4-L

## Comparison of Cloud Storage Types

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks that can be attached to a virtual machine like a disk drive. | Operating systems, databases, and applications that need low-latency disk access. | AWS EBS |
| File Storage | Stores data as files in folders and allows multiple systems or users to access a shared file system. | Shared files, documents, and applications that require a common file system. | AWS EFS |
| Object Storage | Stores data as objects together with metadata and a unique identifier inside a bucket. | Images, videos, backups, documents, and other large amounts of unstructured data. | Amazon S3 |

## Recommendation for the Client

Object Storage is the best choice for storing user-uploaded images because it is designed for large amounts of unstructured data such as photos and videos. It stores files as objects inside buckets and can scale as the number of uploaded images increases. This makes it suitable for a photo-sharing application that may eventually store millions of images.