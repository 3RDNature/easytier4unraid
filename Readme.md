# Easytier for Unraid

A plugin provide easytier(check https://github.com/EasyTier/EasyTier) on unraid so you can connect to VPN before array start.

It still under developing and it is my first unraid plugin.

# Usage

## Start & Stop

```
/etc/rc.d/rc.easytier start
/etc/rc.d/rc.easytier stop
/etc/rc.d/rc.easytier restart
```

## Config

It didn't have a GUI, and simply using config file to control easytier.

You can edit config file at 

```
/boot/config/plugins/easytier/config.toml
```

After you complete configure, you should restart easytier by rc like last chaptor.

## CLI

This plugin provide "easytier-core" and "easytier-cli" command, more details on document of easytier (https://www.easytier.top/guide/introduction.html)