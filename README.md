# PyWallet

[![Join the chat at https://gitter.im/PyWallet/Lobby](https://badges.gitter.im/PyWallet/Lobby.svg)](https://gitter.im/PyWallet/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://secure.travis-ci.org/paulheider/PyWallet.png?branch=develop)](http://travis-ci.org/paulheider/PyWallet)
[![Coverage Status](https://coveralls.io/repos/github/paulheider/PyWallet/badge.svg?branch=develop)](https://coveralls.io/github/paulheider/PyWallet?branch=develop)

Cross platform Ethereum Wallet built with Python and Kivy.

<img src="https://raw.githubusercontent.com/AndreMiras/PyWallet/develop/docs/images/phone_nexus_6p_overview.png" alt="Screenshot Nexus" width="200"> <img src="https://raw.githubusercontent.com/AndreMiras/PyWallet/develop/docs/images/preview_dell_xps_13.png" alt="Screenshot Dell" width="500">

## Features

  * Show balance
  * Show transaction history
  * Receive Ethers via QR code
  * Send Ethers
  * Handle multiple keystores
  * Manage accounts

## Run

### Linux
```
./src/main.py
```

### Android
Run on Android using buildozer:
```
buildozer android debug deploy run logcat
buildozer android adb -- logcat
```

## Ubuntu dependencies
```
sudo apt install zlib1g-dev default-jdk
```

## Documentation

* Miscellaneous documentation in the [docs](docs/) directory
* Recipes documentation in the [python-for-android](src/python-for-android/) directory
