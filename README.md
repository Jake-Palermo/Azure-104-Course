# Deploying Azure infrastructure using JSON ARM templates:

This project contains an Azure Resource Manager template for deploying an Azure Storage Account with customizable parameters.

- Deploys a Storage V2 Azure Storage Account
- Accepts two parameters:
  - `storageName`: The name of the Storage Account (must be unique)
  - `storageSKU`: The SKU (pricing/performance tier) to use
- Outputs the primary endpoints for Blob, Queue, Table, and File services
