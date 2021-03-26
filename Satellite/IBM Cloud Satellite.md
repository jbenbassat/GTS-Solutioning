## IBM Cloud Satellite

[IBM Cloud Satellite](https://www.ibm.com/cloud/satellite) provides a distributed cloud capability,  empowers businesses to realize the full business value of hybrid cloud, putting workloads wherever they need them, and deploying and running apps consistently across any on-premises, edge computing, and public cloud environment.

IBM Cloud Satellite starts with creating a **Location** from your IBM Cloud account and selecting an [IBM Cloud Region](https://cloud.ibm.com/docs/satellite?topic=satellite-sat-regions#understand-supported-regions) you want to use to manage your location. A Satellite location can be an edge location, on-prem datacenter or any public cloud where you run and extend IBM Cloud services. Your location will be made up of hosts (VMs, bare metal servers, etc.) which will serve as compute nodes assigned and attached to your Satellite location control plane.

Once your location is setup, you can create Satellite-enabled services, such as a **Red Hat OpenShift** Cluster. Using Red Hat OpenShift ensures applications and workloads are completely self-contained and able to serve requests. OpenShift ensures a constent developer experience in building and running apps.

Many of these containerize applications require persistent storage. This is where NetApp [Trident](https://netapp-trident.readthedocs.io/en/stable-v21.01/introduction.html) comes in. NetApp Trident is a Container Storage Interface (CSI) compliant storage orchestrator that can provision persistent storage for your containerized applications across all popular NetApp storage platform, including: traditional on-prem [FAS](https://www.netapp.com/data-storage/fas/) or [AFF](https://www.netapp.com/data-storage/aff-a-series/) storage devices, our Software-Defined-Storage, [ONTAP Select](https://www.netapp.com/data-management/software-defined-storage-ontap-select/), which runs ONTAP software on your commodity hardware or in the [IBM Cloud](https://cloud.ibm.com), or in the public cloud, such as [Azure NetApp Files](https://cloud.netapp.com/azure-netapp-files) or [Cloud Volumes ONTAP](https://cloud.netapp.com/ontap-cloud) for AWS or  Google Cloud.

To learn more about the Trident storage orchestrator, visit these links:

* [What is Trident?](https://netapp-trident.readthedocs.io/en/stable-v21.01/introduction.html)
* [Getting started with Trident](https://netapp.io/persistent-storage-provisioner-for-kubernetes/)
* [NetApp Trident Public Github repository](https://github.com/NetApp/trident/blob/stable/v21.01/docs/kubernetes/index.rst)