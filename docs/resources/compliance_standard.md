---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "kion_compliance_standard Resource - terraform-provider-kion"
subcategory: ""
description: |-
  
---

# kion_compliance_standard (Resource)



## Example Usage

```terraform
# Create a compliance standard.
resource "kion_compliance_standard" "s1" {
  name               = "sample-resource"
  created_by_user_id = 1
  owner_users { id = 1 }
  owner_user_groups { id = 1 }
}

# Output the ID of the resource created.
output "standard_id" {
  value = kion_compliance_standard.s1.id
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `created_by_user_id` (Number)
- `name` (String)

### Optional

- `compliance_checks` (Block Set) (see [below for nested schema](#nestedblock--compliance_checks))
- `description` (String)
- `last_updated` (String)
- `owner_user_groups` (Block Set) Must provide at least the owner_user_groups field or the owner_users field. (see [below for nested schema](#nestedblock--owner_user_groups))
- `owner_users` (Block Set) Must provide at least the owner_user_groups field or the owner_users field. (see [below for nested schema](#nestedblock--owner_users))

### Read-Only

- `created_at` (String)
- `ct_managed` (Boolean)
- `id` (String) The ID of this resource.

<a id="nestedblock--compliance_checks"></a>
### Nested Schema for `compliance_checks`

Read-Only:

- `id` (Number) The ID of this resource.


<a id="nestedblock--owner_user_groups"></a>
### Nested Schema for `owner_user_groups`

Read-Only:

- `id` (Number) The ID of this resource.


<a id="nestedblock--owner_users"></a>
### Nested Schema for `owner_users`

Read-Only:

- `id` (Number) The ID of this resource.
