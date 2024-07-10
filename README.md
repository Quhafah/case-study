# case-study

Step 1: Install kops and kubectl
To set up your Kubernetes cluster, you need to install kops and kubectl on your local machine. Follow the steps below:

Install kops
Download the kops binary:
```bash
curl -LO https://github.com/kubernetes/kops/releases/download/v1.21.0/kops-linux-amd64
Make the kops binary executable:
chmod +x kops-linux-amd64
Move the kops binary to a directory in your PATH:
sudo mv kops-linux-amd64 /usr/local/bin/kops
Install kubectl
Download the kubectl binary:
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
Make the kubectl binary executable:
chmod +x kubectl
Move the kubectl binary to a directory in your PATH:
sudo mv kubectl /usr/local/bin/kubectl
```
By following these steps, you will have kops and kubectl installed on your local machine, ready to manage your Kubernetes cluster.

