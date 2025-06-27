# Zed OpenTofu

An [OpenTofu](https://www.opentofu.org/) extension for [Zed](https://zed.dev).

## File association conflicts

In order to automatically use the OpenTofu extension and language server when editing `.tf` and `.tfvars` files, either uninstall the Terraform extension or add this to your `settings.json`:

```jsonc
"file_types": {
  "OpenTofu": ["tf"],
  "OpenTofu Vars": ["tfvars"]
},
```

## Development

To develop this extension, see the [Developing Extensions](https://zed.dev/docs/extensions/developing-extensions) section of the Zed docs.
