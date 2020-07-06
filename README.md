# Awesome-Kubernetes

A curated list for awesome kubernetes resources
Inspired by [@sindresorhus' awesome](https://github.com/sindresorhus/awesome) and [@ramitsurana' awesome](https://github.com/ramitsurana/awesome-kubernetes)

Why another awesome list? Folks in Indonesia are mostly new to Kubernetes, the already existing one is super extensive and new comers usually get confused. As the community grows, we will start small and learn as we go through this repo. Would produce more resources in Bahasa Indonesia as well to cover wider audience in the community.

# Menu

- [Awesome-Kubernetes](#awesome-kubernetes)
- [Starting Point](#starting-point)
- [Articles in Bahasa Indonesia](#articles-in-bahasa-indonesia)
- [Try It](#try-it)
- [Main Resources](#main-resources)
- [Advanced Topics](#advanced-topics)
- [Theoretical Topics](#theoretical-topics)
- [Reading List](#reading-list)

---

# Starting Point

_Good for new folks learning Kubernetes_

- [Kubernetes Comics](https://cloud.google.com/kubernetes-engine/kubernetes-comic/)
- [Kubernetes 101: Pods, Nodes, Containers, and Clusters](https://medium.com/google-cloud/kubernetes-101-pods-nodes-containers-and-clusters-c1509e409e16)
- [Kubernetes Tutorial](https://kubernetes.io/docs/tutorials/)

---

# Try It

- [Minikube (Personal Cluster on Your Local Machine)](https://kubernetes.io/docs/setup/minikube/)
- [Google Kubernetes Engine (Free credit 300\$ USD)](https://cloud.google.com/free/)
- [Kubeadm (Basic Setup for Kubernetes)](https://labs.play-with-k8s.com)

---

# Main Resources

- [Kubernetes Documentation](https://kubernetes.io/docs/home/)

---

# Advanced Topics

- [Helm Charts](https://helm.sh)
  - [Helm Tutorial](https://github.com/muffin87/helm-tutorial)
  - [Awesome Helm](https://github.com/cdwv/awesome-helm)
  - [Deploying Applications with Helm](https://cloudacademy.com/blog/deploying-kubernetes-applications-with-helm/)
  - [Using Helm to Deploy Kubernetes](https://daemonza.github.io/2017/02/20/using-helm-to-deploy-to-kubernetes/)
  - [Writing a Helm Chart](https://www.influxdata.com/blog/packaged-kubernetes-deployments-writing-helm-chart/)
- [Istio: Service Mesh](https://istio.io/)
  - [Traffic Management](https://istio.io/docs/concepts/traffic-management/)
  - [Security](https://istio.io/docs/concepts/security/)
  - [Policies and Telemetry](https://istio.io/docs/concepts/policies-and-telemetry/)
  - [Performance and Scalability](https://istio.io/docs/concepts/performance-and-scalability/)
  - [Setup in Kubernetes](https://istio.io/docs/setup/kubernetes/)
  - Example
    - [Bookinfo Application](https://istio.io/docs/examples/bookinfo/)
    - [Advanced Egress Traffic Control](https://istio.io/docs/examples/advanced-egress/)
    - [Enabling Multicluster](https://istio.io/docs/examples/multicluster/)
- CI/CD
  - [GitLab](https://about.gitlab.com/solutions/kubernetes/)
    - [Connecting GitLab with a Kubernetes cluster](https://docs.gitlab.com/ee/user/project/clusters/)
    - [How to set up Gitlab CI/CD with Google Cloud Container Registry and Kubernetes](https://medium.com/@davivc/how-to-set-up-gitlab-ci-cd-with-google-cloud-container-registry-and-kubernetes-fa88ab7b1295)
    - [Deploying to Google Kubernetes Engine from Gitlab CI](https://medium.com/john-lewis-software-engineering/deploying-to-google-kubernetes-engine-from-gitlab-ci-feaf51dae0c1)
    - [Deploying to Kubernetes using Gitlab CI and werf](https://werf.io/documentation/guides/gitlab_ci_cd_integration.html)
  - Jenkins
    - [Configuring CI/CD on Kubernetes with Jenkins](https://medium.com/containerum/configuring-ci-cd-on-kubernetes-with-jenkins-89eab7234270)
    - [Continuous Deployment to Kubernetes Engine using Jenkins](https://cloud.google.com/solutions/continuous-delivery-jenkins-kubernetes-engine)
- Networking
  - [IPVS-Based In-Cluster Load Balancing Deep Dive](https://kubernetes.io/blog/2018/07/09/ipvs-based-in-cluster-load-balancing-deep-dive/)
- Avoiding Outages
  - [Disruptions](https://kubernetes.io/docs/concepts/workloads/pods/disruptions/)
  - [Specifying a Disruption Budget for your Application](https://kubernetes.io/docs/tasks/run-application/configure-pdb/)
- Managing Resources
  - [Kubernetes best practices: Resource requests and limits](https://cloud.google.com/blog/products/gcp/kubernetes-best-practices-resource-requests-and-limits)
  - [Configure Default Memory Requests and Limits for a Namespace](https://kubernetes.io/docs/tasks/administer-cluster/manage-resources/)
- Cluster Federation
  - [kubernetes/federation](https://github.com/kubernetes/federation)
  - [Federation](https://kubernetes.io/docs/concepts/cluster-administration/federation/)
  - [Set up Cluster Federation with Kubefed](https://kubernetes.io/docs/tasks/federation/set-up-cluster-federation-kubefed/)
  - [Cross-cluster Service Discovery using Federated Services](https://kubernetes.io/docs/tasks/federation/)
  - [Kubernetes Federation Evolution](https://kubernetes.io/blog/2018/12/12/kubernetes-federation-evolution/)
  - [Cluster Federation and Global Load Balancing on Kubernetes and Google Cloud](https://medium.com/google-cloud/planet-scale-microservices-with-cluster-federation-and-global-load-balancing-on-kubernetes-and-a8e7ef5efa5e)
  - [Experimenting with Cross Cloud Kubernetes Cluster Federation](https://medium.com/google-cloud/experimenting-with-cross-cloud-kubernetes-cluster-federation-dfa99f913d54)
- Secret Management
  - [Vault](https://www.vaultproject.io/)

---

# Theoretical Topics

**Distributed System**

- [Large-scale cluster management at Google with Borg](https://pdos.csail.mit.edu/6.824/papers/borg.pdf)
- [The Chubby lock service for loosely-coupled distributed systems](http://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)

**Consensus Algorithm**

- [In Search of an Understandable Consensus Algorithm](web.stanford.edu/~ouster/cgi-bin/papers/raft-atc14)
- [Single Degree Paxos](https://mwhittaker.github.io/blog/single_decree_paxos/)
- [Raft Algorithm](https://ramcloud.stanford.edu/wiki/download/attachments/11370504/raft.pdf)

---

# Reading List

- [CNCF Books](https://github.com/cncf/ambassadors/blob/master/BOOKS.md)
- [Heptio Reading List](https://heptio.com/resources/ebooks/)

---

# Video

- [TGI Kubernetes](https://heptio.com/resources/tgik/)

---

# Articles in Bahasa Indonesia

_Great Kubernetes articles written in Bahasa Indonesia_

- [Pathfinder: Membangun Container Orchestrator Sendiri](https://medium.com/pujanggateknologi/pathfinder-membangun-container-orchestrator-sendiri-634eeeb3a0b) by [Giovanni Sakti](https://twitter.com/giosakti)
- [Kubernetes ConfigMap pada Aplikasi Dinamis](https://medium.com/pujanggateknologi/kubernetes-configmap-pada-aplikasi-dinamis-dce2d38a1040) by [Reyhan Sofian](https://github.com/reyhansofian)
- [Kabel Terhubung di Jaringan Kontainer](https://medium.com/pujanggateknologi/kabel-terhubung-di-jaringan-kontainer-ae46208cde30) by [Giri Kuncoro](https://twitter.com/girikuncoro)
