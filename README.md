# ansible-cups-sane

This is a network printer and scanner setup for an old HP printer owned by a
friend. I deployed it to a Raspberry Pi 4 running Raspberry Pi OS Lite 64-bit
with the printer being connected to USB.

It is somewhat based on [HP41/ansible-cups](https://github.com/HP41/ansible-cups/)
but works with recent versions of ansible:

```sh
$ ansible --version
ansible [core 2.18.4]
  config file = ...
  configured module search path = ...
  ansible python module location = ...
  ansible collection location = ...
  executable location = ...
  python version = 3.13.2 (main, Feb  4 2025, 14:51:09) [Clang 16.0.0 (clang-1600.0.26.6)] (...)
  jinja version = 3.1.6
  libyaml = True
```
