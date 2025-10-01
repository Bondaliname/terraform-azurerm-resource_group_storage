# terraform-azurerm-resource_group_storage

## Як використовувати цей модуль:

```hcl
module "example" {
  source               = "github.com/YOUR_GITHUB_USERNAME/terraform-azurerm-resource_group_storage//modules/resource_group_storage"
  resource_group_name  = "my-rg"
  location             = "East US"
  storage_account_name = "mystorageacct"
}