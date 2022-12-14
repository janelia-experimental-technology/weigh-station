- [About](#orgefb4178)
- [Setup](#org5c413d2)
- [Development](#orgbe39e52)

    <!-- This file is generated automatically from .metadata.org -->
    <!-- File edits may be overwritten! -->


<a id="orgefb4178"></a>

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


<a id="org5c413d2"></a>

# Setup


## Single Board Computer


### Download ros-realtime-rpi4-image

<https://github.com/ros-realtime/ros-realtime-rpi4-image/releases>


<a id="orgbe39e52"></a>

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