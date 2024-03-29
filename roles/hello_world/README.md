# Ⓐ Ansible Role: hello_world

hello world

<!-- TODO: ## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.
-->

<!-- TODO: ## Role Variables

 A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

An example variable.

  hello_world_variable1

Another example variable.

  hello_world_variable2
-->

<!-- TODO: ## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

None
-->

## Using this role in an Ansible playbook

The following example shows how this role can be defined in a playbook with parameters passed to override default variables.

> **INFORMATION**
> It is recommended that you use a Fully Qualified Collection Name (FQCN) when referencing your roles.
>
> For simplicity, this example shows the use of a role *without* a FQCN.

```yaml
---
- hosts: 'all'
  roles:
    - role: daleroux.hello_tam_blog.hello_world
      hello_world_variable1: true
      hello_world_variable2: false
      tags: daleroux.hello_tam_blog.hello_world
```

## Licensing

MIT License

See [LICENSE](https://spdx.org/licenses/MIT.html) to see the full text.
