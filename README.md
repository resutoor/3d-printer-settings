3d-printer-settings
===================

Settings for 3D printing tools

You can take the config files in use in your own workstation e.g. like this 

```bash
cd ~
git clone https://github.com/resutoor/3d-printer-settings.git
for ii in 3d-printer-settings/.????*
do
  iib=$(basename $ii)
  test -e $iib || mv $iib $iib.old
  ln -sf $ii $iib
done
```
