## Licensing & Trademarks

This repository contains build scripts, Dockerfiles, and documentation used to
reconstruct historical Ubuntu Linux root filesystem images for multiple
releases and architectures.

The contents of this repository itself (scripts, Dockerfiles, documentation)
are licensed under the MIT License (see `LICENSE`).

Ubuntu is a distribution composed of software from many upstream projects, each
licensed under its own terms (including GPL, LGPL, BSD, MIT, Apache, and
others). This repository does not relicense Ubuntu or any of its components.

For license information about the software contained within any generated
images or root filesystems, see:

- `/usr/share/doc/*/copyright` inside the images or rootfs
- <https://www.ubuntu.com/legal>

Ubuntu is a registered trademark of Canonical Ltd. This project is not
affiliated with, endorsed by, or sponsored by Canonical.

## Security Notice

All Ubuntu releases produced by this project are end-of-life (EOL) and receive
no security updates. Images generated from this repository are provided for
historical, educational, and compatibility purposes only.

Do not use these images in production or expose them to untrusted networks.

## CI Configuration

The GitHub Actions workflow expects a repository variable named `DOCKER_IMAGE`
containing the base image name, for example: `pwmcollege/ubuntu`. This value is
used to prefix all tags that are pushed during CI builds.

## Redistribution

Redistribution of the generated images or root filesystem tarballs is permitted
under the terms of the individual upstream licenses included in Ubuntu.
This repository preserves all original license files and attributions provided
by upstream projects.
