
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

> Scraper found **9192** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|429|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|429|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|429|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|5|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1043|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|878|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6183|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|107.148.94.92|80|United States|Los Angeles|PEG TECH INC|
|2|107.148.94.92|80|United States|Los Angeles|PEG TECH INC|
|3|35.240.156.235|8080|Singapore|Singapore|Google LLC|
|4|3.8.114.236|3128|United Kingdom|London|Amazon Technologies Inc.|
|5|18.143.215.49|80|Singapore|Singapore|Amazon Technologies Inc.|
|6|213.171.44.134|3128|Russia|Moscow|JSC Comcor|
|7|8.209.114.72|3129|Germany|Frankfurt am Main|Alibaba.com Singapore E-Commerce Private Limited|
|8|3.73.177.183|8888|Germany|Frankfurt am Main|Amazon Technologies Inc.|
|9|47.250.45.81|7890|Malaysia|Kuala Lumpur|Alibaba.com LLC|
|10|45.5.116.152|999|Guatemala|Guatemala City|Inversiones Grajeda Andrade S.A|
|11|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|144.217.119.85|3207|Canada|Beauharnois|OVH Hosting|
|13|200.37.42.43|999|Peru|Caraz|Telefonica del Peru S.A.A.|
|14|103.134.44.176|8080|India|Haridwar|Countrylink Communiction Pvt Ltd|
|15|51.158.147.163|1234|France|Paris|SCALEWAY|
|16|114.7.27.98|8080|Indonesia|Baru Ilir|PT. INDOSAT Tbk|
|17|203.150.128.213|8080|Thailand|Vadhana|Internet Thailand Company Ltd|
|18|54.183.251.57|3128|United States|San Jose|Amazon.com, Inc.|
|19|34.220.121.241|3128|United States|Portland|Amazon.com, Inc.|
|20|165.227.164.49|3128|Germany|Frankfurt am Main|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

