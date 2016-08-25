# Lab 4

## Exercise 1

Below is an example of what your cloud-config file should look like to 
set the reboot strategy:

```
#cloud-config

coreos:
  update:
    reboot-strategy: reboot
```
