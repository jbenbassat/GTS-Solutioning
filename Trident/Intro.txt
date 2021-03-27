Trident is a NetApp open-source and fully supported storage orchestrator for containers and Kubernetes distributions, including Red Hat OpenShift. 
It works with the entire NetApp storage portfolio, including the NetApp ONTAP portfolio which is the storage technology NetApp has positioned for this solution as ONTAP is a standard for IBM GTS.
ONTAP based systems that can be considered viable option for this solution include: AFF, FAS, Cloud Volumes ONTAP (CVO) and ONTAP Select (OTS). They all run the ONTAP Storage OS.
For the scope of this solution, NetApp excludes the following storage services: ANF (Azure NetApp Files), CVS (Cloud Volumes Service) in GCP, AWS and Azure.
Trident provides the ability to accelerate the DevOps workflow by allowing end users to provision and manage storage from their NetApp storage systems as a self-service, without requiring intervention from a storage administrator.
The storage architects and administrator can configure a number of storage backends based on project needs, and storage system models that allow for any number of advanced storage features, such as: compression, specific disk types, or QoS levels that guarantee a certain performance.
After they are defined, these backends can be leveraged by developers as part of their projects to create persistent volume claims (PVCs) and attach persistent storage to their containers on demand.
