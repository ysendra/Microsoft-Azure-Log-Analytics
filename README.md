# Microsoft-Azure-Log-Analytics
This Python script is made to access Microsoft Azure Log analytics to collec Azure Bastion Service log and create a grapgh based on some inputs (environement, Startign & Ending Dates
There are 2 flavors:
 - Environement Credentials (Based on Service Principal login)
 - Default Credentials Based on CLI lgin)

#Prerequisites for Environement Credentials
#Pre-requisites to create the environement variables env.text in the same folder as the notebook
#Example of content in env.txt
#vzpoc_AZURE_TENANT_ID = 'xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'
#vzpoc_AZURE_CLIENT_ID = 'yyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy'
#vzpoc_AZURE_CLIENT_SECRET = 'zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz'
#vzpoc_AZURE_WORKSPACE_ID = 'aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa'

Note: the Environement Credential script is not using the Microsoft Azure Python SDK
