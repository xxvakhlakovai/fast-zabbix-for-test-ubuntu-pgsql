# fast-zabbix-for-test-/docker-compose_ubuntu_pgsql_latest
![68747470733a2f2f6173736574732e7a61626269782e636f6d2f696d672f6c6f676f2f7a61626269785f6c6f676f5f353030783133312e706e67](https://user-images.githubusercontent.com/75326855/126627735-cc5d1dae-59be-481d-9dad-978c51047934.png)
!!!Agent deleted
- sudo apt install git
- mkdir /usr/zabbix/
- cd /usr/zabbix/
- git clone https://github.com/xxvakhlakovai/fast-zabbix-for-work.git
- cd /fast-zabbix-for-work
- vim .env_ - we make the necessary settings(if required)
- docker-compose up -d
- docker ps -a
- Zabbix will be available at: http://host_ip/zabbix
