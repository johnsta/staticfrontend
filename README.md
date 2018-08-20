# A static Vue.js website in Kubernetes with Azure Dev Spaces
This sample shows how to host a static website in Kubernetes using NGINX, and to iteratively develop your static website code using Azure Dev Spaces.

## Get Started
1. Set up AKS and Azure Dev Spaces
    1. [Prerequisites](https://docs.microsoft.com/en-us/azure/dev-spaces/quickstart-nodejs#prerequisites)
    1. [Set up Dev Spaces](https://docs.microsoft.com/en-us/azure/dev-spaces/quickstart-nodejs#set-up-azure-dev-spaces)   
1. Clone this source repo, and open  it as the root code folder in Visual Studio Code.
1. In VS Code, open a Terminal window and run this command to build and run the NGINX container in AKS: `azds up`
1. Open web app in a browser (URL appears in `azds up` output)
1. Edit `html/index.html`, save, and refresh browser.
