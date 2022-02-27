Thanks to an appropriate USD dongle supporting DVB-T signal, you can freely become a Business member of Flightradar24.
This enable new functionalities and avoid advertisement.

1s step is to purchase the DVB-T USB dongle.

Then you can follow the procedure described here: https://pimylifeup.com/raspberry-pi-flightradar24/

(Go directly to "Installing Flightradar24 on Raspbian)

You have to launch the following command:

sudo bash -c "$(wget -O - http://repo.feed.flightradar24.com/install_fr24_rpi.sh)

You will need to:
. create an account on Flightradar
. get your position (Latitude/Longitude)


To start sending data:

$ sudo systemctl restart fr24feed
