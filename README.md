# IoT OpenTherm Project
Project here called 'IoT OpenTherm' is IoT device project to control the furnace using OpenTherm protocol/interface. This device allows to integrate OpenTherm compatible endpoint/slave with IoT infrastructure. Project is inspired with following projects:
* https://ihormelnyk.com/opentherm_thermostat
* https://olegtarasov.me/opentherm-thermostat-esphome
* https://github.com/arthurrump/esphome-opentherm

Repository here contains multiple components like HW, FW, SW, docs.

To prepare the repository:
```
git clone https://github.com/elezbyl/iot-opentherm.git
cd iot-opentherm
git submodule update --init
```

## FW
There are various different IoT FW stack which could be used for IoT OpenTherm project. More details can be found [here](fw/README.md)

## HW
IoT OpenTherm HW Project is based on ESP-12S WiFi module and Ihor's Melnyk adapter design. More details can be found [here](hw/README.md)
