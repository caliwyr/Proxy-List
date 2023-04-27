
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

> Scraper found **5880** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|389|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|389|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|389|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1246|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|759|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2792|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|144.126.141.115|1010|United States|St Louis|Contabo Inc.|
|2|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|3|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|4|210.172.199.88|8080|Japan|Gifu|KITAGATA|
|5|20.241.236.196|3128|United States|Boydton|Microsoft Corporation|
|6|144.126.141.115|1010|United States|St Louis|Contabo Inc.|
|7|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|8|35.247.240.206|3129|Brazil|Sao Paulo|Google LLC|
|9|181.204.22.170|999|Colombia|Cartagena|EPM Telecomunicaciones S.A. E.S.P.|
|10|43.156.100.152|80|Singapore|Singapore|Shenzhen Tencent Computer Systems Company Limited|
|11|117.1.242.234|4001|Vietnam|Hanoi|Viettel Corporation|
|12|203.188.32.107|9812|Thailand|Chatuchak|KSC Commercial Internet Co.Ltd|
|13|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|14|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|15|185.16.61.36|45212|Germany|Karlsruhe|netcup GmbH|
|16|2.179.193.146|80|Iran|Juybar|Iran Telecommunication Company PJS|
|17|65.108.48.232|8080|Finland|Helsinki|Hetzner Online GmbH|
|18|8.219.234.30|7777|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|19|68.183.185.62|80|Singapore|Singapore|DigitalOcean, LLC|
|20|64.225.4.12|9995|United States|Clifton|DigitalOcean, LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

