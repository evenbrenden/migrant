# migrant

Ubuntu GUI Vagrant box.

## Make and run the VM

```
vagrant up
```

Wait until everything has been provisioned, the command terminates and the VM reboots.

Set up "Shared Clipboard" in VirtualBox via "Machine" -> "Settings" -> "Advanced".

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
vagrant box remove ubuntu/focal64
```
