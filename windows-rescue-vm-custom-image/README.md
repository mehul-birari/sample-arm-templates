# Deploy a Windows Rescue VM by picking custom image from a new storage account


[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fmehul-birari%2Fsample-arm-templates%2Fmaster%2Fwindows-vm-hybrid-worker-group%2Fazuredeploy.json)  

This template enables us to deploy a rescue Virtual Machine from a custom image in a new storage account which should have the source image VHD for the VM deployment before it happens.
This template will create 2 Virtual Machines, one being the transfer VM and the second being the Rescue VM. Transfer VM can be deleted after the deployment is complete. 

