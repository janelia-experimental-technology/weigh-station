- [About](#orgd844015)
- [Setup](#org18b487e)
- [Development](#orgbdf2ca1)

    <!-- This file is generated automatically from .metadata.org -->
    <!-- File edits may be overwritten! -->


<a id="orgd844015"></a>

# About

```markdown
- Name: weigh-station
- Description: Rat City weigh station documentation for the Janelia Gowan Lab.
- Version: 0.1.0
- Release Date: 2022-12-14
- Creation Date: 2022-12-14
- License: BSD-3-Clause
- URL: https://github.com/janelia-experimental-technology/weigh-station
- Author: Peter Polidoro
- Email: peter@polidoro.io
- Copyright: 2022 Howard Hughes Medical Institute
- References:
  - https://github.com/janelia-ros/weigh_station_ros
  - https://github.com/janelia-pypi/loadstar_sensors_interface_python
```


<a id="org18b487e"></a>

# Setup


## Single Board Computer


### Download Operating System Image

<https://github.com/ros-realtime/ros-realtime-rpi4-image/releases>


### Flash Operating System Image onto SD Card

<https://github.com/raspberrypi/rpi-imager>


<a id="orgbdf2ca1"></a>

# Development

1.  Install Guix.

[Install Guix](https://guix.gnu.org/manual/en/html_node/Binary-Installation.html)

1.  Clone repository.

```sh
git clone https://github.com/janelia-experimental-technology/weigh-station
cd weigh-station
```

```sh
make metadata-edits
```

1.  Modify project specific variables.

```sh
make metadata
```