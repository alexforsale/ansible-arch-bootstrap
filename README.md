Archlinux Bootstrap
---

Ansible playbook for bootstraping Archlinux system. This is for automating installation process after the [chroot step](https://wiki.archlinux.org/title/Installation_guide#Chroot), so ansible must be installed inside the chroot, or when running the _pacstrap_ command.

For available variables, see _defaults/main.yaml_ in each roles directory.
