# Microsoft Bedrock with Hyper-V on minikube

## Prerequisits

Note: [Chocolatey](https://chocolatey.org/) will make the setup process easier by a lot and is recommended

### Terraform

1. Download Terraform from the [Terraform Download Page](https://www.terraform.io/downloads.html)
2. Unzip the downloaded archive, and copy the executable file to a folder of choice ( f.e. C:\terraform\})
3. Add the folder to your PATH environmental variable.

### kubectl

1. Download [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-on-windows), v1.17.0 can be downloaded directly via [this link](https://storage.googleapis.com/kubernetes-release/release/v1.17.0/bin/windows/amd64/kubectl.exe)
2. Copy the downloaded executable to any folder you like ( f.e. C:\kubectl\)
3. Add the folder to your PATH environmental variable

You can also install kubectl with chocolatey via `choco install kubernetes-cli`

### helm

1. Download the latest helm release from [https://github.com/helm/helm/releases/latest]
2. Unpack the binary to any folder you like ( f.e. C:\kubernetes-helm\)
3. Add the folder to your PATH environmental variable

You can also install helm with chocolatey via `choco install kubernetes-helm`
