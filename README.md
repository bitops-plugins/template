# Plugin template
Check out the BitOps [documentation](https://bitovi.github.io/bitops/) for more information! 

## README.md
Documents how to use the plugin. 

## INSTALL.md
Documentation on how to add the plugin into BitOps

## bitops.schema.yaml
Defines configuration options for the plugin. The names of the configuration options will be used to parse a corresponding `bitops.config.yaml` in an operation repo during runtime.

## plugin.config.yaml
Defines a install and deployment language and file name for the plugin when it is invoked by BitOps.


## deploy file
Defines how the plugin is used to invoke the underlying tool 

## install file
Installs the plugin and any additional needed packages
