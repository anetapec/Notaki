## By polaczyc sie z baza danych Mongodb
```bash
 mongod
 ```
(w innym oknie )
 ```bash
 mongo
 ```
 
 ```bash
 sudo apt-get purge mongodb-org*
sudo apt remove mongodb
sudo apt purge mongodb
sudo apt autoremove
sudo rm -r /var/log/mongodb
sudo rm -r /var/lib/mongodb
sudo apt-get install gnupg
wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list
sudo apt-get update
sudo apt-get upgrade
sudo apt update
sudo apt upgrade
sudo apt-get install -y mongodb-org
sudo apt-get install libc6
sudo service mongod start
sudo service mongod status
```

usuwa Mongodb wczesniejsze

```bash
sudo apt remove --autoremove mongodb-org
```
usuniecie plikow repozytoriow
```bash

 
Ubuntu 18.04 i MongoDB 4.2

Najpierw usuń MongoDB z poprzedniego, jeśli jest zainstalowany:

sudo apt remove --autoremove mongodb-org

Usuń wszystkie pliki listy repozytoriów mongodb:

sudo rm /etc/apt/sources.list.d/mongodb*.list
sudo apt update
```


 
