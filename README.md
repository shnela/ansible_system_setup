## Configure remote host
`ansible-playbook laptop-playbook.yml --ask-sudo-pass`

On Arch/Debian machines install:
 * Dev packages
 * 
For Arch linux:
 * Gnome packages
 * Necessary AUR packages

## Create custom ssh key and copy to remote machine

`ansible-playbook ./playbooks/copy_ssh-playbook.yml  --extra-vars "remote_host=" --ask-pass`

