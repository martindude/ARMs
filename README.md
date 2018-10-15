# ARMs

## Zadanie 3.1


#### ENVs

- p- środowisko produkcyjne
- q - środowisko pre-prod
- d - środowisko developerskie
- t- środowisko testowe


##### RGs

'az-rg-<przeznaczenie>-xx`
  
 az-rg-security-01
 az-rg-vdi-01
 az-rg-logs-01



##### VMs

Type:
  - s - server
  - w - workstation

`<srodowisko>-<type>-<role>-xx`

psdc01
dsapp02


##### VNETs

`az-vnet-<location>-xx`

az-vnet-uksouth-01
az-vnet-westeurope-02


##### Subnets

`az-subnet-<nazwa>-xx`

az-subnet-apps-01
az-subnet-vms-02

##### NICs

`<vmname>-nicxx`

psdc01-nic01
dsapp02-nic01


##### Disks

`<vmname>-disk`

psdc01-c
dsapp02-f

##### Storage Accounts

`az-sa-<role>-xx`

az-sa-logs-01
az-sa-files-01


## Zadanie 3.2

vm-create.json

## Zadanie 3.3

Rolę mozna zdeploywac za pomocą: 

role-create.json

## Zadanie 3.4

N/A
