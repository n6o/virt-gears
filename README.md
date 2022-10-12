# virt-gears

## Create devenv instance by multipass

```
$ multipass launch -n NAME --cloud-init devenv-cloud-init.yml -vvvv
```

## Setup devenv

```
instance$ curl -sS https://raw.githubusercontent.com/n6o/virt-gears/main/devenv-setup.sh | bash
```
