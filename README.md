
## Informacje
Playbook do instalacji systemu Ubuntu 20/22 z wzorca przygotowanego przez NETIS
Playbook usunie wszytskie partycje z dysku oraz utworzy nowe.
Istnieje możliwość wyboru dysku do instalacji (jeżeli jest więcej niż jeden dysk) oraz sposobu instalacji (z UEFI lub bez).

## Wymagania
Komputer musi być właczony z systemu LIVE **Ubuntu 64 bit**
Do uruchomienie playbooka wymagane są pakiery git oraz ansible
 ```
 sudo apt-add-repository multiverse 
 sudo apt-add-repository --yes ppa:ansible/ansible
 sudo apt-get install --yes git ansible
```

## Instalacja
Uruchomienie playbooka:
```
 sudo ansible-pull -U https://github.com/netispl/wzorzec -i hosts
```
