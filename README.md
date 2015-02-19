The Ibuildings Drupal Security Audit tools.
==========================================

Adds various Drush commands to better enable you to audit the security of your Drupal installation.

# Install
 
 With Makefile:
```
; Drupal Security Audit tools
projects[drupal_sectools][subdir] = "contrib"
projects[drupal_sectools][type] = "module"
projects[drupal_sectools][download][type] = "git"
projects[drupal_sectools][download][url] = "https://github.com/ibuildingsnl/drupal_sectools.git"
```

Contains the following modules:


Drupal Security Tool Usage
--------------------------
Adds the 'modules-usages-status' (mus) Drush command.
Generate a CSV listing of all modules with their versions and associated usage counts.
This can be used as input into security auditing scope.

To enable:
```
drush en drupal_sectools_usage
```
