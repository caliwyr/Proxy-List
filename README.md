
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

> Scraper found **8260** proxies at the latest update. Usable proxies are below.

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|🚫|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|947|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|371|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|5859|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|129.159.112.251|3128|United States|Ashburn|Oracle Corporation|
|2|8.209.114.72|3129|Germany|Frankfurt am Main|Alibaba.com Singapore E-Commerce Private Limited|
|3|35.213.91.45|80|Japan|Tokyo|Google LLC|
|4|129.159.112.251|3128|United States|Ashburn|Oracle Corporation|
|5|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|6|20.219.182.59|3129|India|Pune|Microsoft Corporation|
|7|173.176.14.246|3128|Canada|Vaudreuil-Dorion|Le Groupe Videotron Ltee|
|8|31.170.62.240|8080|Iran|Shiraz|Farahoosh Dena PLC|
|9|117.251.103.186|8080|India|Hazratpur|BSNL Internet|
|10|112.217.162.5|3128|South Korea|Gyeyang-gu|LG DACOM Corporation|
|11|125.25.32.240|8080|Thailand|Chiang Mai|TOT Public Company Limited|
|12|217.61.247.50|3128|Sweden|Stockholm|Elastx AB|
|13|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|14|35.213.91.45|80|Japan|Tokyo|Google LLC|
|15|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|16|45.167.253.129|999|Mexico|San Luis Potosí City|QDS NETWORKS SA DE CV|
|17|122.155.165.191|3128|Thailand|Vadhana|CAT Telecom Public Company Limited|
|18|183.221.242.103|9443|China|Mianyang|China Mobile|
|19|41.76.145.136|8080|Mozambique|Maputo|VM  S.A|
|20|45.224.22.177|999|Ecuador|Riobamba|Nedetel S.A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

