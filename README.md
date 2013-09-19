3d-printer-settings
===================

Settings for 3D printing tools

You can take the config files in use in your own workstation e.g. like this 

```bash
cd ~
git clone https://github.com/resutoor/3d-printer-settings.git
for ii in 3d-printer-settings/.????*
do
  mv $ii $ii.old
  ln -sf 3d-printer-settings/$ii $ii
done
```
