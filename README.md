# Terraform Beginner Bootcamp 2023

## Sematic Versioning
this project is going to utilize semantic versioning for tagging
[sematic tagging](https://semver.org/)


The general format:
 **MAJOR.MINOR.PATCH**, e.g.   `1.0.1`

- **MAJOR** version when you make incompatible API changes
- **MINOR** version when you add functionality in a backward compatible manner
- **PATCH** version when you make backward compatible bug fixes
            Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.




## install the Terraform CLI

### Considerations with the Terraform CLI changes
The Terraform CLI installation instructions have changed due to gpg keyring changes. So we needed refer to the latest install CLI instrucions via Terraform Documentation and change the scripting for install.

[install Terraform CLI](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)
 
### Refactoring into Bash Scripts

While fixing the Terraform CLI depercaiting issues we created a new terraform bash script

https://www.ciberciti.biz/faq/how-to-check-os-version-in-linux-command-line/
https://en.wikipedia.org/wiki/Shebang_(Unix)
https://en.wikipedia.org/wiki/Chmod

