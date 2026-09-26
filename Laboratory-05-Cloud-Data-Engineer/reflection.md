# Mission Reflection

**Name:** Edmund Glanida

**Course and Section:** BSIT 4-L

This laboratory helped me understand why object storage is useful for applications that need to store a large number of files. Object storage is better suited for storing millions of photos because it is designed for large amounts of unstructured data and can organize files as objects inside buckets. A traditional block storage hard drive is more suitable for systems that need disk-like storage rather than managing a large collection of independent photos.

Using Docker made deploying the MinIO storage server easier because I could start the service with one command instead of manually installing and configuring all of its components. Docker also allowed MinIO to run inside a container with the required ports and environment variables.

A bucket is a container used to organize objects in object storage. In this activity, I created a bucket named `client-photos` and uploaded a test file to verify that the storage system was working.

Large enterprise companies can protect object storage data from physical server failures by keeping copies or replicas of data across different servers or locations. They can also use backups and redundancy so that a hardware failure does not cause the stored data to be permanently lost.

My confidence in navigating the Linux command line has also improved. I was able to use Docker commands, check the running container with `docker ps`, configure ports, and troubleshoot problems when the original MinIO image was unavailable. This activity gave me more practical experience with Linux, Docker, and cloud storage.