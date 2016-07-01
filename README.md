# vminit
Init Virtual Box Virtual Machine on startup in Ubuntu

## Usage

1) Change "vminit" file with Virtual Machines owner username and Virtual Machines ID

2) `sudo cp vminit /etc/init.d/vminit`

3) `sudo chmod +x /etc/init.d/vminit`

4) `sudo update-rc.d vminit defaults`

5) Reboot host machine, if it's necessary, or just run `sudo /etc/init.d/vminit start`
