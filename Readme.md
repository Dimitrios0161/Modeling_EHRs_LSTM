## Deep Learning Server setup 

Data Science Virtual Machines(DSVM) are a family of Azure Virtual Machine images, pre-configured with several popular tools that are commonly used for data analytics, machine learning and AI development. These directions show how to create an Ubuntu DSVM using Azure CLI and a preconfigured ARM template.

For building and training the model I'm using a *Standard_NC6_Promo* which has one NVidia K80 GPU and six CPU cores. This instance will incur about £0.31 per hour (Azure Region: North Europe) compared to £0.72/hour for a dedicated instance. Further details about available DSVM sizes and compute charges can be found [here](https://azure.microsoft.com/en-us/pricing/details/virtual-machine-scale-sets/linux/).

