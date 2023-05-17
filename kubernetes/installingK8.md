# INSTALLING K8

kubernetes is a command line tool which is used to manage cluster and applications running inside it - `kubectl`

to install kubernetes in linux we use the following commands:

```bash
curl -LO https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl
chmod +x ./kubectl
sudo mv ./kubectl /usr/local/bin/kubectl
```

to verify if your k8 is already installed in your machine you: `kubectl --version`

or `kubectl version --output=yaml`