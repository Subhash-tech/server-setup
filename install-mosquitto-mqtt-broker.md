### Objective: Install mosquito client and update config

[Reference download URL](https://mosquitto.org/download)
Visit the above url to get instructions for other OS

```bash

apt-add-repository ppa:mosquitto-dev/mosquitto-ppa
apt-get update
apt-get install mosquitto

systemctl status mosquitto

cp /etc/mosquitto/mosquitto.conf /etc/mosquitto/mosquitto.conf.bkp

# Update config file by adding below rules
listener 1883
allow_anonymous true

systemctl restart mosquitto
```
