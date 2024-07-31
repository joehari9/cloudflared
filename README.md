# cloudflared
openwrt cloudflared installation
VERSION get the latest version in https://github.com/cloudflare/cloudflared
```
VERSION="2024.6.1"

curl -O -L \
  https://github.com/cloudflare/cloudflared/releases/download/${VERSION}/cloudflared-linux-arm \
&& chmod +x cloudflared-linux-arm \
&& mv cloudflared-linux-arm /usr/bin/cloudflared
```
