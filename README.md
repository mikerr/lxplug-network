# lxplug-network
Wireless and wired networking plugin for lxpanel (based on dhcpcd)


sudo apt-get install automake intltool libgtk2.0-dev libfm-gtk-dev libwnck-dev lxpanel-dev


./autogen

configure

make

sudo cp plugins/.libs/dhcpdui.so /usr/lib/arm-linux-gnueabihf/lxpanel/plugins
