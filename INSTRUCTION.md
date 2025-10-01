# terraform-azurerm-resource_group_storage

## Використання

```hcl
module "rg_storage" {
  source               = "github.com/yourusername/terraform-azurerm-resource_group_storage//modules/resource_group_storage"
  resource_group_name  = "my-resource-group"
  location             = "East US"
  storage_account_name = "uniquestorageacct"
}