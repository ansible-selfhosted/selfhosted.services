# Collection for selfhosted.services

This Ansible collection serve as a bucket for various services quadlet deployment roles and related files.

## Requirements

The target host needs the following:

- podman v5.0 or higher (for Quadlet support)
- ~/.config/systemd/user and ~/.config/containers/systemd must exist for the ansible user


## Installing this collection

You can install the selfhosted.services collection with the Ansible Galaxy CLI:

```console
ansible-galaxy collection install selfhosted.services
```

You can also include it in a `requirements.yml` file and install it with `ansible-galaxy collection install -r requirements.yml`, using the format:

```yaml
---
collections:
  - name: selfhosted.services
    version: ...  # Optional
```


## License

This project is licensed under the [MIT License](LICENSE)

⊂(▀¯▀⊂)
