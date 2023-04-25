
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

> Scraper found **5309** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|256|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|256|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|256|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1010|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|624|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|2592|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|35.247.230.245|3129|Brazil|Sao Paulo|Google LLC|
|2|35.247.247.141|3129|Brazil|Sao Paulo|Google LLC|
|3|35.247.243.5|3129|Brazil|Sao Paulo|Google LLC|
|4|20.93.42.101|8080|Ireland|Dublin|Microsoft Corporation|
|5|68.132.12.228|8888|United States|Staten Island|Verizon Communications|
|6|68.132.12.228|8888|United States|Staten Island|Verizon Communications|
|7|144.126.141.115|1010|United States|St Louis|Contabo Inc.|
|8|35.247.198.196|3129|Brazil|Sao Paulo|Google LLC|
|9|103.69.108.78|8191|Philippines|Santiago|CITI Cableworld Inc.|
|10|212.46.230.102|6969|Russia|Moscow|PJSC "Vimpelcom"|
|11|35.247.243.231|3129|Brazil|Sao Paulo|Google LLC|
|12|8.219.97.248|80|Singapore|Singapore|Alibaba (US) Technology Co., Ltd.|
|13|58.27.197.2|8080|Pakistan|Lahore|Wateen Telecom Limited|
|14|186.121.235.66|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|15|115.144.101.201|10001|South Korea|Gangdong-gu|Korea Telecom|
|16|86.57.156.106|2222|Belarus|Minsk|Republican Unitary Telecommunication Enterprise Beltelecom|
|17|163.177.106.4|8001|China|Shenzhen|China Unicom Guangdong Province Network|
|18|23.132.185.101|53128|Norway|Sandefjord|Joseph Farnell|
|19|213.83.46.204|3128|Germany|Frankfurt am Main|Plus.line AG|
|20|35.247.213.229|3129|Brazil|Sao Paulo|Google LLC|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

