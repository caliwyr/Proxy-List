
# Free HTTP Proxy List 🌍

[![Every 10 Minutes Update](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/mertguvencli/http-proxy-list/actions/workflows/main.yml)
![GitHub](https://img.shields.io/github/license/mertguvencli/http-proxy-list)
![GitHub last commit](https://img.shields.io/github/last-commit/mertguvencli/http-proxy-list)
[![zevtyardt - proxy-list](https://img.shields.io/static/v1?label=zevtyardt&message=proxy-list&color=blue&logo=github)](https://github.com/zevtyardt/proxy-list "Go to GitHub repo")
[![stars - proxy-list](https://img.shields.io/github/stars/zevtyardt/proxy-list?style=social)](https://github.com/zevtyardt/proxy-list)
[![forks - proxy-list](https://img.shields.io/github/forks/zevtyardt/proxy-list?style=social)](https://github.com/zevtyardt/proxy-list)
[![Proxy Updater](https://github.com/zevtyardt/proxy-list/workflows/Proxy%20Updater/badge.svg)](https://github.com/zevtyardt/proxy-list/actions?query=workflow:"Proxy+Updater")
![GitHub repo size](https://img.shields.io/github/repo-size/zevtyardt/proxy-list)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/zevtyardt/proxy-list?logo=commits)](https://github.com/zevtyardt/proxy-list/commits/main)

It is a lightweight project that, every 10 minutes, scrapes lots of free-proxy sites, validates if it works, and serves a clean proxy list.

> Scraper found **7554** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|256|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|256|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|256|

## Sources

|Source|Found Proxies|Succeed|
|------|-------------|-------|
|[free-proxy-list.net](https://free-proxy-list.net)|300|✅|
|[us-proxy.org](https://www.us-proxy.org)|200|✅|
|[proxydb.net](http://proxydb.net)|15|✅|
|[free-proxy-list.com](https://free-proxy-list.com/?page=&port=&type%5B%5D=http&type%5B%5D=https&up_time=0&search=Search)|10|✅|
|[proxy-list.download](https://www.proxy-list.download/HTTP)|26|✅|
|[vpnoverview.com](https://vpnoverview.com/privacy/anonymous-browsing/free-proxy-servers)|32|✅|
|[proxyscan.io](https://www.proxyscan.io)|100|✅|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|785|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|508|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|5178|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.213.91.45|80|Japan|Tokyo|Google LLC|
|2|62.171.150.234|3128|Germany|Nuremberg|Contabo GmbH|
|3|193.233.202.75|8080|United States|Ashburn|Alexhost SRL|
|4|118.99.127.176|8080|Indonesia|Malang|Biznet Metronet|
|5|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|6|65.109.169.211|39119|Finland|Helsinki|Hetzner Online GmbH|
|7|135.125.68.145|3128|France|Roubaix|OVH SAS|
|8|47.251.48.42|8888|United States|Santa Clara|Alibaba.com LLC|
|9|47.251.48.42|8888|United States|Santa Clara|Alibaba.com LLC|
|10|103.204.208.208|8080|Bangladesh|Dhaka|Level3 Carrier Limited|
|11|193.233.202.75|8080|United States|Ashburn|Alexhost SRL|
|12|35.213.91.45|80|Japan|Tokyo|Google LLC|
|13|103.123.5.58|8080|China|Yangjiaping|CHINA UNICOM China169 Backbone|
|14|179.48.11.6|8085|Brazil|Campo Maior|Carnaubanet Ltda|
|15|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|16|47.242.3.214|8081|Hong Kong|Hong Kong|Alibaba.com LLC|
|17|117.69.237.248|8089|China|Rongcheng|Chinanet|
|18|201.184.24.14|999|Colombia|Bogotá|EPM Telecomunicaciones S.A. E.S.P.|
|19|156.59.100.138|3128|Hong Kong|Hong Kong|Zenlayer Inc|
|20|183.91.3.22|11022|Vietnam|Hanoi|CMC Telecom Infrastructure Company|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

