Virtual Machine, Storage Account and Resource Group created using Terraform in Azure. 

create and name a new folder (ctrl+O), Create new file and name it main.tf , provider.tf , varriable.tf  on VS Code.

From the terminal, first, login your az portal with using “az login” command 

Find provider script from Terraform website  https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs

Find Resource Group script from Terraform website  https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group

Find Storage Account from Terraform website  https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/storage_account

Find Windows virtual machine script from Terraform website  https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/windows_virtual_machine

main.tf, provider.tf ,variable.tf. codes collected via terraform web site, then edited the code for requirements of the Project.

provision below commands: 
-- terraform init 
-- terraform plan 
-- terraform apply

