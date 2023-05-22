# Custom field extraction using Katana IP and email regex
```
You can create custom fields to extract and store specific information from page responses using regex rules. These custom fields are defined using a YAML config file and are loaded from the default location at $HOME/.config/katana/field-config.yaml
```

# Example
```
echo google.com | katana -f email,ip
```
