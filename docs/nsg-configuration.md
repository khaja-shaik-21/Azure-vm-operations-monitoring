# Network Security Group (NSG) Configuration

## NSG Details
- Name: nsg-azure-vm-ops
- Associated with subnet: subnet-web

## Inbound Rules
| Rule Name | Port | Protocol | Action |
|---------|------|----------|--------|
| Allow-SSH | 22 | TCP | Allow |
| Allow-HTTP | 80 | TCP | Allow |

## Default Rules
- Allow VNet inbound traffic
- Deny all other inbound traffic

## Security Best Practices
- Only required ports were opened
- NSG applied at subnet level for centralized control
- SSH exposure limited to development/testing use
