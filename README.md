# centos7-firewall-conf

Конфигурация файрвола в домашней сети:
- firewall-masq-v1 = то на чем остановился
- firewall-masq-v2 = тоже самое, что firewall-masq-v1, но с закоментированными более простыми правилами (вместо локальных интерфейсов используется диапозон ip)
- firewall-masq-big = начальная попытка сконфигурировать все используя не только интерфейсы/ip, но и порты. Рабочая версия, но слишком много портов нужно прописывать, для домашнего сервера не имеет смысла держать и сопровождать такую большую конфигурацию

# Мануалы

- http://www.k-max.name/linux/netfilter-iptables-v-linux/
- https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers

# Схема маршрутизации

![](https://github.com/orlov0562/centos7-firewall-conf/blob/master/Netfilter-tables.jpg?raw=true)

