# Local Ansible
This is the only repo needed to setup work machine. `cron.yml` makes sure changes are automatically deployed on local machine

# Assumed
- Debian-like distro
- user with sudo
- ssh key connected to github
- ensure ansible-pull can be run by sudo

# Commands to run before
`sudo apt install pipx`
`pipx install --include-deps ansible`


# To apply this ansible
`sudo ansible-pull -U https://github.com/frozenbanana/local-ansible.git`

# Source to setup this repo
https://opensource.com/article/18/3/manage-your-workstation-configuration-ansible-part-1
