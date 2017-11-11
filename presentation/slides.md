title: Leveraging Kubernetes for Everyone
author:
  name: Stanley Zheng
  twitter: stanzheng
  url: http://stanzheng.com
output: index.html
controls: true

--

# Leveraging Kubernetes for Everyone*
## **see terms and conditions

--

### Hi!

- I work @<img src="https://www.homes.com/images/default/homescom_logo.png">
- Software Developer
- Started shipping apps in 2012
    - I ❤️ the Web
    - Volunteer for Code4HR.org
    - Co-Organizer for Norfolk.js

---

### Hi to you

<img src="https://media.giphy.com/media/3o7TKMt1VVNkHV2PaE/giphy.gif" height="60%" width="60%">

---




### What is Kubernetes?

- Open sourced in June 2014
- 1.0 in June 2015
- 1.8 tagged Sept 2017
- Founding Project of CNCF
<img src="https://www.cncf.io/wp-content/uploads/2017/10/cncf_color-1.png" width="100%">
- Major provides all support hosted Kubernetes

---

<!-- Feels more like this -->
All the open source projects!
<img src="https://raw.githubusercontent.com/cncf/landscape/master/landscape/CloudNativeLandscape_latest.jpg" width="100%">
- src https://github.com/cncf/landscape
---
### How does it help teams?
- Build faster, Ship Faster
- Reslient Containers
- Autoscaling Groups
- Save Money

---

## Preflight check
- Containers
- Multiple Nodes (3+)
- Docker Registry
- CI/CD Workflow
- Principals of https://12factor.net/


More at https://medium.com/@kelseyhightower/12-fractured-apps-1080c73d481c
---

<!-- Feels more like this -->
Expectation
<img src="https://media.giphy.com/media/3ov9jZvXjet1EE65MY/giphy.gif" width="100%">

---
<!-- Feels more like this -->
Reality
<img src="http://www.gifbin.com/bin/102010/1285930405_four-lions-bazooka-fail.gif" width="100%">

---

## Components
- pods
- labels
- replication controllers
- deployments
- services
- service discovery
- health checks
- environment variables
- namespaces
- volumes
- secrets
- logging
- jobs
- nodes

---
### YAML based Developer
<img src="https://i.imgur.com/wn96YUQ.png" width="100%"/>


---

# Starting with Kubernetes
---

## MiniKube

- Mimic Real Kubernetes
    - Able to build and iterate quickly
    - Supports ingress controller
    - Minikube dashboard
- Con
    - Not multi tenant
    - Not same API mirror across cloud providers
    - Not all addons supported
---

## Your team

Application that has a bunch of things Web Service
- Backend
- Database
- Frontend
- Reverse Proxy
- Caching

---
Typical application
<img src="https://qph.ec.quoracdn.net/main-qimg-5b8405bc2155362c88a5a817a1c47077" width="80%" height="80%"/>

---
Microservices?
<img src="https://www.ibm.com/developerworks/websphere/library/techarticles/1601_clark-trs/images/figure5.jpg" width="80%" height="60%"/>

---
Microservices!
<img src="https://i.pinimg.com/originals/98/1b/89/981b89570cb0eac2a5e6694468c09b4b.png" width="80%" height="60%"/>


---
Our Architecture
<img src="http://i.imgur.com/MIArQiP.png"/>
---

What's in Kubernetes?
<img src="https://cdn.thenewstack.io/media/2016/08/Kubernetes-Architecture-1024x637.png"  width="80%" height="60%"/>
---

## Kubernetes Overview

- <a href="http://gist-reveal.it/bit.ly/k8s-miniarch#/18"> Architecture Diagram <a/>
- <a href="http://gist-reveal.it/bit.ly/k8s-miniarch"> Components</a>
- <a href="http://gist-reveal.it/bit.ly/k8s-kubectl"> Using the Command line</a>

---

## More Resources
- <a href="https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615">Udacity Course</a>
- <a href="https://github.com/kelseyhightower/kubernetes-the-hard-way"> Kubernetes the Hard Way - Kelsey Hightower</a>
- <a href="https://kubernetes.io/docs/user-guide/kubectl-cheatsheet/"> Kubernetes Cheat Sheet </a>
---

## Thank you

<!-- Going Minions  -->
<img src="https://i.makeagif.com/media/3-03-2014/rytKR2.gif" width="100%">
