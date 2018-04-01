# Incognito

Copyright (c) 2017-2018 The Incognito Project.   
Portions Copyright (c) 2012-2013 The Cryptonote developers.

## Development resources

- Web: [getincognito.org](https://getincognito.org)
- Forum: [forum.getincognito.org](https://forum.getincognito.org)
- Mail: [dev@getincognito.org](mailto:dev@getincognito.org)
- GitHub: [https://github.com/incognito-currency/incognito](https://github.com/incognito-currency/incognito)
- IRC: [#incognito on Freenode](http://webchat.freenode.net/?randomnick=1&channels=%23incognito&prompt=1&uio=d4)

## Vulnerability response

- Our [Vulnerability Response Process](https://github.com/incognito-currency/meta/blob/master/VULNERABILITY_RESPONSE_PROCESS.md) encourages responsible disclosure
- We are also available via [HackerOne](https://hackerone.com/incognito)

## Build

| Operating System      | Processor | Status |
| --------------------- | -------- |--------|
| Ubuntu 16.04          |  i686    | [![Ubuntu 16.04 i686](https://build.getincognito.org/png?builder=incognito-static-ubuntu-i686)](https://build.getincognito.org/builders/incognito-static-ubuntu-i686)
| Ubuntu 16.04          |  amd64   | [![Ubuntu 16.04 amd64](https://build.getincognito.org/png?builder=incognito-static-ubuntu-amd64)](https://build.getincognito.org/builders/incognito-static-ubuntu-amd64)
| Ubuntu 16.04          |  armv7   | [![Ubuntu 16.04 armv7](https://build.getincognito.org/png?builder=incognito-static-ubuntu-arm7)](https://build.getincognito.org/builders/incognito-static-ubuntu-arm7)
| Debian Stable         |  armv8   | [![Debian armv8](https://build.getincognito.org/png?builder=incognito-static-debian-armv8)](https://build.getincognito.org/builders/incognito-static-debian-armv8)
| OSX 10.10             |  amd64   | [![OSX 10.10 amd64](https://build.getincognito.org/png?builder=incognito-static-osx-10.10)](https://build.getincognito.org/builders/incognito-static-osx-10.10)
| OSX 10.11             |  amd64   | [![OSX 10.11 amd64](https://build.getincognito.org/png?builder=incognito-static-osx-10.11)](https://build.getincognito.org/builders/incognito-static-osx-10.11)
| OSX 10.12             |  amd64   | [![OSX 10.12 amd64](https://build.getincognito.org/png?builder=incognito-static-osx-10.12)](https://build.getincognito.org/builders/incognito-static-osx-10.12)
| FreeBSD 11            |  amd64   | [![FreeBSD 11 amd64](https://build.getincognito.org/png?builder=incognito-static-freebsd64)](https://build.getincognito.org/builders/incognito-static-freebsd64)
| DragonFly BSD 4.6     |  amd64   | [![DragonFly BSD amd64](https://build.getincognito.org/png?builder=incognito-static-dragonflybsd-amd64)](https://build.getincognito.org/builders/incognito-static-dragonflybsd-amd64)
| Windows (MSYS2/MinGW) |  i686    | [![Windows (MSYS2/MinGW) i686](https://build.getincognito.org/png?builder=incognito-static-win32)](https://build.getincognito.org/builders/incognito-static-win32)
| Windows (MSYS2/MinGW) |  amd64   | [![Windows (MSYS2/MinGW) amd64](https://build.getincognito.org/png?builder=incognito-static-win64)](https://build.getincognito.org/builders/incognito-static-win64)

## Coverage

| Type      | Status |
|-----------|--------|
| Coverity  | [![Coverity Status](https://scan.coverity.com/projects/9657/badge.svg)](https://scan.coverity.com/projects/9657/)
| Coveralls | [![Coveralls Status](https://coveralls.io/repos/github/incognito-currency/incognito/badge.svg?branch=master)](https://coveralls.io/github/incognito-currency/incognito?branch=master)
| License   | [![License](https://img.shields.io/badge/license-BSD3-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

## Introduction

Incognito is a private, secure, untraceable, decentralised digital currency. You are your bank, you control your funds, and nobody can trace your transfers unless you allow them to do so.

**Privacy:** Incognito uses a cryptographically sound system to allow you to send and receive funds without your transactions being easily revealed on the blockchain (the ledger of transactions that everyone has). This ensures that your purchases, receipts, and all transfers remain absolutely private by default.

**Security:** Using the power of a distributed peer-to-peer consensus network, every transaction on the network is cryptographically secured. Individual wallets have a 25 word mnemonic seed that is only displayed once, and can be written down to backup the wallet. Wallet files are encrypted with a passphrase to ensure they are useless if stolen.

**Untraceability:** By taking advantage of ring signatures, a special property of a certain type of cryptography, Incognito is able to ensure that transactions are not only untraceable, but have an optional measure of ambiguity that ensures that transactions cannot easily be tied back to an individual user or computer.

## About this project

This is the core implementation of Incognito. It is open source and completely free to use without restrictions, except for those specified in the license agreement below. There are no restrictions on anyone creating an alternative implementation of Incognito that uses the protocol and network in a compatible manner.

As with many development projects, the repository on Github is considered to be the "staging" area for the latest changes. Before changes are merged into that branch on the main repository, they are tested by individual developers in their own branches, submitted as a pull request, and then subsequently tested by contributors who focus on testing and code reviews. That having been said, the repository should be carefully considered before using it in a production environment, unless there is a patch in the repository for a particular show-stopping issue you are experiencing. It is generally a better idea to use a tagged release for stability.

**Anyone is welcome to contribute to Incognito's codebase!** If you have a fix or code change, feel free to submit it as a pull request directly to the "master" branch. In cases where the change is relatively small or does not affect other parts of the codebase it may be merged in immediately by any one of the collaborators. On the other hand, if the change is particularly large or complex, it is expected that it will be discussed at length either well in advance of the pull request being submitted, or even directly on the pull request.

## Supporting the project

Incognito is a 100% community-sponsored endeavor. If you want to join our efforts, the easiest thing you can do is support the project financially. Both Incognito and Bitcoin donations can be made to **donate.getincognito.org** if using a client that supports the [OpenAlias](https://openalias.org) standard. Alternatively you can send XMR to the Incognito donation address via the `donate` command (type `help` in the command-line wallet for details).

The Incognito donation address is: `44AFFq5kSiGBoZ4NMDwYtN18obc8AemS33DBLWs3H7otXft3XjrpDtQGv7SqSsaBYBb98uNbr2VBBEt7f2wfn3RVGQBEP3A` (viewkey: `f359631075708155cc3d92a32b75a7d02a5dcf27756707b47a2b31b21c389501`)

The Bitcoin donation address is: `1KTexdemPdxSBcG55heUuTjDRYqbC5ZL8H`

Core development funding and/or some supporting services are also graciously provided by sponsors:

[<img width="80" src="https://static.getincognito.org/images/sponsors/myincognito.png"/>](https://myincognito.com)
[<img width="150" src="https://static.getincognito.org/images/sponsors/kitware.png?1"/>](http://kitware.com)
[<img width="100" src="https://static.getincognito.org/images/sponsors/dome9.png"/>](http://dome9.com)
[<img width="150" src="https://static.getincognito.org/images/sponsors/araxis.png"/>](http://araxis.com)
[<img width="150" src="https://static.getincognito.org/images/sponsors/jetbrains.png"/>](http://www.jetbrains.com/)
[<img width="150" src="https://static.getincognito.org/images/sponsors/navicat.png"/>](http://www.navicat.com/)
[<img width="150" src="https://static.getincognito.org/images/sponsors/symas.png"/>](http://www.symas.com/)

There are also several mining pools that kindly donate a portion of their fees, [a list of them can be found on our Bitcointalk post](https://bitcointalk.org/index.php?topic=583449.0).

## License

See [LICENSE](LICENSE).

## Contributing

If you want to help out, see [CONTRIBUTING](CONTRIBUTING.md) for a set of guidelines.

## Scheduled mandatory software upgrades

Incognito uses a fixed-schedule mandatory software upgrade (hard fork) mechanism to implement new features. This means that users of Incognito (end users and service providers) need to run current versions and upgrade their software on a regular schedule. Mandatory software upgrades occur during the months of March and September. The required software for these upgrades will be available prior to the scheduled date. Please check the repository prior to this date for the proper Incognito software version. Below is the historical schedule and the projected schedule for the next upgrade.
Dates are provided in the format YYYY-MM-DD. 


| Software upgrade block height | Date       | Fork version | Minimum Incognito version | Recommended Incognito version | Details                                                                            |  
| ------------------------------ | -----------| ----------------- | ---------------------- | -------------------------- | ---------------------------------------------------------------------------------- |
| 1009827                        | 2016-03-22 | v2                | v0.9.4                 | v0.9.4                     | Allow only >= ringsize 3, blocktime = 120 seconds, fee-free blocksize 60 kb       |
| 1141317                        | 2016-09-21 | v3                | v0.9.4                 | v0.10.0                    | Splits coinbase into denominations  |
| 1220516                        | 2017-01-05 | v4                | v0.10.1                | v0.10.2.1                  | Allow normal and RingCT transactions |
| 1288616                        | 2017-04-15 | v5                | v0.10.3.0              | v0.10.3.1                  | Adjusted minimum blocksize and fee algorithm      |
| 1400000                        | 2017-09-16 | v6                | v0.11.0.0              | v0.11.0.0                  | Allow only RingCT transactions, allow only >= ringsize 5      |
| XXXXXXX                        | 2018-03-XX | XX                | XXXXXXXXX              | XXXXXXXXX                  | XXXXXX

X's indicate that these details have not been determined as of commit date, 2017-09-20. 

## Release staging schedule and protocol

Approximately three months prior to a scheduled mandatory software upgrade, a branch from Master will be created with the new release version tag. Pull requests that address bugs should then be made to both Master and the new release branch. Pull requests that require extensive review and testing (generally, optimizations and new features) should *not* be made to the release branch. 

## Installing Incognito from a package

Packages are available for

* Ubuntu and [snap supported](https://snapcraft.io/docs/core/install) systems, via a community contributed build.

    snap install incognito --beta

Installing a snap is very quick. Snaps are secure. They are isolated with all of their dependencies. Snaps also auto update when a new version is released.

* Arch Linux (via [AUR](https://aur.archlinux.org/)):
  - Stable release: [`incognito`](https://aur.archlinux.org/packages/incognito)
  - Bleeding edge: [`incognito-git`](https://aur.archlinux.org/packages/incognito-git)

* Void Linux:

    xbps-install -S incognito

* GuixSD

        guix package -i incognito

* OS X via [Homebrew](http://brew.sh)

        brew tap sammy007/cryptonight
        brew install incognito --build-from-source

* Docker

        # Build using all available cores
        docker build -t incognito .

        # or build using a specific number of cores (reduce RAM requirement)
        docker build --build-arg NPROC=1 -t incognito .
     
        # either run in foreground
        docker run -it -v /incognito/chain:/root/.incognito -v /incognito/wallet:/wallet -p 39001:39001 incognito

        # or in background
        docker run -it -d -v /incognito/chain:/root/.incognito -v /incognito/wallet:/wallet -p 39001:39001 incognito

Packaging for your favorite distribution would be a welcome contribution!

## Compiling Incognito from source

### Dependencies

The following table summarizes the tools and libraries required to build. A
few of the libraries are also included in this repository (marked as
"Vendored"). By default, the build uses the library installed on the system,
and ignores the vendored sources. However, if no library is found installed on
the system, then the vendored source will be built and used. The vendored
sources are also used for statically-linked builds because distribution
packages often include only shared library binaries (`.so`) but not static
library archives (`.a`).

| Dep            | Min. version  | Vendored | Debian/Ubuntu pkg  | Arch pkg       | Optional | Purpose        |
| -------------- | ------------- | ---------| ------------------ | -------------- | -------- | -------------- |
| GCC            | 4.7.3         | NO       | `build-essential`  | `base-devel`   | NO       |                |
| CMake          | 3.0.0         | NO       | `cmake`            | `cmake`        | NO       |                |
| pkg-config     | any           | NO       | `pkg-config`       | `base-devel`   | NO       |                |
| Boost          | 1.58          | NO       | `libboost-all-dev` | `boost`        | NO       | C++ libraries  |
| OpenSSL        | basically any | NO       | `libssl-dev`       | `openssl`      | NO       | sha256 sum     |
| libzmq         | 3.0.0         | NO       | `libzmq3-dev`      | `zeromq`       | NO       | ZeroMQ library |
| libunbound     | 1.4.16        | YES      | `libunbound-dev`   | `unbound`      | NO       | DNS resolver   |
| libsodium      | ?             | NO       | `libsodium-dev`    | ?              | NO       | libsodium      |
| libminiupnpc   | 2.0           | YES      | `libminiupnpc-dev` | `miniupnpc`    | YES      | NAT punching   |
| libunwind      | any           | NO       | `libunwind8-dev`   | `libunwind`    | YES      | Stack traces   |
| liblzma        | any           | NO       | `liblzma-dev`      | `xz`           | YES      | For libunwind  |
| libreadline    | 6.3.0         | NO       | `libreadline6-dev` | `readline`     | YES      | Input editing  |
| ldns           | 1.6.17        | NO       | `libldns-dev`      | `ldns`         | YES      | SSL toolkit    |
| expat          | 1.1           | NO       | `libexpat1-dev`    | `expat`        | YES      | XML parsing    |
| GTest          | 1.5           | YES      | `libgtest-dev`^    | `gtest`        | YES      | Test suite     |
| Doxygen        | any           | NO       | `doxygen`          | `doxygen`      | YES      | Documentation  |
| Graphviz       | any           | NO       | `graphviz`         | `graphviz`     | YES      | Documentation  |


[^] On Debian/Ubuntu `libgtest-dev` only includes sources and headers. You must
build the library binary manually. This can be done with the following command ```sudo apt-get install libgtest-dev && cd /usr/src/gtest && sudo cmake . && sudo make && sudo mv libg* /usr/lib/ ```

### Build instructions

Incognito uses the CMake build system and a top-level [Makefile](Makefile) that
invokes cmake commands as needed.

#### On Linux and OS X

* Install the dependencies
* Change to the root of the source code directory and build:

        cd incognito
        make

    *Optional*: If your machine has several cores and enough memory, enable
    parallel build by running `make -j<number of threads>` instead of `make`. For
    this to be worthwhile, the machine should have one core and about 2GB of RAM
    available per thread.

    *Note*: If cmake can not find zmq.hpp file on OS X, installing `zmq.hpp` from
    https://github.com/zeromq/cppzmq to `/usr/local/include` should fix that error.

* The resulting executables can be found in `build/release/bin`

* Add `PATH="$PATH:$HOME/incognito/build/release/bin"` to `.profile`

* Run Incognito with `incognitod --detach`

* **Optional**: build and run the test suite to verify the binaries:

        make release-test

    *NOTE*: `core_tests` test may take a few hours to complete.

* **Optional**: to build binaries suitable for debugging:

         make debug

* **Optional**: to build statically-linked binaries:

         make release-static

* **Optional**: build documentation in `doc/html` (omit `HAVE_DOT=YES` if `graphviz` is not installed):

        HAVE_DOT=YES doxygen Doxyfile

#### On the Raspberry Pi

Tested on a Raspberry Pi Zero with a clean install of minimal Raspbian Stretch (2017-09-07 or later) from https://www.raspberrypi.org/downloads/raspbian/. If you are using Raspian Jessie, [please see note in the following section](#note-for-raspbian-jessie-users). 

* `apt-get update && apt-get upgrade` to install all of the latest software

* Install the dependencies for Incognito from the 'Debian' column in the table above.

* Increase the system swap size:
```	
	sudo /etc/init.d/dphys-swapfile stop  
	sudo nano /etc/dphys-swapfile  
	CONF_SWAPSIZE=1024  
	sudo /etc/init.d/dphys-swapfile start  
```
* Clone incognito and checkout most recent release version:
```
        git clone https://github.com/incognito-currency/incognito.git
	cd incognito
	git checkout tags/v0.11.0.0
```
* Build:
```
        make release
```
* Wait 4-6 hours

* The resulting executables can be found in `build/release/bin`

* Add `PATH="$PATH:$HOME/incognito/build/release/bin"` to `.profile`

* Run Incognito with `incognitod --detach`

* You may wish to reduce the size of the swap file after the build has finished, and delete the boost directory from your home directory

#### *Note for Raspbian Jessie users:*

If you are using the older Raspbian Jessie image, compiling Incognito is a bit more complicated. The version of Boost available in the Debian Jessie repositories is too old to use with Incognito, and thus you must compile a newer version yourself. The following explains the extra steps, and has been tested on a Raspberry Pi 2 with a clean install of minimal Raspbian Jessie.

* As before, `apt-get update && apt-get upgrade` to install all of the latest software, and increase the system swap size

```	
	sudo /etc/init.d/dphys-swapfile stop  
	sudo nano /etc/dphys-swapfile  
	CONF_SWAPSIZE=1024  
	sudo /etc/init.d/dphys-swapfile start  
```

* Then, install the dependencies for Incognito except `libunwind` and `libboost-all-dev`

* Install the latest version of boost (this may first require invoking `apt-get remove --purge libboost*` to remove a previous version if you're not using a clean install):
```
	cd  
	wget https://sourceforge.net/projects/boost/files/boost/1.64.0/boost_1_64_0.tar.bz2  
	tar xvfo boost_1_64_0.tar.bz2  
	cd boost_1_64_0  
	./bootstrap.sh  
	sudo ./b2  
```
* Wait ~8 hours
```
	sudo ./bjam install
```
* Wait ~4 hours

* From here, follow the [general Raspberry Pi instructions](#on-the-raspberry-pi) from the "Clone incognito and checkout most recent release version" step.

#### On Windows:

Binaries for Windows are built on Windows using the MinGW toolchain within
[MSYS2 environment](http://msys2.github.io). The MSYS2 environment emulates a
POSIX system. The toolchain runs within the environment and *cross-compiles*
binaries that can run outside of the environment as a regular Windows
application.

**Preparing the build environment**

* Download and install the [MSYS2 installer](http://msys2.github.io), either the 64-bit or the 32-bit package, depending on your system.
* Open the MSYS shell via the `MSYS2 Shell` shortcut
* Update packages using pacman:  

        pacman -Syuu  

* Exit the MSYS shell using Alt+F4  
* Edit the properties for the `MSYS2 Shell` shortcut changing "msys2_shell.bat" to "msys2_shell.cmd -mingw64" for 64-bit builds or "msys2_shell.cmd -mingw32" for 32-bit builds
* Restart MSYS shell via modified shortcut and update packages again using pacman:  

        pacman -Syuu  


* Install dependencies:

    To build for 64-bit Windows:

        pacman -S mingw-w64-x86_64-toolchain make mingw-w64-x86_64-cmake mingw-w64-x86_64-boost mingw-w64-x86_64-openssl mingw-w64-x86_64-zeromq mingw-w64-x86_64-libsodium

    To build for 32-bit Windows:
 
        pacman -S mingw-w64-i686-toolchain make mingw-w64-i686-cmake mingw-w64-i686-boost mingw-w64-i686-openssl mingw-w64-i686-zeromq mingw-w64-i686-libsodium

* Open the MingW shell via `MinGW-w64-Win64 Shell` shortcut on 64-bit Windows
  or `MinGW-w64-Win64 Shell` shortcut on 32-bit Windows. Note that if you are
  running 64-bit Windows, you will have both 64-bit and 32-bit MinGW shells.

**Building**

* If you are on a 64-bit system, run:

        make release-static-win64

* If you are on a 32-bit system, run:

        make release-static-win32

* The resulting executables can be found in `build/release/bin`

### On FreeBSD:

The project can be built from scratch by following instructions for Linux above. If you are running incognito in a jail you need to add the flag: `allow.sysvipc=1` to your jail configuration, otherwise lmdb will throw the error message: `Failed to open lmdb environment: Function not implemented`.

We expect to add Incognito into the ports tree in the near future, which will aid in managing installations using ports or packages.

### On OpenBSD:

#### OpenBSD < 6.2

This has been tested on OpenBSD 5.8.

You will need to add a few packages to your system. `pkg_add db cmake gcc gcc-libs g++ miniupnpc gtest`.

The doxygen and graphviz packages are optional and require the xbase set.

The Boost package has a bug that will prevent librpc.a from building correctly. In order to fix this, you will have to Build boost yourself from scratch. Follow the directions here (under "Building Boost"):
https://github.com/bitcoin/bitcoin/blob/master/doc/build-openbsd.md

You will have to add the serialization, date_time, and regex modules to Boost when building as they are needed by Incognito.

To build: `env CC=egcc CXX=eg++ CPP=ecpp DEVELOPER_LOCAL_TOOLS=1 BOOST_ROOT=/path/to/the/boost/you/built make release-static-64`

#### OpenBSD >= 6.2

You will need to add a few packages to your system. Choose version 4 for db. `pkg_add db cmake miniupnpc zeromq`.

The doxygen and graphviz packages are optional and require the xbase set.


Build the Boost library using clang. This guide is derived from: https://github.com/bitcoin/bitcoin/blob/master/doc/build-openbsd.md

We assume you are compiling with a non-root user and you have `doas` enabled.

Note: do not use the boost package provided by OpenBSD, as we are installing boost to `/usr/local`.

```
# Create boost building directory
mkdir ~/boost
cd ~/boost

# Fetch boost source
ftp -o boost_1_64_0.tar.bz2 https://netcologne.dl.sourceforge.net/project/boost/boost/1.64.0/boost_1_64_0.tar.bz2 

# MUST output: (SHA256) boost_1_64_0.tar.bz2: OK
echo "7bcc5caace97baa948931d712ea5f37038dbb1c5d89b43ad4def4ed7cb683332 boost_1_64_0.tar.bz2" | sha256 -c
tar xfj boost_1_64_0.tar.bz2

# Fetch a boost patch, required for OpenBSD
ftp -o boost.patch https://raw.githubusercontent.com/openbsd/ports/bee9e6df517077a7269ff0dfd57995f5c6a10379/devel/boost/patches/patch-boost_test_impl_execution_monitor_ipp
cd boost_1_64_0
patch -p0 < ../boost.patch

# Start building boost
echo 'using clang : : c++ : <cxxflags>"-fvisibility=hidden -fPIC" <linkflags>"" <archiver>"ar" <striper>"strip"  <ranlib>"ranlib" <rc>"" : ;' > user-config.jam
./bootstrap.sh --without-icu --with-libraries=chrono,filesystem,program_options,system,thread,test,date_time,regex,serialization --with-toolset=clang
./b2 toolset=clang cxxflags="-stdlib=libc++" linkflags="-stdlib=libc++"
doas ./b2 -d0 runtime-link=shared threadapi=pthread threading=multi link=static variant=release --layout=tagged --build-type=complete --user-config=user-config.jam -sNO_BZIP2=1 --prefix=/usr/local install
```

Build cppzmq

Build the cppzmq bindings.

We assume you are compiling with a non-root user and you have `doas` enabled.

```
# Create a library link so cmake is able to find it
doas ln -s /usr/local/lib/libzmq.so.4.1 /usr/local/lib/libzmq.so

# Create cppzmq building directory
mkdir ~/cppzmq
cd ~/cppzmq

# Fetch cppzmq source
ftp -o cppzmq-4.2.2.tar.gz https://github.com/zeromq/cppzmq/archive/v4.2.2.tar.gz

# MUST output: (SHA256) cppzmq-4.2.2.tar.gz: OK
echo "3ef50070ac5877c06c6bb25091028465020e181bbfd08f110294ed6bc419737d cppzmq-4.2.2.tar.gz" | sha256 -c
tar xfz cppzmq-4.2.2.tar.gz

# Start building cppzmq
cd cppzmq-4.2.2
mkdir build
cd build
cmake ..
doas make install
```

Build incognito: `env DEVELOPER_LOCAL_TOOLS=1 BOOST_ROOT=/usr/local make release-static`

### On Solaris:

The default Solaris linker can't be used, you have to install GNU ld, then run cmake manually with the path to your copy of GNU ld:

        mkdir -p build/release
        cd build/release
        cmake -DCMAKE_LINKER=/path/to/ld -D CMAKE_BUILD_TYPE=Release ../..
        cd ../..

Then you can run make as usual.

### On Linux for Android (using docker):

        # Build image (select android64.Dockerfile for aarch64)
        cd utils/build_scripts/ && docker build -f android32.Dockerfile -t incognito-android .
        # Create container
        docker create -it --name incognito-android incognito-android bash
        # Get binaries
        docker cp incognito-android:/opt/android/incognito/build/release/bin .

### Building portable statically linked binaries

By default, in either dynamically or statically linked builds, binaries target the specific host processor on which the build happens and are not portable to other processors. Portable binaries can be built using the following targets:

* ```make release-static-linux-x86_64``` builds binaries on Linux on x86_64 portable across POSIX systems on x86_64 processors
* ```make release-static-linux-i686``` builds binaries on Linux on x86_64 or i686 portable across POSIX systems on i686 processors
* ```make release-static-linux-armv8``` builds binaries on Linux portable across POSIX systems on armv8 processors
* ```make release-static-linux-armv7``` builds binaries on Linux portable across POSIX systems on armv7 processors
* ```make release-static-linux-armv6``` builds binaries on Linux portable across POSIX systems on armv6 processors
* ```make release-static-win64``` builds binaries on 64-bit Windows portable across 64-bit Windows systems
* ```make release-static-win32``` builds binaries on 64-bit or 32-bit Windows portable across 32-bit Windows systems

## Running incognitod

The build places the binary in `bin/` sub-directory within the build directory
from which cmake was invoked (repository root by default). To run in
foreground:

    ./bin/incognitod

To list all available options, run `./bin/incognitod --help`.  Options can be
specified either on the command line or in a configuration file passed by the
`--config-file` argument.  To specify an option in the configuration file, add
a line with the syntax `argumentname=value`, where `argumentname` is the name
of the argument without the leading dashes, for example `log-level=1`.

To run in background:

    ./bin/incognitod --log-file incognitod.log --detach

To run as a systemd service, copy
[incognitod.service](utils/systemd/incognitod.service) to `/etc/systemd/system/` and
[incognitod.conf](utils/conf/incognitod.conf) to `/etc/`. The [example
service](utils/systemd/incognitod.service) assumes that the user `incognito` exists
and its home is the data directory specified in the [example
config](utils/conf/incognitod.conf).

If you're on Mac, you may need to add the `--max-concurrency 1` option to
incognito-wallet-cli, and possibly incognitod, if you get crashes refreshing.

## Internationalization

See [README.i18n.md](README.i18n.md).

## Using Tor

While Incognito isn't made to integrate with Tor, it can be used wrapped with torsocks, if you add --p2p-bind-ip 127.0.0.1 to the incognitod command line. You also want to set DNS requests to go over TCP, so they'll be routed through Tor, by setting DNS_PUBLIC=tcp or use a particular DNS server with DNS_PUBLIC=tcp://a.b.c.d (default is 8.8.4.4, which is Google DNS). You may also disable IGD (UPnP port forwarding negotiation), which is pointless with Tor. To allow local connections from the wallet, you might have to add TORSOCKS_ALLOW_INBOUND=1, some OSes need it and some don't. Example:

`DNS_PUBLIC=tcp torsocks incognitod --p2p-bind-ip 127.0.0.1 --no-igd`

or:

`DNS_PUBLIC=tcp TORSOCKS_ALLOW_INBOUND=1 torsocks incognitod --p2p-bind-ip 127.0.0.1 --no-igd`

TAILS ships with a very restrictive set of firewall rules. Therefore, you need to add a rule to allow this connection too, in addition to telling torsocks to allow inbound connections. Full example:

`sudo iptables -I OUTPUT 2 -p tcp -d 127.0.0.1 -m tcp --dport 39002 -j ACCEPT`

`DNS_PUBLIC=tcp torsocks ./incognitod --p2p-bind-ip 127.0.0.1 --no-igd --rpc-bind-ip 127.0.0.1 --data-dir /home/amnesia/Persistent/your/directory/to/the/blockchain`

`./incognito-wallet-cli`

## Debugging

This section contains general instructions for debugging failed installs or problems encountered with Incognito. First ensure you are running the latest version built from the Github repo.

### Obtaining stack traces and core dumps on Unix systems

We generally use the tool `gdb` (GNU debugger) to provide stack trace functionality, and `ulimit` to provide core dumps in builds which crash or segfault.

* To use gdb in order to obtain a stack trace for a build that has stalled:

Run the build.

Once it stalls, enter the following command:

```
gdb /path/to/incognitod `pidof incognitod` 
```

Type `thread apply all bt` within gdb in order to obtain the stack trace

* If however the core dumps or segfaults:

Enter `ulimit -c unlimited` on the command line to enable unlimited filesizes for core dumps

Enter `echo core | sudo tee /proc/sys/kernel/core_pattern` to stop cores from being hijacked by other tools

Run the build.

When it terminates with an output along the lines of "Segmentation fault (core dumped)", there should be a core dump file in the same directory as incognitod. It may be named just `core`, or `core.xxxx` with numbers appended.

You can now analyse this core dump with `gdb` as follows:

`gdb /path/to/incognitod /path/to/dumpfile`

Print the stack trace with `bt`

* To run incognito within gdb:

Type `gdb /path/to/incognitod`

Pass command-line options with `--args` followed by the relevant arguments

Type `run` to run incognitod

### Analysing memory corruption

We use the tool `valgrind` for this.

Run with `valgrind /path/to/incognitod`. It will be slow.

### LMDB

Instructions for debugging suspected blockchain corruption as per @HYC

There is an `mdb_stat` command in the LMDB source that can print statistics about the database but it's not routinely built. This can be built with the following command:

`cd ~/incognito/external/db_drivers/liblmdb && make`

The output of `mdb_stat -ea <path to blockchain dir>` will indicate inconsistencies in the blocks, block_heights and block_info table.

The output of `mdb_dump -s blocks <path to blockchain dir>` and `mdb_dump -s block_info <path to blockchain dir>` is useful for indicating whether blocks and block_info contain the same keys.

These records are dumped as hex data, where the first line is the key and the second line is the data.
