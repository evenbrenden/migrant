# migrant

## Start the VM

```
vagrant up
```

Wait until everything has been provisioned and the command terminates. The VM should reboot.

## Log in to the VM

- Username: `vagrant`
- Password: `vagrant`

## SSH into VM

```
vagrant ssh
```

## Destroy the VM

```
vagrant destroy
rm -rf .vagrant/
vagrant box remove ubuntu/bionic64
```
