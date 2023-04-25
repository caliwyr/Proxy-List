
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

> Scraper found **5370** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|239|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|239|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|239|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1107|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|588|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2592|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|2|40.119.236.22|80|Singapore|Singapore|Microsoft Corporation|
|3|148.251.123.98|7777|Germany|Sangerhausen|Hetzner Online GmbH|
|4|204.2.218.145|8080|United States|Calhoun|North Georgia Network Cooperative, Inc.|
|5|91.107.207.116|8080|Germany|Frankfurt Am Main|Hetzner Online AG|
|6|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|7|35.247.199.47|3129|Brazil|Sao Paulo|Google LLC|
|8|35.247.247.254|3129|Brazil|Sao Paulo|Google LLC|
|9|177.8.169.79|8082|Brazil|São Paulo|Grupohost Comunicacao Multimidia Ltda|
|10|35.247.248.104|3129|Brazil|Sao Paulo|Google LLC|
|11|158.160.56.149|8080|Russia|Moscow|Yandex.Cloud LLC|
|12|154.70.107.81|3128|Cameroon|Douala|MTN Network Solutions (Cameroon)|
|13|68.132.12.228|8888|United States|Staten Island|Verizon Communications|
|14|49.12.209.36|3128|Germany|Falkenstein|Hetzner Online GmbH|
|15|41.78.24.126|32371|Kenya|Nairobi|Xtranet Communications Ltd|
|16|144.126.141.115|1010|United States|St Louis|Contabo Inc.|
|17|43.156.100.152|80|Singapore|Singapore|Shenzhen Tencent Computer Systems Company Limited|
|18|178.18.206.184|53128|Turkey|Bayrakli|Vargonen Teknoloji ve Bilisim Sanayi Ticaret Anonim Sirketi|
|19|158.69.71.245|9300|Canada|Montreal|OVH SAS|
|20|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

