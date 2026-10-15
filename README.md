# SRE Learning Linux

## Topics

- [01 - The Linux Kernel](./01-Linux-Kernel/README.md)

## Lab

Virtual machines to practice Linux.

- Vagrant v2.3.7
- Virtualbox 7.0

The lab includes two virtual machines:

- `almalinux`: AlmaLinux 10, RHEL based OS.
- `kalilinux`: Kali Linux, Debian based OS.

From the **lab/** directory, to deploy the machines:

```bash
vagrant up
```

To stop the machines:

```bash
vagrant halt
```

To destroy the machines:

```bash
vagrant destroy -f
```

