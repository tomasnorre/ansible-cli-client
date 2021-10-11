# Ansible CLI Github Action

This action is based on `ubuntu:focal` image.  
You can execute all `Ansible` related actions i.e, `ansible` or `ansible-playbook`.  
You can also execute standard `Linux` commands as base `Docker` image is `ubuntu`.

## Inputs

### `command`

**Required** Command to execute. Default `"ansible-playbook"`.

## Example usage

```
uses: tomasnorre/ansible-cli-action@0.0.1
with:
  command: "ansible-playbook main.yml"
```
