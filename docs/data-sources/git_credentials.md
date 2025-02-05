---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "octopusdeploy_git_credentials Data Source - terraform-provider-octopusdeploy"
subcategory: ""
description: |-
  Provides information about existing GitCredentials.
---

# octopusdeploy_git_credentials (Data Source)

Provides information about existing GitCredentials.



<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `name` (String) A filter to search by name.
- `skip` (Number) A filter to specify the number of items to skip in the response.
- `take` (Number) A filter to specify the number of items to take (or return) in the response.

### Read-Only

- `git_credentials` (Block List) A list of Git Credentials that match the filter(s). (see [below for nested schema](#nestedblock--git_credentials))
- `id` (String) The ID of this resource.

<a id="nestedblock--git_credentials"></a>
### Nested Schema for `git_credentials`

Read-Only:

- `description` (String) The description of this Git credential.
- `id` (String) The unique ID for this resource.
- `name` (String) The name of the Git credential. This name must be unique.
- `password` (String, Sensitive) The password for the Git credential.
- `space_id` (String) The space ID associated with this resource.
- `type` (String) The Git credential authentication type.
- `username` (String) The username for the Git credential.


