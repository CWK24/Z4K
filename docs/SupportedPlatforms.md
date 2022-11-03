# Supported Platforms

Zerto for Kubernetes can be deployed on multiple Kubernetes platforms.

| Platform                             | Version  |  CSI| Notes |
| ------------------------------------ |--|--- |--- |
| Amazon Elastic Kubernetes Service (Amazon EKS)|  | ebs-csi-node | Supported up to version 1.22  |
| Azure Kubernetes Service (AKS)|   |  csi-azuredisk-node   |  |
| Red Hat OpenShift | 4.6 and higher  |csi-rbdplugin  |  |
| Google Kubernetes Engine (GKE)|   | pdcsi-node | COS nodes are not supported. Therefore, Autopilot deployment is not supported.|  |
| HPE Ezmeral | 5.3 & 5.4 |csi-nodeplugin-kdf, pdcsi-node|  |
| IBM Cloud Kubernetes Service (IKS) |  | ibm-vpc-block-csi-node |   |
| Oracle Container Engine for Kubernetes (OKE) |   |csi-oci-node |Supported in combination with Rook. |
| VMware Tanzu  | VMware 6.7 | vsphere-csi-node |Supported in combination with Rook. |
|   | VMware 7.0u2 |vsphere-csi-node |Full native support. <br> Kubernetes 1.19.9\1.20.5 or higher (CSI Block device support) on top of Tanzu Kubernetes Grid (TKG) is supported.  ||

<span class="Note">Note: Z4K does not support XFS. </span>


![Keycloak_Option2_InitialAccessToken_Back](https://user-images.githubusercontent.com/100526941/199762234-1c6bd45b-6f1a-4215-92a8-37bde3463c17.png)


![Keycloak_Option2_SignIn](https://user-images.githubusercontent.com/100526941/199762298-9e3eb9b8-438d-44d5-9021-2ffd241a1f52.png)
