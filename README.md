## wireguard-install
WireGuard installer for Ubuntu, Debian, AlmaLinux, Rocky Linux, CentOS and Fedora.
This Installer can be also used on LXC containers, without root access to host machine.

This script will let you set up your own VPN server in no more than a minute, even if you haven't used WireGuard before. It has been designed to be as unobtrusive and universal as possible.

### Installation
Run the script and follow the assistant:

`wget https://raw.githubusercontent.com/syntheticore-dev/wireguard-install/refs/heads/master/wireguard-install.sh -O wg-manage.sh && bash wg-manage.sh`

Once it ends, you can run `bash wg-manage.sh` to add more users, remove some of them or even completely uninstall WireGuard.
