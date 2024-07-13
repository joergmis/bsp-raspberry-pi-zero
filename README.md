# bsp-raspberry-pi-zero

Image for the raspberry pi zero 2, built using [kas](https://kas.readthedocs.io/en/latest/index.html).

```sh
# generate the file to automatically connect to the wifi
wpa_passphrase 'your-wifi-name' > layers/meta-iot/recipes-core/wpa-supplicant/files/wpa_supplicant-nl80211-wlan0.conf

# build the image
kas build ./conf.yml
```

## Resources

- [how to configure networking using systemd in yocto / mender hub](https://hub.mender.io/t/how-to-configure-networking-using-systemd-in-yocto-project/1097/1)
