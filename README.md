# Screen locker

## Third Party Code

kcheckpass

## Dependencies

### Debian/Ubuntu

```
sudo dnf in task-develop
sudo dnf install lib64pam-devel x11-server-devel
```

## Build

```shell
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
```

## Install

```shell
sudo make install
```

## License

This project has been licensed by GPLv3.
