# VirtualBox Guest Machine init.d service

Start Virtual Box Machine on startup in Ubuntu. And more..

## Usage

1) Change "vbox-server" file with Virtual Machines owner username and Virtual Machines ID (`$ vboxmanage list vms`)

2) `sudo cp vbox-server /etc/init.d/vbox-server`

3) `sudo chmod +x /etc/init.d/vbox-server`

4) `sudo update-rc.d vbox-server defaults`

5) Reboot host machine, if it's necessary, or just run `sudo /etc/init.d/vbox-server start`
