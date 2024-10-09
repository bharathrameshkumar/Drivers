
# Device Driver Repository for STM32F1xx

This repository contains device drivers for STM32F1xx microcontrollers, including the [CMSIS (Cortex Microcontroller Software Interface Standard)](https://github.com/STMicroelectronics/cmsis_device_f1) and [HAL (Hardware Abstraction Layer) drivers](https://github.com/STMicroelectronics/stm32f1xx_hal_driver).

## Folder Structure

The repository is organized as follows:

```markdown
STM32F1
│
├── Drivers
│   ├── CMSIS
│   │   ├── Core
│   │   ├── Core_A
│   │   ├── DSP
│   │   ├── Device/ST/STM32F1xx
│   │   ├── Include
│   │   ├── NN
│   │   ├── RTOS/Template
│   │   ├── RTOS2
│   │   └── docs
│   │       ├── ARM.CMSIS.pdsc
│   │       ├── LICENSE.txt
│   │       └── README.md
│   ├── stm32f1xx_hal_driver
│
├── Utilities
│   ├── CPU
│   ├── Fonts
│   ├── Log
│   └── Media
│
├── .gitignore
├── .gitmodules
└── README.md

```

### Description of Main Directories

- **Drivers/CMSIS**: Contains the Cortex Microcontroller Software Interface Standard (CMSIS) files including core, DSP, device-specific drivers, and RTOS templates.
- **Drivers/stm32f1xx_hal_driver**: Contains the Hardware Abstraction Layer (HAL) drivers for STM32F1.
- **Utilities**: Additional utilities, including CPU-related files, fonts, logging mechanisms, and media files.

## Adding this Repository as a Git Submodule

To include this repository in your project as a submodule, follow these steps:

1. Navigate to your project directory:

   ```bash
   cd /path/to/your/project
   ```

2. Add the submodule using the following command, replacing `<repo-url>` with the actual repository URL:

   ```bash
   git submodule add <repo-url> STM32F1
   ```

3. Initialize and update the submodule:

   ```bash
   git submodule update --init --recursive
   ```

4. To pull the latest changes in the submodule, you can run:

   ```bash
   git submodule update --remote
   ```

## License

This repository is licensed under the MIT License. See the LICENSE.txt file for details.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or raise an issue.

## Contact

For any questions or suggestions, please contact [Your Name] at [Your Email].
