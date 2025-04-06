# EndeavourOS
Archlinux for Everyone!

To re-run DRACUT: sudo dracut-rebuild

GRUB Editing anything: sudo grub-mkconfig -o /boot/grub/grub.cfg

Remove pamac!
:: a instalação de pacman (6.1.0-3) quebra a dependência "libalpm.so=13-64" necessária por libpamac-aur
:: a instalação de pacman (6.1.0-3) quebra a dependência "pacman<6.1" necessária por libpamac-aur

sudo pacman -R libpamac-aur
