на случай блока/разблока в raw.lst убрать/добавить
```
nftset=/cdn-telegram.org/4#inet#fw4#vpn_domains
nftset=/comments.app/4#inet#fw4#vpn_domains
nftset=/contest.com/4#inet#fw4#vpn_domains
nftset=/fragment.com/4#inet#fw4#vpn_domains
nftset=/graph.org/4#inet#fw4#vpn_domains
nftset=/quiz.directory/4#inet#fw4#vpn_domains
nftset=/t.me/4#inet#fw4#vpn_domains
nftset=/tdesktop.com/4#inet#fw4#vpn_domains
nftset=/telega.one/4#inet#fw4#vpn_domains
nftset=/telegra.ph/4#inet#fw4#vpn_domains
nftset=/telegram-cdn.org/4#inet#fw4#vpn_domains
nftset=/telegram.dog/4#inet#fw4#vpn_domains
nftset=/telegram.me/4#inet#fw4#vpn_domains
nftset=/telegram.org/4#inet#fw4#vpn_domains
nftset=/telegram.space/4#inet#fw4#vpn_domains
nftset=/telesco.pe/4#inet#fw4#vpn_domains
nftset=/tg.dev/4#inet#fw4#vpn_domains
nftset=/tx.me/4#inet#fw4#vpn_domains
nftset=/usercontent.dev/4#inet#fw4#vpn_domains
```
после `service getdomains restart`

в `/etc/config/firewall` добавить/убрать:
```
list entry '91.108.4.0/22'
list entry '91.108.8.0/22'
list entry '91.108.16.0/22'
list entry '91.108.12.0/22'
list entry '149.154.160.0/20'
list entry '91.105.192.0/23'
list entry '91.108.20.0/22'
list entry '185.76.151.0/24'
```
после `service firewall restart`
