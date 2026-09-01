# Linux headers 6.18.15

This repository provides the amd64 kernel headers package for Linux 6.18.15.
It is intended for DKMS and other external kernel module builds.

## Package

`linux-headers-6.18.15_6.18.15-gc05395988e2f+public3-1_amd64.deb`

Install on a matching Linux 6.18.15 system:

```sh
sudo dpkg -i linux-headers-6.18.15_6.18.15-gc05395988e2f+public3-1_amd64.deb
```

The installed external-module build entry point is:

```text
/lib/modules/6.18.15/build
```

Verify the package against `SHA256SUMS` before installation.
