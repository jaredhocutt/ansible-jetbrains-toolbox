# JetBrains Toolbox

Installs JetBrains Toolbox.

## Requirements

None

## Role Variables

| Variable                    | Required | Default | Description                                  |
| --------------------------- | -------- | ------- | -------------------------------------------- |
| `jetbrains_toolbox_version` | :x:      | `1.8`   | The version of JetBrains Toolbox to install. |


## Dependencies

None

## Example Playbook

```yaml
- hosts: localhost
  vars:
    jetbrains_toolbox_version: 1.8
  roles:
      - jaredhocutt.jetbrains-toolbox
```
