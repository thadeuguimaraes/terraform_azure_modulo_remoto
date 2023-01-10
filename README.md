# Terraform Azure Remote Module

Este é um módulo Terraform para provisionar recursos na nuvem Azure utilizando o Azure Remote Provider. Este módulo permite que você gerencie recursos do Azure, incluindo máquinas virtuais, redes, armazenamento e muito mais, diretamente a partir do Terraform.

## Requisitos

- Conta ativa do Azure
- Acesso à chave de assinatura da conta do Azure
- Terraform 0.13 ou superior

## Configurações

Este módulo possui várias configurações que podem ser especificadas através de variáveis no arquivo `variables.tf`. As configurações incluem a região, o tamanho de VM, o tipo de disco, entre outras. Certifique-se de verificar e editar essas configurações antes de executar o comando `terraform apply`.

## Documentação

Para obter mais informações sobre como usar este módulo, consulte a [documentação do terraform](https://developer.hashicorp.com/terraform/docs) e a
[documentação sobre os módulos remotos da Azure](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)

### Obs: lembre-se de manter seus arquivos de credenciais seguros.
