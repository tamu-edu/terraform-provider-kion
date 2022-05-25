---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "kion_azure_arm_template Resource - terraform-provider-kion"
subcategory: ""
description: |-
  
---

# kion_azure_arm_template (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **deployment_mode** (Number)
- **name** (String)
- **resource_group_name** (String)
- **resource_group_region_id** (Number)
- **template** (String)

### Optional

- **description** (String)
- **id** (String) The ID of this resource.
- **last_updated** (String)
- **owner_user_groups** (Block List) (see [below for nested schema](#nestedblock--owner_user_groups))
- **owner_users** (Block List) (see [below for nested schema](#nestedblock--owner_users))
- **template_parameters** (String)

### Read-Only

- **ct_managed** (Boolean)
- **version** (Number)

<a id="nestedblock--owner_user_groups"></a>
### Nested Schema for `owner_user_groups`

Optional:

- **id** (Number) The ID of this resource.


<a id="nestedblock--owner_users"></a>
### Nested Schema for `owner_users`

Optional:

- **id** (Number) The ID of this resource.

