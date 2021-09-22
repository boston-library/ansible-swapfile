# ansible-swapfile

An Ansible role for creatiing a swapfile.

## Role Variables

- `swapfile_size`: Size of swapfile (default: `1GB`)
- `swapfile_path`: Location of swapfile (default: `/swapfile`)

This ansible role is taken mostly out of [ansible-swapfile](https://github.com/azavea/ansible-swapfile.git) from Azavea Inc., but I stripped it down for brevity.