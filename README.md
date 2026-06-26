# apcupsd ntfy scripts

This repository contains scripts designed to replace the out-of-the-box
notification apcupsd scripts with scripts that alert to a ntfy push
notification service.

## Dependencies

curl

## Installation

Checkout the repo

```sh
git clone https://github.com/seankibler/apcupsd-ntfy.git
```

Modify the NTFY_TOPIC in each file with your favorite editor

Install to apcupsd directory
```sh
sudo cp onbattery offbattery changeme /etc/apcupsd/
```
