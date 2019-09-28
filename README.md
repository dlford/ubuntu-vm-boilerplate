# ubuntu-vm-boilerplate

A simple bash script to handle boilerplate configurations for new Ubuntu VMs (Machine ID, SSH server keys, Hostname)

## Usage

Run the following command from a bash session, you will be prompted for a new hostname, and whether you wish to reboot the system.

```sh
sudo bash -c "bash <(wget -qO- https://raw.githubusercontent.com/dlford/ubuntu-vm-boilerplate/master/run.sh)"
```
