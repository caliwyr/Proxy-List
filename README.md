
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

> Scraper found **9125** proxies at the latest update. Usable proxies are below.

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
|[proxyscan.io](https://www.proxyscan.io)|0|🚫|
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|1|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1062|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|910|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6169|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|5.161.207.168|3128|United States|Ashburn|Hetzner Online GmbH|
|2|107.148.193.162|1080|United States|San Jose|PEG TECH INC|
|3|13.52.186.184|3128|United States|San Jose|Amazon.com, Inc.|
|4|3.8.8.61|3128|United Kingdom|London|Amazon Technologies Inc.|
|5|194.163.132.232|3128|Germany|Düsseldorf|Contabo GmbH|
|6|5.161.207.168|3128|United States|Ashburn|Hetzner Online GmbH|
|7|107.148.193.162|1080|United States|San Jose|PEG TECH INC|
|8|13.52.186.184|3128|United States|San Jose|Amazon.com, Inc.|
|9|13.115.53.174|3128|Japan|Tokyo|Amazon Technologies Inc|
|10|27.79.53.243|50003|Vietnam|Tan Tien|Viettel Corporation|
|11|140.238.245.116|8100|India|Mumbai|Oracle Corporation|
|12|89.58.60.238|8080|Austria|Vienna|netcup GmbH|
|13|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|14|183.82.100.253|3128|India|Hyderabad|Beam Telecom Pvt Ltd|
|15|45.182.176.38|9947|Brazil|São Paulo|Evolucao Telecom Ltda|
|16|115.144.102.132|10041|South Korea|Mapo-gu|Korea Telecom|
|17|118.97.100.75|8080|Indonesia|Menteng|PT. Telekomunikasi Indonesia|
|18|20.222.85.98|3128|Japan|Tokyo|Microsoft Corporation|
|19|181.167.81.69|8080|Argentina|Buenos Aires|Telecom Argentina S.A|
|20|20.120.240.49|80|United States|Quincy|Microsoft Corporation|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

