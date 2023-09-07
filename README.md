# Ender 3 V2 Klipper Setup

This repository contains all the essential configuration files for running an Ender 3 V2 3D printer with Klipper firmware.

## Table of Contents

- [Installation](#installation)
- [Configuration Files](#configuration-files)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone this repository to your machine.
    ```bash
    git clone https://github.com/Etienneg93/Ender3V2Klipper.git
    ```
2. Follow the Klipper [installation guide](https://klipper3d.org/Installation.html) to set up the printer.

## Configuration Files

Here's a quick rundown of the key files in this repo:

- **macros/**: Directory containing custom macros.
- **.moonraker.conf.bkp**: Backup for Moonraker configuration.
- **KlipperScreen.conf**: KlipperScreen interface configuration.
- **KlipperScreen.conf.save**: Backup for KlipperScreen configuration.
- **LICENSE**: License file.
- **adaptive_mesh.cfg**: Configuration for adaptive mesh bed leveling.
- **fluidd.cfg**: Configuration for the Fluidd interface.
- **moonraker-obico-update.cfg**: Moonraker Obico update configuration.
- **moonraker-obico.cfg**: Moonraker Obico configuration.
- **moonraker.conf**: Moonraker main configuration.
- **old_printer.cfg**: Backup for old printer configuration.
- **park.cfg**: Configuration for parking the print head.
- **pause_park.cfg**: Configuration for pause and parking behavior.
- **picoadxl.cfg**: Configuration for Pico ADXL345 sensor.
- **printer.cfg**: Main Klipper printer configuration.
- **webcam.txt**: Webcam configuration.

## Contributing

If you find any issues or have suggestions for improvements, feel free to create a pull request or open an issue.

## License

This project is licensed under the terms of the [MIT License](LICENSE).
