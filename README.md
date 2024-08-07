# AZ-CLI-Uploader
A bash-based CLI tool that allows users to quickly upload files to a specified cloud storage solution
- adding AI to scan and categorize documents and file them by contents.
## First Steps
- Update Azure CLI
- az login
- Touch "script. file"
- nano "script. file"

- file parsing Lesson 
(  )


- insert "
#!/bin/bash

# Variables
STORAGE_ACCOUNT_NAME="<your_storage_account_name>"
STORAGE_ACCOUNT_KEY="<your_storage_account_key>"
CONTAINER_NAME="<your_container_name>"
FILE_PATH="<path_to_your_file>"
BLOB_NAME="<name_of_the_blob_in_azure>"

# Upload file to Azure Blob Storage
az storage blob upload \
  --account-name $STORAGE_ACCOUNT_NAME \
  --account-key $STORAGE_ACCOUNT_KEY \
  --container-name $CONTAINER_NAME \
  --file $FILE_PATH \
  --name $BLOB_NAME

echo "File uploaded successfully to $STORAGE_ACCOUNT_NAME/$CONTAINER_NAME/$BLOB_NAME"
"
## Second Steps
