

```
echo 'src/gz ipks https://raw.githubusercontent.com/LancerSky/ipks/main/18.06/mips_24kc' >> /etc/opkg/customfeeds.conf
```



If you failed to download `Packages.sig`, you need to remove `option check_signature` from `/etc/opkg.conf`.

