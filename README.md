# linux-kernel-config
Repository for .config Vivobook S15

`sudo cp config /usr/src/linux/.config`
`make -j3 && make modules_install && mount /boot && make install && grub-mkconfig -o /boot/grub/grub.cfg`
