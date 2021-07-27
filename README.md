# kubernetes

![image](https://user-images.githubusercontent.com/44415163/127106142-8e474a1b-5587-4d80-8ca3-aa28f567153d.png)

kubeadm is a tool that enables Kubernetes administrators to quickly and easily bootstrap minimum viable clusters that are fully compliant with Certified Kubernetes guidelines.

####                                          Kubernetes High Availability Cluster

  ![image](https://user-images.githubusercontent.com/44415163/127106197-6e2df155-6637-4726-ac42-aab948556f99.png)
  
  

                                       Fig 1.1 Kubernetes High Level Cluster Diagram.

##### Hardware Requirements:
*	Three machines for Master Nodes.
*	Three machines for worker Nodes.
*	Full network connectivity between all machines in the cluster.
*	Sudo privileges on all the nodes in the system.
*	SSH access from one device in the system.
*	Kubeadm and kubelet installed on all the machines. Kubectl is optional.

##### Nodes Configurations:
One or more machines running one of:
*	Ubuntu 16.04+
*	Debian 9
*	CentOS 7
*	RHEL 7
*	Fedora 25/26 (best-effort)
*	HypriotOS v1.0.1+
*	Container Linux (tested with 1800.6.0)
*	2 GB or more of RAM per machine (any less will leave little room for your apps)
*	2 CPUs or more
*	Full network connectivity between all machines in the cluster.
*	Unique hostname, MAC address, and product_uuid for every node. 
•	Certain ports are open on your machines. See here for more details.
•	Swap disabled. You MUST disable swap in order for the kubelet to work properly.
