
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

> Scraper found **5914** proxies at the latest update. Usable proxies are below.

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1254|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|728|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2849|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.247.228.52|3129|Brazil|Sao Paulo|Google LLC|
|2|144.126.141.115|1010|United States|St Louis|Contabo Inc.|
|3|35.247.236.15|3129|Brazil|Sao Paulo|Google LLC|
|4|51.159.0.236|3128|France|Paris|SCALEWAY|
|5|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|6|66.228.53.77|8080|United States|Richardson|Akamai Technologies, Inc.|
|7|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|8|35.247.208.123|3129|Brazil|Sao Paulo|Google LLC|
|9|40.117.59.214|3128|United States|Boydton|Microsoft Corporation|
|10|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|11|20.93.42.101|8080|Ireland|Dublin|Microsoft Corporation|
|12|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|13|144.126.141.115|1010|United States|St Louis|Contabo Inc.|
|14|192.155.82.99|8080|United States|Fremont|Akamai Technologies, Inc.|
|15|181.205.44.219|8080|Colombia|Medellín|EPM Telecomunicaciones S.A. E.S.P.|
|16|43.156.100.152|80|Singapore|Singapore|Shenzhen Tencent Computer Systems Company Limited|
|17|68.132.12.228|8888|United States|Staten Island|Verizon Communications|
|18|103.167.170.50|8080|Indonesia|Tangerang|PT Rajeg Media Telekomunikasi|
|19|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|20|27.54.96.11|18081|Japan|Kirishima Shi|Minamikyusyu CableTV Net Inc.|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

