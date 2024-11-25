# USB HUB Board Project

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

USB HUB Board high level diagram is available here:
[High Level](arch/high_level.md)

Repository contains multiple components like ARCH, HW, FW, SW and DOCs.

To prepare the repository:
```
git clone --recurse-submodules https://github.com/elezbyl/usb-hub.git
```
# ARCH
More details can be found [here](arch/README.md)

# HW
More details can be found [here](hw/README.md)

# FW
More details can be found [here](fw/README.md)
