---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "datadog_api_key Data Source - terraform-provider-datadog"
subcategory: ""
description: |-
  Use this data source to retrieve information about an existing api key.
---

# datadog_api_key (Data Source)

Use this data source to retrieve information about an existing api key.

## Example Usage

```terraform
data "datadog_api_key" "foo" {
  name = "foo-application"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- **id** (String) Id for API Key.
- **name** (String) Name for API Key.

### Read-Only

- **key** (String, Sensitive) The value of the API Key.


