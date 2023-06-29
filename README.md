
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

> Scraper found **8539** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|409|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|409|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|409|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1104|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|749|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|5603|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.213.91.45|80|Japan|Tokyo|Google LLC|
|2|173.176.14.246|3128|Canada|Vaudreuil-Dorion|Le Groupe Videotron Ltee|
|3|171.227.7.254|50003|Vietnam|Gia Nghia|Viettel Corporation|
|4|135.125.68.145|3128|France|Roubaix|OVH SAS|
|5|117.3.241.173|50003|Vietnam|Hanoi|Viettel Corporation|
|6|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|7|118.69.111.51|8080|Vietnam|Ho Chi Minh City|FPT Telecom Company|
|8|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|9|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|10|171.234.229.63|4001|Vietnam|Hanoi|Viettel Corporation|
|11|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|12|45.62.161.17|8080|Thailand|Bangkok|RAM Host|
|13|8.209.114.72|3129|Germany|Frankfurt am Main|Alibaba.com Singapore E-Commerce Private Limited|
|14|138.199.41.122|8888|United States|New York|Datacamp Limited|
|15|20.120.240.49|80|United States|Quincy|Microsoft Corporation|
|16|35.213.91.45|80|Japan|Tokyo|Google LLC|
|17|89.19.208.184|3128|Poland|Warsaw|Artnet Sp. z o.o.|
|18|190.97.240.10|1994|Venezuela|Vigia|Viginet C.A|
|19|167.71.225.180|3128|India|Bengaluru|DigitalOcean, LLC|
|20|41.76.145.136|3128|Mozambique|Maputo|VM  S.A|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

