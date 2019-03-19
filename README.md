# MochimoMiner
Miner for Mochimo coin - Post quantum currency
# MochimoMiner (v1.1 - Mar-2019) (using the latest version is better)
https://github.com/krypdkat/MochimoMiner/releases/tag/1.1
## Linux
### Linux Install dependencies
```
sudo apt-get update
sudo apt-get install libcpprest-dev
```

## Usage:
Just run the executable file, everything will be done automatically.

### Mining with auto-script:
- You should restarts this miner every 2 hours, it makes our miner more stable, avoid duplicate share with other machine.

### Remember to Edit *your wallet address* inside config.txt

## Config example (config.txt & deviceconfig.txt)
### config.txt
```
your_address <required>
pool_URL <required>
pool_URL_1 <optional>
pool_URL_2 <optional>
pool_URL_3 <optional>
```
### deviceconfig.txt (we recommend you should let MochimoMiner generates the config file)
```
number of device
device_id_0 intensity_rate
device_id_1 intensity_rate
device_id_2 intensity_rate
```
## Known performance:
- GTX 1080Ti: 2.4 GH/s (2.6 GH/s for OC cards)
- GTX 1080: ??
- GTX 1070: 1.45 GH/s
- GTX 1070: 1.2 GH/s
- GTX 1060: ??
- GTX 1050: ??
- GTX 970: 0.75 GH/s

## Linux
### Linux Install dependencies

```
sudo apt-get update
sudo apt-get install libcpprest2.8 libcpprest-dev libncurses5-dev libssl-dev unixodbc-dev g++ git
```
If you can not install above libs, copy ***.so** files inside the bundle to this path: **/usr/lib/x86_64-linux-gnu** and **/usr/lib**

# Donation
- ETH: 0x5DD020B1b6e90d49D3350061393a0F555f1BFa0D
