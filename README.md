
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

> Scraper found **10182** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|645|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|645|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|645|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1358|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1400|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6341|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|66.70.178.214|9300|Canada|Beauharnois|OVH SAS|
|2|43.153.117.113|8800|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|3|116.105.253.231|10003|Vietnam|Hanoi|Viettel Corporation|
|4|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|5|52.221.204.20|3128|Singapore|Singapore|Amazon.com, Inc.|
|6|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|7|18.130.247.181|3128|United Kingdom|London|Amazon Technologies Inc.|
|8|187.189.119.153|999|Mexico|Centro|Total Play Telecomunicaciones SA De CV|
|9|52.221.204.22|3128|Singapore|Singapore|Amazon.com, Inc.|
|10|43.153.117.113|8800|United States|Santa Clara|Shenzhen Tencent Computer Systems Company Limited|
|11|165.232.169.44|8080|Singapore|Singapore|DigitalOcean, LLC|
|12|52.221.204.87|3128|Singapore|Singapore|Amazon.com, Inc.|
|13|18.228.171.241|3128|Brazil|São Paulo|Amazon Technologies Inc.|
|14|52.221.204.102|3128|Singapore|Singapore|Amazon.com, Inc.|
|15|52.221.204.238|3128|Singapore|Singapore|Amazon.com, Inc.|
|16|119.8.10.18|7890|Mexico|Mexico City|Huawei International Pte. LTD|
|17|179.32.62.127|999|Colombia|Bogotá|Colombia Telecomunicaciones S.a. ESP|
|18|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|19|213.171.44.134|3128|Russia|Moscow|JSC Comcor|
|20|200.25.254.193|54240|Colombia|Neiva|Andinet ON Line|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

