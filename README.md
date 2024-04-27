# lolra_ESP8266_testing
ESP8266 SDK and compile the code for testing, LoRa experiment without LoRa modem / radio chip


Linux is used (ie. ubutnu for Windows, WSL)
tool chain,
```
mkdir esp
cd esp
git clon https://github.com/espressif/ESP8266_RTOS_SDK
git clone https://github.com/cpq/esputil
cd esputil
make
pip install --upgrade pip
sudo /home/xiao/esp/ESP8266_RTOS_SDK/install.sh
. /home/xiao/esp/ESP8266_RTOS_SDK/export.sh
git clone https://github.com/cpq/esputil
cd ~/esp/ESP8266_RTOS_SDK/examples/get-started/hello_world
make menuconfig


```

source code,
```
git clone --recurse-submodules https://github.com/cnlohr/lolra
~/esp/ESP8266_RTOS_SDK/lolra/esp8266/example_125k_raw
make

```

