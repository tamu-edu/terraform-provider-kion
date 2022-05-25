---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "kion_gcp_iam_role Resource - terraform-provider-kion"
subcategory: ""
description: |-
  
---

# kion_gcp_iam_role (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **gcp_role_launch_stage** (Number)
- **name** (String)
- **role_permissions** (List of String)

### Optional

- **description** (String)
- **id** (String) The ID of this resource.
- **last_updated** (String)
- **owner_user_groups** (Block List) (see [below for nested schema](#nestedblock--owner_user_groups))
- **owner_users** (Block List) (see [below for nested schema](#nestedblock--owner_users))
- **system_managed_policy** (Boolean)

### Read-Only

- **gcp_id** (String)
- **gcp_managed_policy** (Boolean)

<a id="nestedblock--owner_user_groups"></a>
### Nested Schema for `owner_user_groups`

Optional:

- **id** (Number) The ID of this resource.


<a id="nestedblock--owner_users"></a>
### Nested Schema for `owner_users`

Optional:

- **id** (Number) The ID of this resource.

