## Instalacja systemu UBUNTU 18.04 z wzorca NETIS

 apt-add-repository multiverse
 
 apt install git ansible
 
 ansible-pull -U https://github.com/netispl/wzorzec -i hosts
