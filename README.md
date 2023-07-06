
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

> Scraper found **8155** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|330|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|330|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|330|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|972|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|567|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|5533|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|5.161.207.168|3128|United States|Ashburn|Hetzner Online GmbH|
|2|148.251.110.152|3128|Germany|Falkenstein|Hetzner Online GmbH|
|3|35.213.91.45|80|Japan|Tokyo|Google LLC|
|4|5.161.207.168|3128|United States|Ashburn|Hetzner Online GmbH|
|5|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|6|34.143.228.238|8080|Singapore|Singapore|Google LLC|
|7|128.199.98.232|3128|Singapore|Singapore|DigitalOcean, LLC|
|8|140.238.58.147|80|Japan|Tokyo|Oracle Corporation|
|9|112.217.162.5|3128|South Korea|Gyeyang-gu|LG DACOM Corporation|
|10|35.240.156.235|8080|Singapore|Singapore|Google LLC|
|11|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|12|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|154.209.253.83|8443|United States|Los Angeles|Shanghai Ruisu Network Technology|
|14|47.251.48.42|8888|United States|Santa Clara|Alibaba.com LLC|
|15|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|16|159.224.243.185|37793|Ukraine|Dnipro|Content Delivery Network LTD|
|17|201.184.24.12|999|Colombia|Bogotá|EPM Telecomunicaciones S.A. E.S.P.|
|18|106.244.154.91|8080|South Korea|Bucheon-si|LG DACOM Corporation|
|19|200.30.138.54|3128|El Salvador|San Salvador|Amnet Datos El Salvador|
|20|91.106.65.107|9812|Iran|Bandar-e Emam Khomeyni|PJSC "Badr Rayan Jonoob"|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

