# ⚙️ Config files for [Ranger](https://github.com/ranger/ranger)
<div align="center">
<a href="https://ranger.fm/">
<img src="https://ranger.fm/ranger_logo.png" width="200">
</a>
</div>

## Installing
```bash
# Make a backup
mv ~/.config/ranger{,.bak}

# Clone the config files
git clone https://github.com/fulld0s/ranger.git ~/.config/ranger
```

## Install [ranger_devicons](https://github.com/alexanderjeurissen/ranger_devicons)
Ranger has added support for loading directories in the plugins folder which makes it easier to install and keep plugins updated.
To install, just clone the repo into the plugins folder:
```bash
git clone https://github.com/alexanderjeurissen/ranger_devicons ~/.config/ranger/plugins/ranger_devicons
```
Then execute the following `echo "default_linemode devicons" >> $HOME/.config/ranger/rc.conf` (or wherever your `rc.conf` is located).

## [Dependencies](https://github.com/ranger/ranger?tab=readme-ov-file#dependencies)
