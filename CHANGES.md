Changes
=======

## 2022-05-03

- Upgrade GEOS to 3.10.2.
- Remove all builds other than arm64 linux.

## 2021-10-04

- Upgrade GEOS to 3.9.1 in Windows builds.

## 2021-08-24

- Upgrade multibuild commit to 12a0172. 
- Add aarch64 linux builds for Pythons 3.8 and 3.9.

## 2021-03-03

- Upgrade GEOS to 3.9.1.

## 2021-02-01

- Upgrade multibuild commit to 4d1d9ea.

## 2020-12-14

- Add Python 3.9 builds.

## 2020-08-21

* Auditwheel 3.1.0 breaks shapely, so we have customized build_wheel_cmd to
  ensure that we are using auditwheel 3.0.0 (#5).

## 2020-00-00

* Move Windows AppVeyor build from Shapely to here.

## 2020-02-29

* Compile GEOS with -g -O2 flags.

## 2019-01-27

* Update multibuild commit to 6b0ddb5.

## 2019-01-12

* Update GEOS to version 3.8.0.

## 2019-12-08

* Remove Python 3.4 builds.

## 2019-12-07

* Add 64-bit manylinux1 and macosx Python 3.8 builds.
* Update multibuild commit to 4491026 for Python 3.8 support.

## 1.0.0 (soon)

* Multibuild commit is 548ebc8
* GEOS version 3.6.2
* Cython 0.28.3
* Minimum MacOS version is 10.9
* Supports Python 2.7, 3.5. 3.6, and 3.7 on 64-bit Linux
* Supports Python 2.7, 3.4, 3.5, 3.6, and 3.7 on OSX (Xcode 9.4)

