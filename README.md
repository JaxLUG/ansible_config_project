# JaxLUG™ Ansible Config Project - ACP

This repository contains the official Jacksonville, Florida, Jacksonville
Linux Users Group™ community Ansible Config Project (ACP).

This is the JaxLUG's Ansible Config Project repo containing various
resources to configure Linux systems using Ansible.

This project is intended to aide in making custom Ansible resources. Anyone
may submit their Ansible resources, which includes direct git submodule
usage from your own personal repository, to this repository for others to
use as a starting point for theirs, directly, or other helpful purpose.

## Categories

The repository is categorized by directories named after Linux distros, or
the Ansible target system, and more can be added as needed, if your distro
is missing, add it.

## Format

Within each directory, the layout should follow the standard Ansible format,
with common subdirs such as roles and host_vars, or custom ones like
files and plays.

E.x.
```
└── distro
    ├── files/
    ├── host_vars/
    ├── plays/
    └── roles/
        └── role_name
            ├── defaults
            ├── files
            ├── handlers
            ├── tasks
            ├── templates
            └── vars
```

This is an initial work-in-progress community project, anyone is
welcome to participate and/or use.

Jacksonville Linux Users Group Inc. dba JaxLUG \
A Florida Non-Profit Corporation 501(c)(3) \
[https://www.jaxlug.ngo](https://www.jaxlug.ngo/)
