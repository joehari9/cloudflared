# cloudflared
Openwrt cloudflared installation</br>
1.login ssh using putty or another ssh client tools and execute command bellow</br></br>
VERSION get the latest version in https://github.com/cloudflare/cloudflared

```
VERSION="2024.6.1"

curl -O -L \
  https://github.com/cloudflare/cloudflared/releases/download/${VERSION}/cloudflared-linux-arm \
&& chmod +x cloudflared-linux-arm \
&& mv cloudflared-linux-arm /usr/bin/cloudflared
```
2. get your token from cloudflare page in tunnel path and paste your token in TOKEN secsion in command bellow

```
TOKEN="your_actual_token"
curl -o install.sh https://raw.githubusercontent.com/yourusername/yourrepository/branchname/install.sh
sed -i "s/<yourtoken>/${TOKEN}/g" install.sh
chmod +x install.sh
./install.sh
```
