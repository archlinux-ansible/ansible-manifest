---

# Repo manifest for Ansible tree

This repo manifest helps to check out the entire Ansible tree.

To check out:

```shell
$ mkdir ansible
$ cd ansible
$ repo init \
  -u ssh://git@github.com/archlinux-ansible/ansible-manifest \
  -m default.xml \
  -b master
```

To check out master branch for all repos (avoiding detached HEAD):

```shell
$ repo start master --all
```
