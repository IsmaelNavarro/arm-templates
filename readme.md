#### Create Group
az group create --name **{groupName}** --location "West Europe"

#### Deploy arm template
az group deployment create --resource-group **{groupName}** \
    (--template-uri|--template-file) **{path}** \
    --parameters **{parameterName}={parameterValue}**