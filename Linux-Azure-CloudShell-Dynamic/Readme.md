This project is meant to run in Azure Cloud shell.  It should work as-is with the exception of access to a storage account for downloading the puppet bootstrap files.  You will need to setup an Azure Keyvault with a secret and then reconfigure _main.tf to access your vault.

Replace anything in <> with your own values.