# DockerEcosystem
=================

A running list of Docker's Ecosystem of tools. Contributions to the list welcome.

### Table of Contents
**[Orchestration] (#orchestration)**
**[Networking] (#networking)**
**[Data and Volumes] (#data-and-volumes)**
**[Layers] (#layers)**
**[Development] (#development)**
**[Base Images] (#base-images)**
**[Thin Bases] (#thin-bases)**
**[Fat Bases] (#fat-bases)**
**[Patterns] (#patterns)**
**[Graphical User Interface] (#graphical-user-interface)**
**[Hosting] (#hosting)**
**[Alternative Docker Registries] (#alternative-docker-registries)**
**[Alternatives Container Engines] (#alternatives-container-engines)**


Orchestration
=============
*could do with splitting into subsections....*
* Docker's tools in this space [Docker machine,swarm and compose] ( http://blog.docker.com/2015/02/orchestrating-docker-with-machine-swarm-and-compose/)
* Fig (now Docker Compose) [Fig] (http://www.fig.sh/)
* Define multi-container apps [Docker Compose] (https://github.com/docker/compose)
* Automate provision of Docker on remote hosts [Docker Machine] (https://github.com/docker/machine)
* Cluster/Pool Docker Hosts as vHost [Docker Swarm] (https://github.com/docker/swarm/)
* Multi-container app definition and clustering [Google Kubernettes] (http://kubernetes.io/)
* Clustering and Orchastration [Apache Mesos] (http://mesos.apache.org/)
* Define multi-container apps [Panamax] (http://panamax.io/)
* Containerized workflow management [Dray] (https://github.com/CenturyLinkLabs/dray)
* Config file generation [Tiller] (https://github.com/markround/tiller)

Networking
==========
* [Weave] (http://weave.works/)
* [SocketPlane] (http://socketplane.io/)

Service Discovery
-----------------
* [Skydock] (https://github.com/crosbymichael/skydock)
* [Registrator] (https://github.com/gliderlabs/registrator)


Data and Volumes
================
* [Flocker] (https://docs.clusterhq.com/en/0.3.2/gettingstarted/)


Layers
======
* [Docker Squash] (https://github.com/jwilder/docker-squash)

Logging
=======
* Cgroups info [CAdvisor] (https://github.com/google/cadvisor)
* Instructions for Syslog container [Syslog] (https://github.com/jpetazzo/syslogdocker)

Base Images
===========
These are linux distros specifically stripped down for running containerized processes. 
*I may later subset this section based on the mechanism for PID=1*
* [Ubuntu Snappy] (http://www.ubuntu.com/cloud/tools/snappy)
* [Rancher] (http://rancher.com/)
* [CoreOS] (https://coreos.com/using-coreos/containers/)
* [Phusion] (http://phusion.github.io/baseimage-docker/)

Development
===========
* [PowerStrip] (https://github.com/ClusterHQ/powerstrip)

Patterns
========
* [Grand Ambassador] (http://container42.com/2014/08/28/docker-grand-ambassador/)
* [8 Docker patterns] (http://www.hokstad.com/docker/patterns)

Graphical User Interface
========================
* [Kitematic] (https://kitematic.com/)

Hosting
=======
* [Tutum] (https://www.tutum.co/)
* [Rancher] (http://rancher.com/rancher-io/)

Alternative Public Registries
=============================
* ?


Alternatives Container Engines
==============================
* [Ubuntu LXD] (http://www.ubuntu.com/cloud/tools/lxd)
* [CoreOS Rocket] (https://coreos.com/blog/rocket/)
