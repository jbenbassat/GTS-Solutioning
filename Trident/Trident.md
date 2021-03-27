## NetApp Trident 

### Introduction to NetApp Trident

Trident is a NetApp open-source and fully supported storage orchestrator for containers and Kubernetes distributions, **including Red Hat OpenShift**, hence works with the underlying Kubernetes storage framewok of CSI, Operator, PV and PVCs, enabling persistent storage capabilities that are based on NetApp storage.
Trident provides the ability to accelerate the DevOps workflow by allowing end users to provision and manage storage from their NetApp storage systems as a self-service, without requiring intervention from a storage administrator.

Trident works with the entire NetApp storage portfolio, including the NetApp ONTAP family of products, which is the storage technology NetApp has positioned for this solution, and is the standard supported NetApp technology by IBM GTS.

ONTAP based systems that can be considered viable option for this solution include: [AFF](https://www.netapp.com/data-storage/aff-a-series/), [FAS](https://www.netapp.com/data-storage/fas/), Cloud Volumes ONTAP [(CVO)](https://cloud.netapp.com/ontap-cloud) which is available in AWS, Azure and GCP, and ONTAP Select [(OTS)](https://www.netapp.com/data-management/software-defined-storage-ontap-select/) which is a SDS flavor of ONTAP and runs as virtual machine and can also be deployed in the [IBM Cloud on bare metal servers](https://cloud.ibm.com/docs/vmwaresolutions?topic=vmwaresolutions-netapp&mhsrc=ibmsearch_a&mhq=ONTAP%20Select). They all run the ONTAP Storage OS. 

For the scope of this solution, NetApp excludes the following storage services: ANF (Azure NetApp Files), CVS (Cloud Volumes Service) in GCP, AWS and Azure.

Together, ONTAP and Trident provide advanced data management capabilitiesat at the OpenShift platform level, and these capabilities can enable various use cases including those associated with multiple OpenShift clusters such as in DR, Cloud migration, hybrid cloud topologies, IBM Cloud Satellite, etc.


### Simplify the Consumption of Persistent Volumes (PV) in Openshift & Kubernetes

Persistent storage for stateful applications is a major inhibitor in the broad adoption of containers for the enterprise. NetApp was the first to offer a robust and [fully supported](https://netapp-trident.readthedocs.io/) open-source solution to address this gap and has since increased its investment and participation in the community and its partner ecosystem to shape the way containers approach data management. 

Container technology is an essential piece of [NetApp’s Data Fabric](https://www.netapp.com/us/info/what-is-data-fabric.aspx) vision. Trident enables customers to get the most out of their NetApp investment, simplifying the deployment of containers throughout the enterprise while protecting and managing data, wherever, whenever — across the fabric. 

Need a picture insert here showing Trident and OpenShift in the context of the Data Fabric... Jacky to provide.

### For additional information on Trident, please visit:

* [Getting started with Trident](https://netapp.io/persistent-storage-provisioner-for-kubernetes/)
* [NetApp Trident Public Github repository](https://github.com/NetApp/trident/blob/stable/v21.01/docs/kubernetes/index.rst)
