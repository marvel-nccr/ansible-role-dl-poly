[![Build Status](https://travis-ci.org/marvel-nccr/ansible-role-dl-poly.svg?branch=master)](https://travis-ci.org/marvel-nccr/ansible-role-dl-poly)

# Ansible Role: marvel-nccr.dl_poly

An Ansible role that installs [DL POLY Classic](https://gitlab.com/DL_POLY_Classic) on Ubuntu.

## Installation

`ansible-galaxy install marvel-nccr.dl_poly`

## Role Variables

See `defaults/main.yml`

## Example Playbook

```yaml
- hosts: servers
  roles:
  - role: marvel-nccr.dl_poly
```

## Tests

This role uses [Molecule](https://molecule.readthedocs.io/en/latest/#) and
Docker for tests. Once Docker is installed, run tests using

```bash
pip install -r requirements.txt
molecule test
```

## License

MIT

## Contact

Please direct inquiries regarding Quantum Mobile and associated ansible roles to the [AiiDA mailinglist](http://www.aiida.net/mailing-list/).
