# unifi-nat66
Simple deb package to enable persistent NAT66 on unifi devices with systemd

## note:
Just adding a plain systemd unit appears to provide better persistence with a simpler and more maintainable setup experience:
https://github.com/HPPinata/Notizen/tree/main/unifi

Install over SSH:
```
ssh root@unifi "curl -Lo nat66-systemd.deb https://github.com/HPPinata/unifi-nat66/releases/download/0.2/nat66-systemd_0.2_all.deb && dpkg -i nat66-systemd.deb"
```
