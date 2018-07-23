# Quay-Entreprise-for-k8s
A helm chart for Quay
# Installing Helm 
This is the official documentation to [install](https://docs.helm.sh/using_helm/#installing-helm) Helm.
## Initialize Helm and Install Tiller
Once you have Helm ready, you can initialize the local CLI and also install Tiller into your Kubernetes cluster in one step:
``` 
$ helm init
```
This will install Tiller into the Kubernetes cluster you saw with ```kubectl config current-context```.
By default, when Tiller is installed,it does not have authentication enabled. 
To learn more about configuring strong TLS authentication for Tiller, consult the [Tiller TLS guide](https://docs.helm.sh/using_helm/#using-ssl-between-helm-and-tiller).

# Install Quay Entreprise Chart

To install a chart, you just need to pull this repository and run the command below:
```
helm install --debug ./Quay-Entreprise-for-k8s
```
