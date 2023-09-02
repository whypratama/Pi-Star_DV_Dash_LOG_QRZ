# Pi-Star_DV_Dash_LOG_QRZ
Pi-Star DV Dashboard (Based on works by Hans-J. Barthen (DL5DI) and Kim Huebel (DG9VH)). Add Log To QRZ

![f8cb92fa-22db-45b8-a46d-31063f1a6aef](https://github.com/whypratama/Pi-Star_DV_Dash_LOG_QRZ/assets/42627915/2b8023fa-a679-4f36-ac43-ff7ba2496276)


=========================================
SSH ke Raspberry Pi

Login as         : pi-star

password      : raspberry

rpi-rw

sudo chmod 777 /var/www/dashboard/

cd //

cd home

sudo wget -O lh.php https://raw.githubusercontent.com/whypratama/Pi-Star_DV_Dash_LOG_QRZ/d5addd6102f8753d20506cd613f46b22380b75e3/mmdvmhost/lh.php

sudo wget -O pistar-css https://raw.githubusercontent.com/whypratama/Pi-Star_DV_Dash_LOG_QRZ/1eb98e0a8f05d0b3b23242e19b22fd1b2c048956/css/pistar-css.php

sudo cp pistar-css.php /var/www/dashboard/css/

sudo cp lh.php /var/www/dashboard/mmdvmhost/ 

sudo wget -O /var/www/dashboard/user.csv https://radioid.net/static/user.csv

sudo nano /var/www/dashboard/mmdvmhost/lh.php

(ganti QRZ API, Callsign,Frq TX RX dengan milik pribadi)
------------------
