Oracle Cloud Infrastructure (Oci) services include 5 things : 
1. Compute : OCI compute Service consist of 5 components (bare metal, dedicated virtual hosts, virtual machine, container engines and functions).
2. Storage : Storage have a 2 types Storage Model and Storage Services. 
   Storage model : Computing on applications requires storage with certain specification, such as supports persistent and non-persistent storage.
   Storage services : There are 5 storage services supported by OCI (block volume, local NVME, file storage, object storage and archive storage).
   1. Block volume have a characteristics can be used for high computing purposes, data is stored on the device with fixed size blocks e.g. 512 bytes.
   2. Local NVME havhe a characteristics temporary storage required by applications that require very low latency and high processing, typically used on NoSQL databases (eg: MongoDB, Redis).
   3. File storage have a characteristics suitable for applications that can run on different OS, can be accessed over the network, generally doesn't require additional software.
   4. Object storage have a characteristics all data is managed like an object, object are stored in the storage bucket, can be used to store data from many sources.
   5. Archive storage characteristics(cold) : storage costs 10 time less than standard tier. minimum data storage 90 days.
3. Networking : VCN is an infrastructures as s Service (IaaS) service. VCN is a network owned by VM. VCN allow user to manage existing network in a cloud environment. we can set the IP address, create subnets and route tables, also configure the firewall.
4. Identity and Access Management (IAM) : Can control who has access to  your cloud resources, and type of access they have, and specific resources.IAM policies are document that define who and how can be used to access resources.
5. Database cloud service : The Oracle Autonomous Database service frees database administrators from operational task even when the database is deployed in the cloud. 
