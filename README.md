
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

> Scraper found **9899** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|536|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|536|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|536|

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
|[proxylist.geonode.com](https://proxylist.geonode.com/api/proxy-list?limit=300&page=1&sort_by=lastChecked&sort_type=desc&protocols=http,https)|0|✅|
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1245|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|1129|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6442|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|115.144.101.201|10001|South Korea|Mapo-gu|Korea Telecom|
|2|195.154.185.32|3128|France|Vitry-sur-Seine|Online S.A.S.|
|3|191.186.106.34|8080|Brazil|São Paulo|Claro NXT Telecomunicacoes Ltda|
|4|144.217.253.209|9300|Canada|Beauharnois|OVH SAS|
|5|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|6|200.105.215.22|33630|Bolivia|La Paz|AXS Bolivia S. A.|
|7|136.243.55.199|3128|Germany|Falkenstein|Hetzner Online GmbH|
|8|103.168.58.150|3128|Vietnam|Cau Giay|Floor 5, 255 Tran Dang Ninh, Dich Vong, Cau Giay District, Ha Noi City|
|9|209.38.254.44|45212|Germany|Frankfurt am Main|DigitalOcean, LLC|
|10|209.38.201.164|45212|Germany|Frankfurt am Main|DigitalOcean, LLC|
|11|103.177.176.70|4343|Indonesia|Klender|PT Milenial Inti Telekomunikasi|
|12|5.188.154.104|8080|Kazakhstan|Almaty|NLS|
|13|103.115.20.4|8181|Indonesia|Subang|PMYNET|
|14|37.120.192.154|8080|Netherlands|Amsterdam|M247 Europe SRL|
|15|212.174.17.73|8085|Turkey|Gaziantep|Turk Telekomunikasyon Anonim Sirketi|
|16|94.228.204.225|41890|Russia|Moscow|Uniontel ZAO network|
|17|58.69.32.226|8081|Philippines|Mandaluyong City|Philippine Long Distance Telephone Co.|
|18|64.225.8.115|9968|United States|Clifton|DigitalOcean, LLC|
|19|190.12.121.35|999|Argentina|Avellaneda|CPS|
|20|217.117.29.68|3128|Lithuania|Vilnius|UAB "Baltnetos komunikacijos"|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

