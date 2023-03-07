# mikrotik-vultr
wget -qO- https://download.mikrotik.com/routeros/7.8/chr-7.8.img.zip | bsdtar -xvf-

dd if=chr-7.8.img of=/dev/vda
