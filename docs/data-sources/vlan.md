---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "netbox_vlan Data Source - terraform-provider-netbox"
subcategory: ""
description: |-
  
---

# netbox_vlan (Data Source)



## Example Usage

```terraform
# Get VLAN by name
data "netbox_vlan" "vlan1" {
  name = "vlan-1"
}

# Get VLAN by VLAN ID
data "netbox_vlan" "vlan2" {
  vid = 1234
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `name` (String)
- `vid` (Number)

### Read-Only

- `description` (String)
- `id` (String) The ID of this resource.
- `role` (Number)
- `site` (Number)
- `status` (String)
- `tenant` (Number)

