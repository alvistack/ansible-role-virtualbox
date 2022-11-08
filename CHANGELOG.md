# Ansible Role for VirtualBox

## 6.6.0 - TBC

### Major Changes

-   Remove Fedora 35 support
-   Remove openSUSE Leap 15.3 support

## 6.5.0 - 2022-10-14

-   Support Ansible community package 6.5.0

### Major Changes

-   Support Ubuntu 22.10
-   Support Fedora 37

## 6.4.0 - 2022-09-15

### Major Changes

-   Support Ansible community package 6.4.0

## 6.3.0 - 2022-08-24

### Major Changes

-   Support Ansible community package 6.3.0

## 6.2.0 - 2022-08-03

### Major Changes

-   Support Ansible community package 6.2.0

## 6.1.0 - 2022-07-14

### Major Changes

-   Support Ansible community package 6.1.0
-   Remove Ubuntu 21.10 support

## 6.0.0 - 2022-06-22

### Major Changes

-   Support Ansible community package 6.0.0

## 5.9.0 - 2022-06-08

### Major Changes

-   Support Ansible community package 5.9.0

## 5.8.0 - 2022-05-20

### Major Changes

-   Support Ansible community package 5.8.0
-   Remove Fedora 34 support

## 5.7.0 - 2022-04-27

### Major Changes

-   Rename Ansible Role with FQCN
-   Support Ansible community package 5.7.0
-   Support RHEL 9
-   Support CentOS 9 Stream
-   Support openSUSE Leap 15.4

## 5.6.0 - 2022-04-07

### Major Changes

-   Support Ansible community package 5.6.0
-   Support Fedora 36
-   Support Ubuntu 22.04
-   Support Ansible community package 5.5.0
-   Support Ansible community package 5.4.0

## 5.5.0 - 2022-02-11

### Major Changes

-   Remove Ubuntu 21.04 support
-   Skip package upgrade before running molecule
-   Support Fedora Rawhide
-   Support Debian Testing

## 5.4.0 - 2021-12-31

### Major Changes

-   Remove openSUSE Leap 15.2 support
-   Upgrade minimal Ansible community package support to 4.10

## 5.3.0 - 2021-10-20

### Major Changes

-   Remove Fedora 33 support
-   Remove Ubuntu 20.10 support
-   Support Fedora 35
-   Support Ubuntu 21.10
-   Upgrade minimal Ansible community package support to 4.7.0

## 5.2.0 - 2021-09-19

### Major Changes

-   Install dependencies with package manager
-   Upgrade minimal Ansible community package support to 4.5.0

## 5.1.0 - 2021-07-18

### Major Changes

-   Upgrade minimal Ansible community package support to 4.2.0
-   Support Debian 11
-   Support openSUSE Leap 15.3

## 5.0.0 - 2021-06-02

### Major Changes

-   Simplify VirtualBox Extension Pack installation
-   Upgrade minimal Ansible support to 4.0.0
-   Support Fedora 34
-   Support Ubuntu 21.04
-   Simplify download archive logic

## 4.7.0 - 2021-03-13

### Major Changes

-   Bugfix [ansible-lint `namespace`](https://github.com/ansible-community/ansible-lint/pull/1451)
-   Bugfix [ansible-lint `no-handler`](https://github.com/ansible-community/ansible-lint/pull/1402)
-   Bugfix [ansible-lint `unnamed-task`](https://github.com/ansible-community/ansible-lint/pull/1413)
-   Simplify Python dependency with system packages
-   Support RHEL 8 with Molecule
-   Support RHEL 7 with Molecule
-   Remove CentOS 8 support
-   Improve HTTP transparent proxy support
-   Improve download archive logic
-   Support CentOS 8 Stream
-   Support openSUSE Tumbleweed
-   Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

-   Simplify Molecule scenario for vagrant-libvirt
-   Support VirtualBox Extension Pack
-   Remove EOL version support
-   Migrate from Travis CI to GitLab CI
-   Support Fedora 33
-   Remove Fedora 32 support
-   Support Ubuntu 20.10
-   Remove redundant tags from tasks

## 4.5.0 - 2020-08-26

### Major Changes

-   Upgrade minimal Ansible Lint support to 4.3.2
-   Upgrade Travis CI test as Ubuntu Focal based
-   Upgrade minimal Ansible support to 2.10.0
-   Support openSUSE Leap 15.2
-   Remove Ubuntu 19.10 support

## 4.4.0 - 2020-06-04

### Major Changes

-   Support Fedora 32
-   Support Debian 10
-   `molecule -s default` with delegated to localhost

## 4.3.0 - 2020-04-22

### Major Changes

-   Template `molecule -s default` with dummy docker driver
-   Support CentOS/RHEL 8
-   Support Ubuntu 20.04
-   Remove Ubuntu 16.04 support
-   Upgrade minimal Molecule support to 3.0.2
-   Migrate role name to lowercase or underline
-   Migrate group name to lowercase or underline
-   Migrate molecule `group_vars` to file

## 4.2.0 - 2020-02-13

### Major Changes

-   Migrate molecule driver to Libvirt
-   Migrate molecule verifier to Ansible
-   Support Ubuntu 19.10

## 4.1.0 - 2020-01-16

### Major Changes

-   Default `interpreter_python` with `python3`
-   Bugfix `python3-xml` not exists for openSUSE Leap 15.1

## 4.0.0 - 2019-11-05

### Major Changes

-   Upgrade minimal Ansible support to 2.9.0
-   Upgrade Travis CI test as Ubuntu Bionic based

## 3.5.0 - 2019-10-06

### Major Changes

-   Support openSUSE Leap 15.1
-   Default with Python 3
-   Revamp molecule test with vagrant

## 3.4.0 - 2019-09-18

### Major Changes

-   Run molecule test manually on Travis CI

## 3.3.0 - 2019-08-27

### Major Changes

-   Update for RHEL 7
-   Add Vagrant test for RHEL 7

## 3.2.0 - 2019-07-08

### Major Changes

-   Update LXD test profile for Kubernetes v1.15.0 support
-   Fix molecule `group_vars` with links
-   Replace `with_items` with `loop`
-   Replace `with_dict` with `var`
-   Replace `with_first_found` with `lookup('first_found')`

## 3.1.0 - 2019-06-13

### Major Changes

-   Simplify for openSUSE by `disable_gpg_check: true`

## 3.0.0 - 2019-05-31

-   Initial release for Ansible 2.8 or higher
-   Support both Ubuntu 16.04/18.04 or RHEL/CentOS 7 or openSUSE Leap 15
