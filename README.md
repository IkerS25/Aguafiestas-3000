cd /usr/lib/python3.11
sudo rm EXTERNALLY-MANAGED

sudo apt-get install libatlas-base-dev libportaudio0 libportaudio2 libportaudiocpp0 portaudio19-dev

sudo apt install portaudio19-dev

pip3 install edge_impulse_linux -i https://pypi.python.org/simple

sudo apt install git

git clone https://github.com/edgeimpulse/linux-sdk-python

sudo apt-get install python3-pip

sudo python3 -m pip install edge_impulse_linux -i https://pypi.python.org/simple

sudo python3 -m pip install pyaudio

git clone https://github.com/adafruit/Adafruit_Python_GPIO.git

cd Adafruit_Python_GPIO

sudo python3 setup.py install

pip3 install adafruit-blinka

sudo pip3 install adafruit-circuitpython-ssd1306
