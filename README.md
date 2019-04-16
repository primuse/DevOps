# Creating a Virtual machine
Creating a server will give you insights into how servers work and help you be successful any time you’re working with a server in the future.

## Prerequisites
- 1 A laptop/ desktop with at least 4gb RAM
- 2 Download and install Vagrant from [here](https://www.vagrantup.com/downloads.html)
- 3 Download and install Virtual box [here](https://www.virtualbox.org/wiki/Downloads)

## Getting Started

Start by cloning this repo.

```
git clone https://github.com/primuse/DevOps.git
```
After cloning the repo `cd` into it and run `vagrant up` in the terminal to start the virtual machine.

![Terminal 1](assets/terminal.png "Terminal 1")

Run `vagrant global-status` to see all virtual machines and to confirm ours is running.

![Terminal 2](assets/terminal2.png "Terminal 2")

Run `vagrant ssh` to ssh into the virtual machine.

![Terminal 3](assets/terminal3.png "Terminal 3")

You should see a prompt with this `vagrant@ubuntu-bionic:~$` to show that you are currently in a full-fledged SSH session. You can go ahead and interact with the machine and do whatever you want.

The possibilities are endless.
