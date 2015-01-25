# leonelgalan.node

Installs nodejs and the **latest** npm.

# Role Variables

Default variables are:

```yml
---
npm_packages: []
```

## Dependencies

* nodesource.node

```shell
ansible-galaxy install --role-file=requirements.yml --force
```

## Example Playbook
```yml
- hosts: all

roles:
  - role: leonelgalan.node
  npm_packages:
    - gulp
    ```

## Vagrant

```shell
vagrant up
```

## License

_leonelgalan.node_ is released under the [MIT License](http://opensource.org/licenses/MIT  ).

## Author Information

Leonel Galán (<leonel@smashingboxes.com>)
