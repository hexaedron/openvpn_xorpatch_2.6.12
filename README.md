# openvpn_xorpatch_2.6.12
XOR patch for OpenVPN 2.6.12. Based on https://github.com/clayface/openvpn_xorpatch

Works for me in OPNsense 24 and 25 (FreeBSD 14.1 and 14.2)

## How to build for FreeBSD/OPNSense/pfSense
```bash
cd openvpn_xorpatch_2.6.12/openvpn-2.6.12
./configure CFLAGS="-I/usr/local/include" LDFLAGS="-L/usr/local/lib" --disable-selinux --disable-systemd
make install
```
