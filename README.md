# Ubuntu installation guide

Ubuntu Server Installer, and backend for Ubuntu Desktop Installer

Subiquity is an installer framework for Ubuntu. It provides the Ubuntu Server with a text-based installation user interface and Ubuntu Core first-boot configuration. Subiquity is also the back end for the Ubuntu Desktop installer.


## Autoinstall configuration reference manual

https://canonical-subiquity.readthedocs-hosted.com/en/latest/reference/autoinstall-reference.html

## Generate password

https://linux-de.com/?p=2853

```shell
# password generation with
openssl passwd -6
```

## Article - Ubuntu 24.04 with autoinstall.yaml

https://nsg.cc/post/2024/autoinstall/

```
+-----+------+---------------------------------+
| ESP | Boot | LUKS                            |
+-----+------+---------------------------------+
| LVM                             |
+---------------------------------+
| root               | swap | ... |
+--------------------+------+-----+
```

## Autoinstall quick start

https://canonical-subiquity.readthedocs-hosted.com/en/latest/howto/autoinstall-quickstart.html


## Creating autoinstall configuration

https://canonical-subiquity.readthedocs-hosted.com/en/latest/tutorial/creating-autoinstall-configuration.html


## Autoinstall Validation

https://canonical-subiquity.readthedocs-hosted.com/en/latest/howto/autoinstall-validation.html


## Autoinstall schema

https://canonical-subiquity.readthedocs-hosted.com/en/latest/reference/autoinstall-schema.html


## Further example

https://github.com/canonical/subiquity/tree/main/examples/autoinstall
