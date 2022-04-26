# Radarr role

[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-neoloc.radarr-blue.svg)](https://galaxy.ansible.com/neoloc/ansible-role-radarr/)

Galaxy: https://galaxy.ansible.com/neoloc/radarr

## Instructions

This role will install Radarr to serve the UI at `<server address>/radarr`.

## Variables and their defaults

| variable name               | default value     | description                                                                             |
| --------------------------- | ----------------- | --------------------------------------------------------------------------------------- |
| radarr\_\_config_directory  | `/var/lib/radarr` | Radarr configuration files directory                                                    |
| radarr\_\_install_directory | `/opt`            | Radarr installation directory (will use `<dir>/Radarr`)                                 |
| radarr\_\_username          | `radarr`          | Username under which to run Radarr                                                      |
| radarr\_\_password          | `!` (disabled)    | Radarr user's password                                                                  |
| radarr\_\_group             | `media`           | Radarr user's group                                                                     |
| radarr\_\_group_id          | `1100`            | The GID for Radarr's group                                                              |
| radarr\_\_version           | `latest` (stable) | See https://github.com/Radarr/Radarr/releases                                           |

## Original Author

Galaxy: https://galaxy.ansible.com/coaxial/radarr
