# tailscale-gnome-qs

[<img alt="" height="100" src="https://raw.githubusercontent.com/andyholmes/gnome-shell-extensions-badge/master/get-it-on-ego.svg?sanitize=true">](https://extensions.gnome.org/extension/6139/tailscale-qs/)

##### BUILD (UBUNTU) GNOME EXTENSION

```bash
sudo apt update && sudo apt install make gettext gnome-shell
make build
make install
```

##### CONFIG
Make sure you set yourself tailscale operator

```bash
sudo tailscale set --operator=$USER
```

##### ENABLE EXTNSION ON UBUNTU 22.04 / 22.10

Installing GNOME Shell Extensions on Ubuntu

```bash
sudo apt install gnome-tweaks
```
Know the version of GNOME Shell you are using. This helps determine whether an extension is compatible with your system. You can use the command below to find it:

```bash
gnome-shell --version
```
# Use the gnome-shell-extensions package
Ubuntu (and several other Linux distributions such as Fedora) provide a package with a minimal set of GNOME extensions. You don’t have to worry about compatibility here as it is tested by your Linux distribution.

```bash
sudo apt install gnome-shell-extensions
```

Once installed, log out and re-login to your system. 

After that, start GNOME Extensions App from Overview (found in your applications).

You’ll find a few extensions installed. You can just toggle the button to start using an installed extension.
![image](https://github.com/bencoster/tailscale-gnome-qs/blob/master/Tailscale%20Extension%20Enable%20Screenshot.png)


##### SCREENSHOT

![image](https://github.com/joaophi/tailscale-gnome-qs/assets/23062105/b4209a00-0cd8-45bd-869a-e2a0a7cfdb81)

