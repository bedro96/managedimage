# Managed Image creation.
Create a managed image from packer temp file and blank data disk, place under test-imgrepo-rg resource group.

1. Please identify the Resource ID of manged disk, name as PackerTemp-1576133404, and update packer_os_managed_disk_id in terraform.tfvars.
2. Once these codes are applied, imgtestwithdatadisk20191212 image will be provision under test-imgrepo-rg resource group.
