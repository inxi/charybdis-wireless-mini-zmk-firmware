```bash
git clone https://github.com/280Zo/charybdis-wireless-mini-zmk-firmware.git
cd charybdis-wireless-mini-zmk-firmware
rm -rf config
git clone ssh://git@git.chernousov.me:2224/chernousov/config-charybdis-zmk.git config
cd local-build
docker compose run --rm builder
```
