# Static website in Kubernetes with Azure Dev Spaces
This sample shows how to host a static website in Kubernetes using NGINX, and to iteratively develop your static website code using Azure Dev Spaces.

## Get Started
1. [Set up AKS and Azure Dev Spaces](https://docs.microsoft.com/en-us/azure/dev-spaces/quickstart-nodejs)
1. Select your AKS cluster to develop in:
    `az aks use-dev-space -g <aksGroup> -n <aksName>`
    
1. Open Visual Studio Code and open a Terminal window
1. Generate a Helm chart (we already have a Dockerfile): `azds prep --public`
1. Build and run container in AKS: `azds up`
1. Open URL in browser (URL appears in `azds up` output)
1. Edit index.html, save, and refresh browser.
