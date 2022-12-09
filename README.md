# migrant

Ubuntu GUI Vagrant file.

## Make and run the VM

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

## Remove the VM

```
vagrant destroy
vagrant box remove ubuntu/bionic64
```
