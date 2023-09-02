# Pi-Star_DV_Dash_LOG_QRZ
Pi-Star DV Dashboard (Based on works by Hans-J. Barthen (DL5DI) and Kim Huebel (DG9VH)). Add Log To QRZ



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


MMMMMWX0Okkkkkkkkkkkkkkxl;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;;lxkkkkkkkkkkkkkkO0XWMMMMM
MMMWKo;'........................................................................................................................................................................................';oKWMMM
MMM0:...',,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,'...:0MMM
MMWx'..,cccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccccc,..'dWMM
MMNo...;cc;''''''''''''''''''''''''''''''''''''''',,,,,,,,,,,,,,,,,'''''''''''''''''''''''''''''''''''''''''''',,,,,,,,,,,,,,,,,,'''''''''''''''''''''''''''''''''''''''''''''''''''''''''''';cc;...oNMM
MMXc...;c:,;lllllllll:'.......,:llllllllc,....':lodddddddddddddddddoc;.......;clllllllllllllllllll:,........':lodddddddddddddddddol:'.........'cllllllll:'.......:llllllllllllllllllllll:'...':c;...cKMM
MM0:..':c:';xOOOOOOOOkc......,oOOOOOOOOOo,...:dOOOOOOOOOOOOOOOOOOOOOOkl'....,dOOOOOOOOOOOOOOOOOOOOkc'......;dOOOOOOOOOOOOOOOOOOOOOOOd:........:kOOOOOOOOx;......,dOOOOOOOOOOOOOOOOOOOOOOk:...':l:'..;0MM
MMO,..':c;..ckOOOOOOOOd,....'oOOOOOOOOOo,...,dOOOOOOOOOOOOOOOOOOOOOOOOkc....;xOOOOOOOOOOOOOOOOOOOOOc'.....,oOOOOOOOOOOOOOOOOOOOOOOOOOd;.......;xOOOOOOOOk:......'oOOOOOOOOOOOOOOOOOOOOOOkc....;c:,..,kMM
MWx'..,cc;..'oOOOOOOOOOl'..'lkOOOOOOOOo,....:kOOOOOOOOOOOOOOOOOOOOOOOOOl'...;xOOOOOOOOOOOOOOOOOOOOOc'.....;xOOOOOOOOOOOOOOOOOOOOOOOOOkc.......;xOOOOOOOOkc......'lOOOOOOOOOOOOOOOOOOOOOOOl'...;cc,..'xWM
MNo...;cc,...,dOOOOOOOOx;.'ckOOOOOOOOo,.....cOOOOOOOOOOkxxxxkOOOOOOOOOOl'...;xOOOOOOOOOOOOOOOOOOOOkc'.....;xOOOOOOOOOOOOkkkOOOOOOOOOOOc.......,dOOOOOOOOOl.......;oooooooooolodxkOOOOOOOOo'...,cc;...oNM
MXc...;cc,....:xOOOOOOOOo,ckOOOOOOOOo,......lOOOOOOOOOx:'''':xOOOOOOOOOl....';clllllllloodxkOOOOOOk:......;xOOOOOOOOOd:;;;;ckOOOOOOOOOl.......,dOOOOOOOOOl'.................;okOOOOOOOOOkc'...':c;...cXM
MK:..':c:'.....ckOOOOOOOkxkOOOOOOOOo,......'oOOOOOOOOOo'....,dOOOOOOOOOc................:xkOOOOOOOd,......;xOOOOOOOOkc.....,dOOOOOOOOOl'......'oOOOOOOOOOo'...............'cxOOOOOOOOOOx:'....':l:'..;0M
MO,..':c:'.....'oOOOOOOOOOOOOOOOOOo,.......'oOOOOOOOOOo'.....;clllllool,...............,dOOOOOOOOkc.......;xOOOOOOOOkc.....,dOOOOOOOOOo'......'oOOOOOOOOOd,..............,okOOOOOOOOOko,.......;l:'..,OM
Wx'..,cc;.......;dOOOOOOOOOOOOOOOo,........,dOOOOOOOOOl'..............................'lkOOOOOOOOd,.......;xOOOOOOOOOl.....'oOOOOOOOOOo'.......lOOOOOOOOOx;............':xOOOOOOOOOOx:'........;cc,..'xW
No...;cc,........:xOOOOOOOOOOOOOo,.........;xOOOOOOOOOl...............................;xOOOOOOOOkc........;xOOOOOOOOOl.....'oOOOOOOOOOd,.......cOOOOOOOOOx;...........,okOOOOOOOOOko,..........,cc;...oN
Xl...;cc,........'lkOOOOOOOOOOOl'..........;xOOOOOOOOOc..............................'oOOOOOOOOOd,........;xOOOOOOOOOl.....'oOOOOOOOOOd,.......ckOOOOOOOOk:..........:dOOOOOOOOOOxc'...........,cc;...cX
K:..':l:'.........,dOOOOOOOOOkl'...........:kOOOOOOOOkc..............................:kOOOOOOOOkl.........;xOOOOOOOOOl'....'lOOOOOOOOOx;.......:kOOOOOOOOkc........'lkOOOOOOOOOOo;.............':c:'..:K
O;..':c:'.........'oOOOOOOOOOd,............ckOOOOOOOOk:.............................,dOOOOOOOOOd;.........,xOOOOOOOOOo'.....lOOOOOOOOOx;.......:xOOOOOOOOOl.......,dOOOOOOOOOOxc'.......''''...':c:'..,O
k'..,cc;..........,dOOOOOOOOOo'............lOOOOOOOOOx:.....:oddooollc;'...........'lOOOOOOOOOkc..........,dOOOOOOOOOo'.....cOOOOOOOOOx;.......;xOOOOOOOOOl'.....'lOOOOOOOOOOkdlllloodddxxxo,...;cc,..'x
d...,cc,..........;xOOOOOOOOOl............'lOOOOOOOOOx:....'oOOOOOOOOOd,...........:xOOOOOOOOOd;..........,dOOOOOOOOOo'.....ckOOOOOOOOk:.......,dOOOOOOOOOo'.....'lOOOOOOOOOOOOOOOOOOOOOOOOk:...,cc;...o
l...;cc,..........:kOOOOOOOOkc............'oOOOOOOOOOOxolcclkOOOOOOOOOd,..........,oOOOOOOOOOOc...........,dOOOOOOOOOo'....'lOOOOOOOOOk:.......,dOOOOOOOOOd,......cOOOOOOOOOOOOOOOOOOOOOOOOOl...,cc;...c
:..':c:'..........ckOOOOOOOOk:............'oOOOOOOOOOOOOOOOOOOOOOOOOOOd,..........ckOOOOOOOOOd;...........,dOOOOOOOkxdllllodkOOOOOOOOOkc.......'oOOOOOOOOOd,......ckOOOOOOOOOOOOOOOOOOOOOkkxc...':l:'..:
,..':l:'..........,loddxxxkkd;.............ckOOOOOOOOOOOOOOOOOOOOOOOOOo,.........;xOOOOOOOOOkc............,dOOOOOOOOOOOOOOOOOOOOOOOOOOkc.......'oOOOOOOOOOx;......:xOOOOOkkxxxdooollcc::;;,'....':l:'..,
'..,cl:;,,,,''''.......'',,,'..............'cxOOOOOOOOOOOOOOOOOOOOOOOOl.........'oOOOOOOOOOOd,............,dOOOOOOOOOOOOOOOOOOOOOOOOOOx;.......'lOOOOOOOOko,......';c::;;;,,''...........'''',,,;:cc,...
'..';:::cccccccc::::;;;;,,,''''..............,:coodxxxkkOOOOOOOOOOOOko,.........ckOOOOOOOOOkc.............'lOOOOOOOOOOOOOOOOOOOOOOOOOd:.........,clcc::;;,'.............''''',,,;;;;;::::ccccccc:::;'..'
d,......'''',,,,;;;;::::ccccccc:::::;;;,,,,,'''..'''',,;;::ccllloolc;'.........,oOOOOOOOOOOd,..............;dOOOOOOOOOOOOOOOOkkxxdol:'...................''',,,,;;;;;::::ccccccc::::;;;;,,,,''''......,o
W0dl::;,,''.............'''',,,,;;;;::::ccccccc:::::;;;,,,,'''''................;clloodddxd;................':oddddoollcc::;;,,''.......'''',,,,,;;;:::::ccccccc::::;;;;,,,,''''.............'',,;;cld0W
MMMWWNXXK00Okxxdoolc::;,,''.............'''',,,,;;;;::::cccccccc::::;;;,,,,,''''........''...............................''',,,,,;;;;::::ccccccc::::;;;;,,,,''''..............',,;::cloodxxkO00KXXNWWMMM
MMMMMMMMMMMMMMMMMMWWWNXXKK0Okxxdoolc::;,,''.............'''',,,,;;;;::::cccccccc::::;;;;,,,,''''........''''',,,;;;;;:::cccccccc::::;;;;,,,,''''..............',,;::cloodxxkO00KXXNWWWMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWWNNXK00Okxxdoolc::;,,''.............'''',,,,;;;;::::cccccccc::::::::cccccccc::::;;;;,,,,''''.............'',,;::cloodxxkO00KXXNWWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNNXKK0Okxxdoolc::;,,''.............'''',,,,;;;;;;;;,,,,''''.............'',,;::cloodxxkO0KKXNNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNNXKK0Okxxddolcc:;,,''..................'',,;:ccloddxxkO0KKXNNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
MMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMWWNXK0OOxdol:;,'....',;:codxkO0KXNWWMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMMM
