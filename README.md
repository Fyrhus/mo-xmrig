## Fork info

This fork contains minor changes that allow `pause-on-active` to work on Linux. Requires X11. To build XMRig from this you must also have headers for X11 and XScreenSaver (to get them on Ubuntu, execute `sudo apt-get install libx11-dev libxss-dev`).

# XMRig

XMRig is a high performance, open source, cross platform RandomX, KawPow, CryptoNight and AstroBWT unified CPU/GPU miner and [RandomX benchmark](https://xmrig.com/benchmark). Official binaries are available for Windows, Linux, macOS and FreeBSD.

## Mining backends
- **CPU** (x64/ARMv8)
- **OpenCL** for AMD GPUs.
- **CUDA** for NVIDIA GPUs via external [CUDA plugin](https://github.com/MoneroOcean/xmrig-cuda).

## Download
* **[Binary releases](https://github.com/MoneroOcean/xmrig/releases)** (MoneroOcean's XMRig without `pause-on-active` fix)
* **[Build from source](https://xmrig.com/docs/miner/build)** (Do not forget additional headers for X11 and XScreenSaver)

## Usage
The preferred way to configure the miner is the [JSON config file](https://xmrig.com/docs/miner/config) as it is more flexible and human friendly. The [command line interface](https://xmrig.com/docs/miner/command-line-options) does not cover all features, such as mining profiles for different algorithms. Important options can be changed during runtime without miner restart by editing the config file or executing [API](https://xmrig.com/docs/miner/api) calls.

* **[Wizard](https://xmrig.com/wizard)** helps you create initial configuration for the miner.
* **[Workers](http://workers.xmrig.info)** helps manage your miners via HTTP API.

## Donations
* Default donation 1% (1 minute in 100 minutes) can be increased via option `donate-level` or disabled in source code. Disabled by default in MoneroOcean's fork of XMRig
* XMR: `48edfHu7V9Z84YzzMa6fUueoELZ9ZRXq9VetWzYGzKt52XU5xvqgzYnDK9URnRoJMk1j8nLwEVsaSWJ4fhdUyZijBGUicoD`

## Developers
* **[xmrig](https://github.com/xmrig)**
* **[sech1](https://github.com/SChernykh)**

## Contacts
* support@xmrig.com (won't help you with this fork)
* [reddit](https://www.reddit.com/user/XMRig/)
* [twitter](https://twitter.com/xmrig_dev)
