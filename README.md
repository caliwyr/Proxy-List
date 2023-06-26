
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

> Scraper found **9236** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|328|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|328|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|328|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|952|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|781|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6420|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.213.91.45|80|Japan|Tokyo|Google LLC|
|2|117.3.241.72|50003|Vietnam|Hanoi|Viettel Corporation|
|3|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|4|171.226.91.210|14023|Vietnam|Hanoi|Viettel Corporation|
|5|116.111.217.203|11010|Vietnam|Tan Tien|Viettel Corporation|
|6|27.79.51.231|50003|Vietnam|Tan Tien|Viettel Corporation|
|7|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|8|117.3.246.90|50003|Vietnam|Hanoi|Viettel Corporation|
|9|129.154.225.163|8100|India|Mumbai|Oracle Corporation|
|10|103.171.241.9|8080|Indonesia|Jakarta|PT Abs Multimedia Indonesia|
|11|8.219.170.236|3128|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|12|202.86.138.18|8080|Macao|Macao|Companhia de Telecomunicacoes de Macau|
|13|81.12.44.197|3129|Iran|Tehran|RESPINA Networks|
|14|27.79.50.15|10008|Vietnam|Tan Tien|Viettel Corporation|
|15|173.176.14.246|3128|Canada|Vaudreuil-Dorion|Le Groupe Videotron Ltee|
|16|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|17|115.144.222.174|12639|South Korea|Jung-gu|Korea Telecom|
|18|195.222.165.209|3128|Russia|Moscow|PJSC "Vimpelcom"|
|19|18.190.21.166|80|United States|Dublin|Amazon.com, Inc.|
|20|62.171.161.88|2018|Germany|Nuremberg|Contabo GmbH|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

