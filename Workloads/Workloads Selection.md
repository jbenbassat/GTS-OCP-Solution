# **Workload Selection Guidance**

          !!! info "Page Owner: George Mobargha"
        
          !!! info "Sr. Solutions Architect - IBM and Red Hat Alliances "
          !!! info "This section discusses the leading use cases for NetApp storage solutions. Whilst we are focusing on containerised workloads and applications requiring persistent storage, the NetApp platform can be used in a hybrid fashion, hosting traditional vm-based and bare-metal workloads as well as containerised stateful applications. In this section we discuss the requirements for databses in general as well as SAP and general file-based workloads. Persistent storage (file and block) is provided via Trident which is the CSI dynamic storage provisioner and is discussed separately."             
    
          !!! info "Status"
              - [ ] Structure
              - [ ] Draft
              - [ ] Reviewed
              - [x] Ready
              - [ ] Published
        
          !!! info "Classification"
              - [] IBM Confidential
                  - [X] Public

## **Databases**

Choosing the right storage can make the difference in your database deployment. Develop applications faster, reduce costs by up to 60%, and perform online backups in minutes rather than hours while achieving the database performance and protection you need.

### Databases like smart storage

Databases are the foundation of your business.  performance, availability, and protection should be your highest priorities. NetApp storage can satisfy the performance and resilience required for your database deployment. The right storage includes the intelligence and automation needed to accelerate innovation with increased operational efficiency.

### **Your cloud storage must offer these features to help your business succeed.**

### Performance

Databases benefit from low latency, high IOPs, and high throughput storage to deliver the right application performance.

### Availability

Redundancy and high availability configurations protect against device failures to help keep your applications online.

### Durability

Service failure shouldn’t result in data loss, even in the cloud. You need storage that protects against data loss due to unplanned service outages.

### Protection

Data corruption, external threats, or accidental data loss are all reasons why the right protection is needed for your data.

### Agility

Application development workflows benefit from rapid iteration and parallel testing to innovate and reduce costs.

### Optimization

Increase database efficiency and automate common tasks to reduce risk caused by human error and to improve operational productivity.

### NetApp ONTAP makes the difference

ONTAP is the smart storage OS for your database of choice.  ONTAP delivers unmatched performance, availability, and protection. The advanced capabilities of ONTAP allow you to effortlessly scale capacity, improve resource utilization, and dramatically increase user productivity. You can deploy ONTAP on-premises on a range of engineered systems or as Cloud Volumes as a fully managed storage service or a user managed storage layer on your choice of cloud infrastructure.

- Dynamically change your storage SLA to instantly scale performance, up or down, up to 128 Mbps/TB and under 1 ms latency.

- Improve database uptime with guaranteed data availability and durability.

- Protect your data with in-place snapshot copies and instant recovery. Replicate to a remote location for backup and DR.

- Prevent unwanted data access with inline and data-at-rest encryption.

- Rapidly create hundreds of space efficient copies of production data in minutes rather than days to accelerate application development and perform parallel QA testing.

- Reduce risk and operational overhead with intuitive management and RESTful APIs.


## SAP

One of the most anticipated tech transitions is the move to SAP S/4HANA. By 2027, SAP ends support for non-HANA databases with its Enterprise Suite of software. For many, this transition will create an opportunity to move critical applications to the cloud.

The real benefits for SAP deployments do not come from infrastructure savings alone, but through accelerating projects, simplifying operations, and well-designed application integration. Choosing the right storage for your SAP deployment is essential to achieve your business goals.

#### Maximize performance

Tune performance and capacity of SAP ECC and S/4HANA at runtime with as lows as sub-millisecond latencies and up to 6 GiB/s throughput.

#### Increase uptime

Avoid the pain of downtime and the cost of data loss with guaranteed nine 9s of data durability.

#### Improve resilience

Benefit from five 9s minimum uptime and available RPO=0 configurations.

#### Protect confidently

Backup 8x faster and restore quickly with space efficient snapshots and available block level replication.

#### Accelerate to the cloud

Migrate to the cloud without changing code. Accelerate application development using space efficient copies to enable rapid prototyping and parallel testing.

#### Simplify operations

Shrink your costs with data management automation and cold data tiering for up to 70% cloud storage savings.

#### Benefits - Production HANA

- High performance and highly available enterprise block or NFS service to share files across all SAP S/4HANA instances
- Accelerate projects by delivering prototypes or new landscapes in minutes
- Improved resiliency via space efficient snapshots that do not impact performance

#### Benefits - Shared Files

- Enterprise grade NFS and SMB proven for thousands of SAP deployments
- Built in SnapShot copies for automated backups · Simplified operations resulting in up to 50% savings
- Automated synchronization within the cloud, between clouds and hybrid setups.
- Efficient data reduction capabilities shrink cloud storage costs by as much as 70%

#### Benefits - Application Dev/Test

- Efficient replication from on-premises for DR or to populate for development or testing
- Rapid copies to accelerate development by up to 70%.
- Improved development, test and migration projects with enterprise grade data management in the cloud
- Support for hybrid operations using Cloud Volumes ONTAP with automated synchronization within the cloud, between clouds and hybrid setups.
- Simplified operations resulting in up to 50% savings

#### Benefits - Disaster recovery

- Cost efficient storage-based replication from on-premises for DR avoids additional application servers in the cloud
- Eliminate risk by performing efficient DR testing using native cloning technology without breaking the mirror.
- Leverage DR replication image for additional development/test system copies
- Application-consistent HANA backups leveraging Snapshot copies with zero performance load

## File Shares

NetApp ONTAP is the right storage OS choice for hosting SAP. ONTAP delivers unmatched performance, availability, and protection for Linux and Windows clients. With ONTAP you can effortlessly scale capacity, improve resource utilization, and dramatically increase user productivity. Deploy ONTAP as Cloud Volumes as a fully managed storage service or a user managed storage layer on your choice of cloud infrastructure.

1. Access files via NFS (v3, v4.1) or SMB/CIFS and reduce management overhead with intuitive management and RESTful APIs.
2. Prevent unwanted access with inline and data-at-rest encryption and address strict retention needs with WORM file locking.
3. Rapidly create space efficient copies of production or other data to accelerate application development and QA testing.
4. Shrink your costs with efficient data reduction and cold data tiering for up to 70% cloud storage savings.
5. Improve uptime and performance with guaranteed availability and durability SLAs and choice of three performance tiers in the cloud.
6. Protect your data with in-place snapshot copies and instant recovery. Replicate to a remote location for backup and DR.
