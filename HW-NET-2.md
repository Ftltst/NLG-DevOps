## 1

ifconfig - linux
ipconfig - win

## 2

Протокол neighbor discovery protocol
Пакет - NDP
Команды - ndp [hostname]

## 3

VLAN
```
TYPE=Ethernet
PROXY_METHOD=none
BROWSER_ONLY=no
BOOTPROTO=none
DEFROUTE=yes
IPV4_FAILURE_FATAL=no
NAME=eth0.200
UUID=04cb4fa6-f820-45c0-b847-df94e9628bc5
DEVICE=eth0.200
ONBOOT=yes
IPADDR=192.168.2.100
NETMASK=255.255.255.0
VLAN=yes
```
ip link

## 4

mode-1, mode-2 и далее до mode-6
1 - В данном режиме сетевые пакеты отправляются “по кругу”, от первого интерфейса к последнему
2 - Один из интерфейсов работает в активном режиме, остальные в ожидающем
3 - балансировка нагрузки через XOR мак-адресов для выбора интерфейса
4 - динамическое объединение одинаковых портов
5 - Адаптивная балансировки нагрузки трафика (входящий трафик на 1, исходящий распределяется)
6 - Адаптивная балансировка нагрузки балансируется и входящий и исходящий трафик

## 5

в \29 - 8
32 подсетей
10.10.10.1\24
10.10.10.2\24
10.10.10.3\24

## 6

От 100.64.0.0 до 100.127.255.255 с маской \26 (учитывая что не более 62 хостов)

## 7
win - arp -a, netsh interface IP delete arpcache, arp -d ipaddr
linux - arp -a, arp -d, arp -d ipaddr
