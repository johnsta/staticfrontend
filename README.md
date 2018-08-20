# Static website in Kubernetes with Azure Dev Spaces
This sample shows how to host a static website in Kubernetes using NGINX, and to iteratively develop your static website code using Azure Dev Spaces.

## Get Started
1. Set up AKS and Azure Dev Spaces
    1. [Prerequisites](https://docs.microsoft.com/en-us/azure/dev-spaces/quickstart-nodejs#prerequisites)
    1. [Set up Dev Spaces](https://docs.microsoft.com/en-us/azure/dev-spaces/quickstart-nodejs#set-up-azure-dev-spaces)   
1. Clone this source repo, and open it as the root code folder in Visual Studio Code. Then, open a Terminal window in VS Code and running the following commands.
1. Build and run container in AKS: `azds up`
1. Open web app in a browser (URL appears in `azds up` output)
1. Edit `html/index.html`, save, and refresh browser.
