
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

> Scraper found **5672** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|274|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|274|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|274|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1287|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|624|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2678|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.247.248.45|3129|Brazil|Sao Paulo|Google LLC|
|2|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|3|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|4|35.247.214.238|3129|Brazil|Sao Paulo|Google LLC|
|5|35.247.199.249|3129|Brazil|Sao Paulo|Google LLC|
|6|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|7|35.247.205.198|3129|Brazil|Sao Paulo|Google LLC|
|8|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|9|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|10|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|11|139.59.228.95|8118|Singapore|Singapore|DIGITALOCEAN|
|12|8.219.234.30|7777|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|35.247.197.36|3129|Brazil|Sao Paulo|Google LLC|
|14|35.247.218.71|3129|Brazil|Sao Paulo|Google LLC|
|15|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|16|109.205.112.184|80|Iraq|Al Yarmuk|ScopeSky for communications, internet and technology services LLC|
|17|73.242.86.12|8118|United States|Minnetonka|Comcast Cable Communications|
|18|115.144.101.201|10001|South Korea|Gangdong-gu|Korea Telecom|
|19|36.255.84.5|83|India|Bengaluru|Gatik Business Solutions|
|20|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

