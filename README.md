# service_systemd

service_name: blackhole_watcher.service

Te vinden in: /etc/systemd/system/

en daarin wordt dan verwezen naar: /home/kodi/scripts
LET OP: als je deze kloont, let dan wel op dat je /env backupt

sudo systemctl start <service_name>
sudo systemctl stop <service_name>
sudo systemctl restart <service_name>
sudo systemctl status <service_name>
sudo systemctl disable <service_name> Disable a service from starting at boot:

Meer info: https://www.digitalocean.com/community/tutorials/how-to-use-systemctl-to-manage-systemd-services-and-units

Om nieuwe versie te downloaden:

git clone https://github.com/westsurname/scripts.git zie https://github.com/westsurname/scripts voor als je het voor de eerste keer doet ivm requirements.

