# Azure Command List

This document provides a complete list of common Azure commands used with Azure CLI.

## Table of Contents

- [Azure CLI Commands](#azure-cli-commands)
- [Azure Resource Management Commands](#azure-resource-management-commands)
- [Azure Storage Commands](#azure-storage-commands)
- [Azure Virtual Machine Commands](#azure-virtual-machine-commands)
- [Azure App Service Commands](#azure-app-service-commands)

## Azure CLI Commands

| Command                                   | Description                                              |
|-------------------------------------------|----------------------------------------------------------|
| `az login`                                | Log in to your Azure account.                            |
| `az logout`                               | Log out from your Azure account.                         |
| `az account show`                         | Show the details of the currently active account.       |
| `az account list`                         | List all available Azure accounts.                      |
| `az account set --subscription <name>`   | Set the active subscription.                             |

## Azure Resource Management Commands

| Command                                   | Description                                              |
|-------------------------------------------|----------------------------------------------------------|
| `az group create --name <group-name>`   | Create a new resource group.                            |
| `az group list`                           | List all resource groups in the subscription.          |
| `az group delete --name <group-name>`    | Delete a resource group and its resources.             |
| `az resource show --name <name>`         | Show details of a specific resource.                   |

## Azure Storage Commands

| Command                                   | Description                                              |
|-------------------------------------------|----------------------------------------------------------|
| `az storage account create --name <name>` | Create a new storage account.                          |
| `az storage account list`                | List all storage accounts in the subscription.         |
| `az storage container create --name <name>` | Create a new container in a storage account.         |
| `az storage blob upload --container-name <name>` | Upload a blob to a container.                      |
| `az storage blob list --container-name <name>` | List blobs in a specified container.               |

## Azure Virtual Machine Commands

| Command                                   | Description                                              |
|-------------------------------------------|----------------------------------------------------------|
| `az vm create --resource-group <group-name> --name <vm-name>` | Create a new virtual machine.                    |
| `az vm list`                              | List all virtual machines in the subscription.        |
| `az vm start --name <vm-name> --resource-group <group-name>` | Start a virtual machine.                         |
| `az vm stop --name <vm-name> --resource-group <group-name>`  | Stop a virtual machine.                          |
| `az vm delete --name <vm-name> --resource-group <group-name>` | Delete a virtual machine.                        |

## Azure App Service Commands

| Command                                   | Description                                              |
|-------------------------------------------|----------------------------------------------------------|
| `az webapp create --resource-group <group-name> --name <app-name>` | Create a new web app.                        |
| `az webapp list`                         | List all web apps in the subscription.                 |
| `az webapp start --name <app-name> --resource-group <group-name>` | Start a web app.                            |
| `az webapp stop --name <app-name> --resource-group <group-name>`  | Stop a web app.                             |
| `az webapp delete --name <app-name> --resource-group <group-name>` | Delete a web app.                           |

