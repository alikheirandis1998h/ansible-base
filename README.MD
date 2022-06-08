# Ansible Installation

`Install python 3.9 on your system`

`python3.9 -m venv PATH/TO/VENV`

`source PATH/TO/VENV/bin/activate`

`pip install ansible`

`pip install yamllint`

`pip install ansible-lint`

`pip install molecule[docker]`

## Common Commands

`molecule init role myrole`

`molecule init scenario`

`molecule test`

`molecule test --scenario-name scenario-1`

`molecule converge`

`molecule verify`

`molecule login`

`molecule destroy`

`ansible-playbook playbooks/playbook-1.yml`
