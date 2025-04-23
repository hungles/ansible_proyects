# SSH Key Copy Program

This program is designed to copy your SSH keys from the machine running the program to a specified user on target machines. The user to which the keys will be copied can be specified in the `user: insertar_usuario` section of the `copy-sshkey.yml` file.

## Requirements

1. The target machines must have the same username and password.
2. The specified users on the target machines must have root privileges.
3. Ansible will use these credentials to perform the operations.

## Usage

1. Open the `copy-sshkey.yml` file.
2. Replace `isert_user` in the `user:` section with the desired username.
3. Run the program using Ansible to copy the SSH keys to the specified user on the target machines.

Ensure that all target machines meet the requirements before executing the program.