BootStrap: shub
From: willgpaik/centos8_roar:gpu
%setup

%files

%environment

%runscript
    exec python3 "$@"

%post
    dnf -y install netcdf-devel hdf5-devel proj-devel geos-devel
    pip3 install matplotlib pandas sklearn seaborn keras torchsummary netCDF4
    pip3 install shapely pyshp geos
    pip3 install git+https://github.com/matplotlib/basemap.git

