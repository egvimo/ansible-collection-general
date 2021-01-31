# Ansible collection of miscellaneous roles

![Molecule Test](https://github.com/egvimo/ansible-collection-general/workflows/Molecule%20Test/badge.svg)

This collection contains the following roles:

| Role         | Name        | Documentation                         |
| ------------ | ----------- | ------------------------------------- |
| Bash-it      | bash_it     | [Readme](roles/bash_it/README.md)     |
| Docker       | docker      | [Readme](roles/docker/README.md)      |
| JDownloader  | jdownloader | [Readme](roles/jdownloader/README.md) |
| Raspberry Pi | raspberry   | [Readme](roles/raspberry/README.md)   |
| ReadyMedia   | minidlna    | [Readme](roles/minidlna/README.md)    |
| User         | user        | [Readme](roles/user/README.md)        |

## Installation

The latest version of the collection can be installed via Ansible Galaxy:

```shell
ansible-galaxy collection install egvimo.general
```

Or directly from the repository via `requirements.yml`:

```yml
collections:
  - name: https://github.com/egvimo/ansible-collection-general.git
    type: git
    version: main # Or any other Git branch, tag or commit
```

## License

Copyright © 2020 egvimo.

Licensed under the MIT License. See [LICENSE](LICENSE).
