# linux_gaming
ansible role for provisioning gaming platforms

## requirements

## variables

## dependencies
requires the following role(s):
- [rpm_fusion](https://github.com/chomatz/rpm_fusion)

## examples
```
- name: install steam
  ansible.builtin.include_role:
    name: linux_gaming
    tasks_from: steam_install.yml
```
```
- name: allow running steam via sudo
  ansible.builtin.include_role:
    name: linux_gaming
    tasks_from: steam_sudo.yml
```
```
- name: install xone dongle/gamepad driver
  ansible.builtin.include_role:
    name: linux_gaming
    tasks_from: xone_driver.yml
```
