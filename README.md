# DockerEcosystem
=================

A running list of Docker's Ecosystem of tools. Contributions to the list welcome (send me a PR).

### Table of Contents
* **[Composition, Scheduling and Orchestration] (#orchestration)**
* **[Networking] (#networking)**
* **[Data and Volumes] (#data-and-volumes)**
* **[Docker Container Layers] (#docker-container-layers)**
* **[Base Linux Images] (#base-linux-images)**
* **[Graphical User Interface] (#graphical-user-interface)**
* **[Hosting] (#hosting)**
* **[Specifications and Standards](#specifications-and-standards)**
* **[Patterns] (#patterns)**
* **[Docker Development] (#docker-development)**
* **[Alternatives Container Engines] (#alternatives-container-engines)**



Composition, Scheduling and Orchestration 
=========================================
*Orchastration space quite expansive, could do with splitting into subsections....*
* Docker's tools in this space [Docker machine,swarm and compose] ( http://blog.docker.com/2015/02/orchestrating-docker-with-machine-swarm-and-compose/)
* [Fig] (http://www.fig.sh/). Now Docker Compose see below
* [Docker Compose] (https://github.com/docker/compose). Define multi-container apps 
* [Docker Machine] (https://github.com/docker/machine). Automate provision of Docker on remote hosts 
* [Docker Swarm] (https://github.com/docker/swarm/). Cluster/Pool Docker Hosts as vHost
* [Packer](https://www.packer.io/) not strictly Docker specific, but definitly used in this space
* [Crane](https://github.com/michaelsauter/crane)
* [Shipyard](https://github.com/shipyard/shipyard)
* [Maestro](https://github.com/toscanini/maestro) formerly dockermix
* [Fleet] (https://github.com/coreos/fleet) low level Docker clustering
* [Google Kubernettes] (http://kubernetes.io/). Multi-container app definition and clustering 
* [Apache Mesos] (http://mesos.apache.org/). Clustering and Orchastration 
* [Panamax] (http://panamax.io/). Define multi-container apps 
* [Dray] (https://github.com/CenturyLinkLabs/dray). Containerized workflow management
* [Marathon] (https://mesosphere.github.io/marathon/docs/native-docker.html) container scheduler
* [Nextflow] (http://www.nextflow.io/). Enables self contained, reproducible computational pipelines 
* [Tiller] (https://github.com/markround/tiller). Config file generation 

Networking
==========
* [Weave] (http://weave.works/) container networking across multiple hosts
* [SocketPlane] (http://socketplane.io/) Open Vsqitch + Docker networking
* [Flannel] (https://github.com/coreos/flannel) is an etcd backed network fabric for containers
* [Calico] (http://www.projectcalico.org/getting-started/docker/) L3 fabric solution for Linux Containers

Service Discovery
=================
* [Skydock] (https://github.com/crosbymichael/skydock)
* [Registrator] (https://github.com/gliderlabs/registrator)

Data and Volumes
================
* [Flocker] (https://docs.clusterhq.com/en/0.3.2/gettingstarted/)
* [Ferry] (http://ferry.opencore.io/en/latest/) ?move?

Docker Container Layers
===============================
* [Docker Squash] (https://github.com/jwilder/docker-squash)

Logging
=======
* [CAdvisor] (https://github.com/google/cadvisor) Cgroups statistics
* [Syslog] (https://github.com/jpetazzo/syslogdocker). Syslog container 

Base Linux Images
=================
These are linux distros specifically stripped down for running containerized processes. 
*I may later subset this section based on the mechanism for PID=1*
* [Ubuntu Snappy] (http://www.ubuntu.com/cloud/tools/snappy)
* [Project Atomic] (http://www.projectatomic.io/) 
* [Rancher] (http://rancher.com/)
* [CoreOS] (https://coreos.com/using-coreos/containers/)
* [Phusion] (http://phusion.github.io/baseimage-docker/)

Graphical User Interface
========================
* [Kitematic] (https://kitematic.com/)
* [DockerUI] (https://github.com/crosbymichael/dockerui)
* [Shipyard](https://github.com/shipyard/shipyard)

Hosting
=======
* [Tutum] (https://www.tutum.co/) deploy containers to VMs from a wide range of cloud providers
* [Google Container Engine] (https://cloud.google.com/container-engine/) deploy containers directly to GCE powered by Kubernetes
* [Amazon Container Service] (http://aws.amazon.com/ecs/) deploy containers directly to EC2
* [Rancher] (http://rancher.com/rancher-io/)
* [Quay](https://quay.io)
* [Orchard] (https://www.orchardup.com/)
* [Octohost] (http://octohost.io/) mini Docker PaaS


Specifications and Standards
============================
[Common Workflow Language](https://github.com/common-workflow-language/common-workflow-language)
[Bioboxes](https://github.com/bioboxes/rfc)

Patterns
========
* [Grand Ambassador] (http://container42.com/2014/08/28/docker-grand-ambassador/)
* [8 Docker patterns] (http://www.hokstad.com/docker/patterns)

Docker Development
===========
* [PowerStrip] (https://github.com/ClusterHQ/powerstrip)
* [Docker-Py] (https://github.com/docker/docker-py)

Alternative Container Engines
==============================
* [Ubuntu LXD] (http://www.ubuntu.com/cloud/tools/lxd)
* [CoreOS Rocket] (https://coreos.com/blog/rocket/)
