## About
[WireGuard](https://www.wireguard.com/) (WG) is a communication protocol and free and open-source software that implements encrypted virtual private networks, and was designed with the goals of ease of use, high speed performance, and low attack surface. The default settings don't necessarily mean bad for everyone, but isn't a silver bullet too.

This is just another WG installer project, but with the assumption that the users would be using home ISPs.

## Installation
> ⚠️ Rebooting your OS might be resulting in you couldn't remove the added users/configs later and have to remove them manually.
- Clone this repo;
- Run the script; and
- Follow the setup instructions
```
$ git clone https://github.com/galpt/wg-home.git
$ cd wg-home
$ sudo bash wireguard-install.sh
```

Once it ends, you can run it again to add more users, remove some of them or even completely uninstall WireGuard.

## FAQ
### I want to run my own VPN, but don't have a server for that?
A cheap VPS with a decent monthly data transfer quota would do. Some of them might be Linode, Vultr, DigitalOcean, and more.

### Finally got it running, but how come I couldn't open some websites?
It's starting to become a new issue that some websites take the innitiative to block traffic from commonly known cloud providers.
Getting a VPS from your local cloud providers might be less tempting, as they usually don't have good enough peering, but they got you clean IP addresses!

## Credits

Thanks to [Nyr](https://github.com/Nyr) for making the project.
You can check the original project [here](https://github.com/Nyr/wireguard-install).
