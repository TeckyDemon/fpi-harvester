# FPI-Harvester

![Made with Python](https://img.shields.io/badge/made%20with-python-0.svg?color=cc2020&labelColor=ff3030&logo=python&logoColor=white&style=for-the-badge)

![GitHub](https://img.shields.io/github/license/DeBos99/fpi-harvester.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub followers](https://img.shields.io/github/followers/DeBos99.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/DeBos99/fpi-harvester.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/DeBos99/fpi-harvester.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub watchers](https://img.shields.io/github/watchers/DeBos99/fpi-harvester.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/DeBos99/fpi-harvester.svg?color=2020cc&labelColor=5050ff&style=for-the-badge)

![GitHub commit activity](https://img.shields.io/github/commit-activity/w/DeBos99/fpi-harvester.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/DeBos99/fpi-harvester.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/DeBos99/fpi-harvester.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/DeBos99/fpi-harvester.svg?color=ffaa00&labelColor=ffaa30&style=for-the-badge)

![GitHub issues](https://img.shields.io/github/issues-raw/DeBos99/fpi-harvester.svg?color=cc2020&labelColor=ff3030&style=for-the-badge)
![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/DeBos99/fpi-harvester.svg?color=10aa10&labelColor=30ff30&style=for-the-badge)

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=NH8JV53DSVDMY)

**FPI-Harvester** is bot for harvesting emails from [forum.pasja-informatyki.pl](https://forum.pasja-informatyki.pl/) website.

## Content

- [Content](#content)
- [Features](#features)
- [Installation](#installation)
  - [Windows](#windows)
  - [Unix](#unix)
    - [Debian/Ubuntu](#apt)
    - [Arch Linux/Manjaro](#pacman)
    - [CentOS](#yum)
    - [MacOS](#homebrew)
- [Usage](#usage)
- [Documentation](#documentation)
  - [Optional arguments](#optional-arguments)
- [Disclaimer](#disclaimer)
- [Authors](#authors)
- [Contact](#contact)
- [License](#license)

## Features

* Multi-threaded.
* IP rotation.
* 3 modes of verbosity.

## Installation

### Windows

* Install [Git](https://git-scm.com/download/win).
* Install [Python](https://www.python.org/downloads/).
* Run following command in the command prompt:
```
git clone "https://github.com/DeBos99/fpi-harvester.git"
```

### Unix

#### <a name="APT">Debian/Ubuntu based

* Run following commands in the terminal:
```
sudo apt install git python -y
git clone "https://github.com/DeBos99/fpi-harvester.git"
```

#### <a name="Pacman">Arch Linux/Manjaro

* Run following commands in the terminal:
```
sudo pacman -S git python --noconfirm
git clone "https://github.com/DeBos99/fpi-harvester.git"
```

#### <a name="YUM">CentOS

* Run following commands in the terminal:
```
sudo yum install git python -y
git clone "https://github.com/DeBos99/fpi-harvester.git"
```

#### <a name="Homebrew">MacOS

* Run following commands in the terminal:
```
brew install git python
git clone "https://github.com/DeBos99/fpi-harvester.git"
```

## Usage

`python main.py ARGUMENTS`

## Documentation

### Optional arguments

| Argument                  | Description                                             | Default value               |
| :------------------------ | :------------------------------------------------------ | :-------------------------- |
| -h<br>--help              | Shows help message.                                     |                             |
| -t T<br>--threads T       | Sets the number of threads to **T**.                    | 15                          |
| -p PATH<br>--proxies PATH | Sets the path to the list with the proxies to **PATH**. | Proxies list from internet. |
| -o PATH<br>--output PATH  | Sets the path of the output file to **PATH**.           | data.txt                    |
| -v<br>--verbose           | Enables verbose mode.                                   | False.                      |
| -d<br>--debug             | Enabled debug mode.                                     | False.                      |

## Disclaimer

**FPI-Harvester** was created for educational purposes and I'm not taking responsibility for any of your actions.

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos99](https://github.com/DeBos99)

## Contact

Discord: DeBos#3292

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
