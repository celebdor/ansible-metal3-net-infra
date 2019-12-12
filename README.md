# Metal-3-net-infra

This will set up networking infra for more complex metal3-dev-env environments

## Usage
Provision:

```
$ sudo WORKING_DIR=/data/backed/net-infra ansible-playbook -vvv -i inventory provision.yml
```

Clean up:

```
$ sudo WORKING_DIR=/data/backed/net-infra ansible-playbook -vvv -i inventory cleanup.yml
```
