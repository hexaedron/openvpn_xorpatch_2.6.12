# openvpn_xorpatch_2.6.12
XOR patch for OpenVPN 2.6.12

Works for me in OPNsense 24.7.3_1 (FreeBSD 14.1)

## How to build for FreeBSD/OPNSense/pfSense
```bash
cd openvpn_xorpatch_2.6.12/openvpn-2.6.12
./configure CFLAGS="-I/usr/local/include" LDFLAGS="-L/usr/local/lib" --disable-selinux --disable-systemd
make install
```
