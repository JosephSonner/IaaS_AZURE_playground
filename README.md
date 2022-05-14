# IaaS_AZURE_playground
ARM templates for deploying a playground in AZURe

Usage: 

Download the AZURE CLI from microsoft for your platform: 
https://docs.microsoft.com/en-us/cli/azure/install-azure-cli

Configure the CLI to use the appropriate cloud (Gov or Commercial) 
https://docs.microsoft.com/en-us/cli/azure/azure-cli-configuration

Log into AZURE:
_az login --use-device-code command_ (--use-device-code is required if MFA is enabled on the AZURE subscription)

Select the subscription you with to deploy to: 
_az account set --subscription <sub-name>

