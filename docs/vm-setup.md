# Virtual Machine Setup

## VM Details
- Name: vm-linux-ops-01
- OS: Ubuntu Server 22.04 LTS
- Size: Standard B1s
- Region: East US
- Authentication: SSH public key

## Setup Steps
1. Created a resource group to organize Azure resources
2. Configured a Virtual Network and subnet
3. Created a Linux virtual machine using Ubuntu 22.04
4. Generated SSH key pair for secure access
5. Assigned a public IP for external connectivity

## VM Access
SSH command used:
```bash
ssh -i linux-vm-key.pem azureuser@<public-ip>
