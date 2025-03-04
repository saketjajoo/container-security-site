# Tools for Attackers

## Container Attack Surface Assessment & Breakout

Useful tools to run inside a container to assess the sandbox that's in use, and exploit some common breakout issues.

* [amicontained](https://github.com/genuinetools/amicontained) -  will show you information about the container runtime and rights you have.
* [ConMachi](https://github.com/nccgroup/ConMachi/) - Pentester focused container attack surface assessment tool.
* [deepce](https://github.com/stealthcopter/deepce) - Docker Enumeration, Escalation of Privileges and Container Escapes 
* [botb](https://github.com/brompwnie/botb) - Container breakout assessment tool. Can automatically exploit common issues like the Docker socket mount.
* [keyctl-unmask](https://github.com/antitree/keyctl-unmask) - Tool that specifically focuses on grabbing kernel keyring entries from containers that allow the keyctl syscall

## Container Orchestration Tools

### RBAC Assessment Tooling

* [kubectl-who-can](https://github.com/aquasecurity/kubectl-who-can) - Tool that lets you ask "who can" do things in RBAC, e.g. who can get secrets.
* [rakkess](https://github.com/corneliusweig/rakkess) - Shows the RBAC permissions available to a user as a list
* [rback](https://github.com/team-soteria/rback) - tool for graphical representation of RBAC permissions in a kubernetes cluster.

### Kubernetes Security Auditing Tools

* [kube-bench](https://github.com/aquasecurity/kube-bench) - Tool to assess compliance with the CIS benchmark for various Kubernetes distributions.

### Kubernetes Penetration Testing Tool

* [kube-hunter](https://github.com/aquasecurity/kube-hunter) - Tool to test and exploit standard Kubernetes Security Vulnerabilities.
* [kubestrike](https://github.com/vchinnipilli/kubestrike) - Security auditing tool for Kubernetes looks at Authenticated and unauthenticated scanning.
* [peirates](https://github.com/inguardians/peirates) - Kubernetes container breakout tool
* [kdigger](https://github.com/quarkslab/kdigger) - Kubernetes breakout/discovery tool

### Kubelet Tooling

* [kubeletctl](https://github.com/cyberark/kubeletctl) - This is a good tool to automate the process of assessing a kubelet instance. If the instance is vulnerable it can also carry out some exploit tasks.

### etcd Tooling

* [auger](https://github.com/jpbetz/auger) - Tool for decoding information pulled directly from the etcd database.

### Container Registry Tooling

* [reg](https://github.com/genuinetools/reg) - Tool for interacting with Container registries
* [regclient](https://github.com/regclient/regclient) - Another tool for interacting with container registries
* [go-pillage-registries](https://github.com/nccgroup/go-pillage-registries) - Tool to search the manifests and configuration for images in a registry for potentially sensitive information.

### Training Tools

If you're looking to practice with some of the tools here, in a safe environment, there are projects to help with that.

* [Kube Security Lab](https://github.com/raesene/kube_security_lab) - Basic set of Kubernetes security scenarios implemented in Ansible with Kind.
* [Kubernetes Simulator](https://github.com/kubernetes-simulator/simulator) - AWS based Kubernetes cluster environment with different vulnerability scenarios.
* [Kubernetes Goat](https://github.com/madhuakula/kubernetes-goat) - Focuses on vulnerable deployments on top of an existing cluster. Also available on line [with Katacoda](https://katacoda.com/madhuakula/scenarios/kubernetes-goat)