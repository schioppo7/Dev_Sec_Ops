# Lab 00 - Environment setup

This lab creates a Debian Bookworm virtual machine for the Bash exercises.

## Requirements

- Vagrant
- VirtualBox

## Run the lab

Run these commands from the repository root:

```bash
vagrant validate
vagrant up
vagrant ssh
```

Inside the virtual machine, the repository is mounted at `/workspace`.

Use `vagrant halt` to stop the machine.
