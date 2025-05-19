# OIIA OIIA Spinning Cat Plymouth Theme

This is a simple plymouth theme that displays a spinning cat while your system starts.

## Dependencies:
Have plymouth installed and enabled.
If you have not yet installed plymouth: https://wiki.archlinux.org/title/Plymouth

## How to install:
Simply clone this repo, move it into `/usr/share/plymouth/themes/` and enable it.
```shell
git clone https://github.com/mango7006/cattheme
mv -r cattheme /usr/share/plymouth/themes/
plymouth-set-default-theme -R cattheme
```

## TODO:
- Contemplate My Life Choices
- Make more dumb themes
