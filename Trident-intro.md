# Introduction to NetApp Trident
Trident is a NetApp open-source and fully supported storage orchestrator for containers and Kubernetes distributions, including Red Hat OpenShift hence works with the underlying Kubernetes storage framewok of CSI, Operator, PV and PVCs, enabling persistent storage capabilities that are based on NetApp storage.

It works with the entire NetApp storage portfolio, including the NetApp ONTAP portfolio, which is the storage technology NetApp has positioned for this solution, and is the standard supported NetApp technology by IBM GTS.

ONTAP based systems that can be considered viable option for this solution include: AFF, FAS, Cloud Volumes ONTAP [(CVO)](https://cloud.netapp.com/ontap-cloud) which is available in AWS, Azure and GCP and ONTAP Select [(OTS)](https://www.netapp.com/data-management/software-defined-storage-ontap-select/) which is SDS flavor of ONTAP and runs as virtual machine and can also be deployed in the [IBM Cloud on bare metal servers](https://cloud.ibm.com/docs/vmwaresolutions?topic=vmwaresolutions-netapp&mhsrc=ibmsearch_a&mhq=ONTAP%20Select). They all run the ONTAP Storage OS.
For the scope of this solution, NetApp excludes the following storage services: ANF (Azure NetApp Files), CVS (Cloud Volumes Service) in GCP, AWS and Azure.

Trident provides the ability to accelerate the DevOps workflow by allowing end users to provision and manage storage from their NetApp storage systems as a self-service, without requiring intervention from a storage administrator.


The storage architects and administrator can configure a number of storage backends based on project needs, and storage system models that allow for any number of advanced storage features, such as: compression, specific disk types, or QoS levels that guarantee a certain performance.
After they are defined, these backends can be leveraged by developers as part of their projects to create persistent volume claims (PVCs) and attach persistent storage to their containers on demand. Together, ONTAP storage features and Trident, provide advanced data managemt capabilities in OpenShift deployments.


