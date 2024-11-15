# USB HUB Projects

<p align="right">
  <img src="https://www.oshwa.org/wp-content/uploads/2014/03/oshw-logo-100-px.png" />
</p>

USB HUB Board project is an open source project described by following:
* USB 3.0 upstream port,
* four USB 3.0 downstream ports,
* MCU on board for management and telemetry,
* simple host-to-MCU interfaces based on USB VCP/CDC,
* two USB 3.0 HUB devices, first - unmanageable (always enabled) with MCU and second HUB connected behind, second - manageable by the MCU,
* downstream ports with power enabling/disabling,
* downstream ports with overcurrent protection,
* downstream ports with power consumption monitoring,
* main system voltages rails power consumption monitoring.


Repository here contains multiple components like HW, FW, SW, docs.

To prepare the repository:
```
git clone https://github.com/elezbyl/usb-hub.git
cd usb-hub
git submodule update --init
```

# FW
TBD
More details can be found [here](fw/README.md)

# HW
TBD
More details can be found [here](hw/README.md)
