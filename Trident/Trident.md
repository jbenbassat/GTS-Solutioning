## NetApp Trident test jacky

!!! info "Page Owner: Troy Hess"

!!! info "Solutions Engineer - IBM and RedHat Alliances "

!!! info "Status"
- [X] Structure
- [X] Draft
- [ ] Reviewed
- [ ] Ready
- [ ] Published

!!! info "Classification"
- [ ] IBM Confidential
- [X] Public

### What is Trident?

NetApp Trident is a Container Storage Interface (CSI) compliant storage orchestrator that can provision persistent storage for your containerized applications across all popular NetApp storage platform, including: traditional on-prem [FAS](https://www.netapp.com/data-storage/fas/) or [AFF](https://www.netapp.com/data-storage/aff-a-series/) storage devices, our Software-Defined-Storage, [ONTAP Select](https://www.netapp.com/data-management/software-defined-storage-ontap-select/), which runs ONTAP software on your commodity hardware or in the [IBM Cloud](https://cloud.ibm.com), or in the public cloud, such as [Azure NetApp Files](https://cloud.netapp.com/azure-netapp-files) or [Cloud Volumes ONTAP](https://cloud.netapp.com/ontap-cloud) for AWS or  Google Cloud.

### Simplify the Consumption of Persistent Volumes (PV) in Openshift & Kubernetes

Persistent storage for stateful applications is a major inhibitor in the broad adoption of containers for the enterprise. NetApp was the first to offer a robust and [fully supported](https://netapp-trident.readthedocs.io/en/stable-v21.01/support/requirements.html#requirements) open-source solution to address this gap and has since increased its investment and participation in the community and its partner ecosystem to shape the way containers approach data management. 

Container technology is an essential piece of [NetApp’s Data Fabric](https://www.netapp.com/us/info/what-is-data-fabric.aspx) vision. Trident enables customers to get the most out of their NetApp investment, simplifying the deployment of containers throughout the enterprise while protecting and managing data, wherever, whenever — across the fabric. 

[Trident](https://github.com/netapp/trident) is a Container Storage Interface (CSI) compliant dynamic storage orchestrator that enables consumption and management of storage resources across all popular NetApp storage platforms. It natively integrates with Kubernetes to dynamically provision persistent volume requests on demand. Additionally, Trident has a REST interface that can be used by any application to create and manage storage across the configured resources. 

NetApp Trident is a Container Storage Interface (CSI) compliant storage orchestrator that can provision persistent storage for your containerized applications across all popular NetApp storage platform, including: traditional on-prem [FAS](https://www.netapp.com/data-storage/fas/) or [AFF](https://www.netapp.com/data-storage/aff-a-series/) storage devices, our Software-Defined-Storage, [ONTAP Select](https://www.netapp.com/data-management/software-defined-storage-ontap-select/), which runs ONTAP software on your commodity hardware or in the [IBM Cloud](https://cloud.ibm.com), or in the public cloud, such as [Azure NetApp Files](https://cloud.netapp.com/azure-netapp-files) or [Cloud Volumes ONTAP](https://cloud.netapp.com/ontap-cloud) for AWS or  Google Cloud.

### For additional information on Trident, please visit:

* [Getting started with Trident](https://netapp.io/persistent-storage-provisioner-for-kubernetes/)
* [NetApp Trident Public Github repository](https://github.com/NetApp/trident/blob/stable/v21.01/docs/kubernetes/index.rst)
