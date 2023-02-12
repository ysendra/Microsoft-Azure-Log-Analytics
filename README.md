# Microsoft-Azure-Log-Analytics
These Python scripts are made to access Microsoft Azure Log analytics to collect Azure Bastion Service logs and create a graph based on some inputs (Environment type (Lab or Production), Starting & Ending Dates)
There are two implementation flavors:
 - Environment Credentials: Based on Service Principal login
 - Default Credentials: Based on CLI login

#Prerequisites for Azure Bastion Service: 
 - Enable Logs on Azure Bastion Service (Through "Diagnostic Settings" in the Azure Bastion menu)

#Prerequisites for Environment Credentials 
 - Create the environment variables "env.text" in the same folder as the notebook 

#Example of content in env.txt 
vzpoc_AZURE_TENANT_ID = 'xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx'

vzpoc_AZURE_CLIENT_ID = 'yyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy'

vzpoc_AZURE_CLIENT_SECRET = 'zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz'

vzpoc_AZURE_WORKSPACE_ID = 'aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa'

Note: the Python environment shall load the Microsoft Azure Python SDK
