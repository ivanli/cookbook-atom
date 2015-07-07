atom Cookbook
=============
Installs Atom text editor through chocolatey. This installer will always install the latest version of Atom, 
with automatic updates turned on.

Requirements
------------
Runs on windows. Relies on chocolatey packages.

#### packages
- `chocolatey` - atom needs chocolatey to install Atom.

Attributes
----------
None.

Usage
-----
Just include `atom` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[atom]"
  ]
}
```

Contributing
------------
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Ivan Li
