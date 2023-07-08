
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

> Scraper found **9253** proxies at the latest update. Usable proxies are below.

## Usage

Click the file format that you want and copy the URL.

|File|Content|Count|
|----|-------|-----|
|[data.txt](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.txt)|`ip_address:port` combined (seperated new line)|452|
|[data.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data.json)|`ip, port`|452|
|[data-with-geolocation.json](https://raw.githubusercontent.com/mertguvencli/http-proxy-list/main/proxy-list/data-with-geolocation.json)|`ip, port, geolocation`|452|

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
|[proxyscrape.com](https://api.proxyscrape.com/v2/?request=displayproxies&protocol=http&timeout=10000&country=all&ssl=all&anonymity=all)|1371|✅|
|[github.com/clarketm/proxy-list](https://raw.githubusercontent.com/clarketm/proxy-list/master/proxy-list-raw.txt)|400|✅|
|[github.com/monosans/proxy-list](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/http.txt)|564|✅|
|[github.com/TheSpeedX/PROXY-List](https://raw.githubusercontent.com/TheSpeedX/PROXY-List/master/http.txt)|6235|✅|


## Sample Proxies With Geolocation Info

|#|Ip|Port|Country|City|Internet Service Provider|
|-|--|----|-------|----|-------------------------|
|1|185.161.70.117|20000|United States|Los Angeles|DediPath|
|2|158.160.56.149|8080|Russia|Moscow|Yandex.Cloud LLC|
|3|186.121.235.222|8080|Bolivia|La Paz|AXS Bolivia S. A.|
|4|193.233.202.75|8080|United States|Ashburn|Alexhost SRL|
|5|113.53.231.133|3129|Thailand|Ban Pho|TOT Public Company Limited|
|6|209.126.9.54|3128|United States|St Louis|Nubes, LLC|
|7|64.225.8.82|9985|United States|Clifton|DigitalOcean, LLC|
|8|43.130.148.94|80|United States|Ashburn|Shenzhen Tencent Computer Systems Company Limited|
|9|67.225.139.153|3128|United States|Lansing|Liquid Web, L.L.C|
|10|190.2.212.20|999|Colombia|Bogotá|TV AZTECA SUCURSAL COLOMBIA|
|11|37.187.19.49|3128|France|Gravelines|OVH SAS|
|12|20.44.206.138|80|Singapore|Singapore|Microsoft Corporation|
|13|41.76.145.18|443|Mozambique|Maputo|VM  S.A|
|14|109.194.101.128|3128|Russia|Yoshkar-Ola|CJSC "ER-Telecom Holding" Yoshkar-Ola branch|
|15|64.225.4.29|9816|United States|Clifton|DigitalOcean, LLC|
|16|189.201.164.91|999|Mexico|San Luis Potosí City|ATC HOLDING FIBRA MEXICO, S. DE R.L. DE C.V.|
|17|179.61.253.112|3128|Germany|Frankfurt am Main|Collin Schneeweiss|
|18|202.86.138.18|8080|Macao|Macao|Companhia de Telecomunicacoes de Macau|
|19|189.201.164.91|999|Mexico|San Luis Potosí City|ATC HOLDING FIBRA MEXICO, S. DE R.L. DE C.V.|
|20|154.209.253.83|8443|United States|Los Angeles|Shanghai Ruisu Network Technology|



## Contributing

Contributions are welcome, and they are greatly appreciated! Every
little bit helps, and credit will always be given.

