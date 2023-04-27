
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

> Scraper found **6250** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|447|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|447|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|447|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1509|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|767|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2891|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|107.152.33.219|8080|United States|Chicago|tzulo, inc.|
|2|64.225.105.92|8080|Germany|Frankfurt am Main|DigitalOcean, LLC|
|3|65.109.128.213|8080|Finland|Helsinki|Hetzner Online GmbH|
|4|65.108.157.140|8080|Finland|Helsinki|Hetzner Online GmbH|
|5|47.74.34.81|1111|Japan|Tokyo|Alibaba.com LLC|
|6|62.210.209.223|3128|France|Paris|Online S.A.S.|
|7|20.93.42.101|8080|Ireland|Dublin|Microsoft Corporation|
|8|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|9|107.152.33.219|8080|United States|Chicago|tzulo, inc.|
|10|167.99.116.111|8001|United States|Clifton|DigitalOcean, LLC|
|11|51.159.0.236|3128|France|Paris|SCALEWAY|
|12|61.28.233.217|3128|Vietnam|Ho Chi Minh City|Vinadata broadcast via vinagame AS Number|
|13|117.1.242.234|4001|Vietnam|Hanoi|Viettel Corporation|
|14|27.54.96.11|18081|Japan|Kirishima Shi|Minamikyusyu CableTV Net Inc.|
|15|35.247.199.47|3129|Brazil|Sao Paulo|Google LLC|
|16|14.37.44.69|8080|South Korea|Seo-gu|Korea Telecom|
|17|158.160.56.149|8080|Russia|Moscow|Yandex.Cloud LLC|
|18|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|19|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|20|46.29.165.166|8123|Russia|Moscow|BNET|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

