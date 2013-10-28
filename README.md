dwordlist
=========

Autocomplete for X11.

### Dependencies
- dmenu;
- xte from the xautomation metapackage;
- Arch users will need the words package.

### Installation
- Resolve dependencies. On Debian, this means:

`sudo apt-get install dmenu xautomation`
- place dwordlist in your PATH and make sure it's executable.

```
sudo cp dwordlist /usr/bin/
sudo chmod +x /usr/bin/dwordlist
```
- bind some key to the dwordlist command (I personally use alt+enter). xbindkeys is recommended. If you're using a desktop environment, it probably provides a feature for this already. Look in your DE's settings.
