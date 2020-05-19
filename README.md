# gfw_whitelist

The GFW whitelist of AutoProxy format.

gfw_whitelist URL: [https://raw.githubusercontent.com/neko-dev/gfw_whitelist/master/gfw_whitelist.txt](https://raw.githubusercontent.com/neko-dev/gfw_whitelist/master/gfw_whitelist.txt)

## Usagage of gfw_whitelist

### SwitchyOmega

Install [SwitchyOmega](https://chrome.google.com/webstore/detail/padekgcemlokbadohgkifijomclgjgif) Chrome extension.

Create a Switch Profile, `Default` use the proxy profile, add a rule list(AutoProxy format) and fill the `gfw_whitelist URL`. `Rule list rules` use the `Direct` profile.

![](https://ooo.0o0.ooo/2017/01/24/5886e09252eb6.png)

![](https://ooo.0o0.ooo/2017/01/24/5886e0925da91.png)

## Usage of AutoProxy-Editor.jar

`java -jar AutoProxy-Editor.jar gfw_whitelist.txt` to add domains into `gfw_whitelist.txt`

[AutoProxy Rules](https://github.com/neko-dev/gfw_whitelist/blob/master/AutoProxy_Rules.md)

```txt
This tools can help you to edit AutoProxy file.
Use 'add' to add a domain.
Use 'remove' to remove a domain.
Use 'show' to show the list.
Use 'load' to load autoproxy file from disk.
Use 'save' to save autoproxy file to disk.
Use 'help' to show this help message.
You can use 'help [command]' to show help message for that command.
```

## Usage of commit.jar

`java -jar commit.jar` to to commit the `gfw_whitelist` in a formal format.

### Source: [https://github.com/Omico/gfw_whitelist-CommitTool](https://github.com/Omico/gfw_whitelist-CommitTool)
