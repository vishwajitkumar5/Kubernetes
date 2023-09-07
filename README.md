Kubernetes Architecture


![Untitled-2021-06-14T092850](https://github.com/vishwajitkumar5/Kubernetes/assets/36007696/4eb02cd7-c97d-461b-84b3-c67a3c45a1fc)


There are two types 

1.control plane

2.Data plane

Data Plane
==========================
In Data plane there are 

Container

Kubelet

kube proxy

Container: 
==========

It is responsible for running your containeers.

kubelet:
========
It is basically responsible for creation of pods.It will basically ensure that the pod is always in the running state.If it is not in running state it will takes the necessary action using the kubernetes controll plane.

kube proxy:
===========
It is basically responsible for the networking like generating the IP address or load balancing basically it uses IP TABLE in your linux machines.
