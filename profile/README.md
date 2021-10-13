## 👋 Hello!

Welcome to [Embedded Artistry](https://embeddedartistry.com)'s GitHub repository collection! 

If this is your first time coming across us, take a look at our [Welcome](https://embeddedartistry.com/first-time-here/) page.

## Repository Breakdown

We host a number of repositories, but not all of them are necessarily useful to our visitors - some are forks of repositories we rely on, and others support our development and website infrastructure. 

Here's a breakdown of what we think might be interested for our visitors.

1. [embedded-resources](#embedded-resources)
2. [Document Templates](#document-templates)
3. [Reusable Infrastructure](#reusable-infrastructure)
4. [Standard-like Libraries](#standard-like-libraries)

### embedded-resources

The [embedded-resources](https://github.com/embeddedartistry/embedded-resources) repository contains example code and other resources that are referenced in articles on [our website](https://embeddedartistry.com).

### Document Templates

We like to keep our documentation under revision control and in the same repository as our source code. The [templates](https://github.com/embeddedartistry/templates) repo contains a number of documentation templates that we use on our projects. 

### Standard-like Libraries

We provide a number of "standard-like" libraries that can be used on embedded projects  (primarily targeted at ARM microcontrollers, which is what we work on). These libraries are not necessarily standard conformant; we focus on including a subset of functionality that is useful in microcontroller development. For a more complete and conformant solution, we recommend [picolibc](https://github.com/picolibc/picolibc).

- [libc](https://github.com/embeddedartistry/libc)
- [libcpp](https://github.com/embeddedartistry/libcpp) (llvm libcxx with modifications)
- [libmemory](https://github.com/embeddedartistry/libmemory) - a memory management library for microcontrollers; provides a freelist `malloc` implementation along with sample RTOS wrappers
- [compiler-rt](https://github.com/embeddedartistry/compiler-rt) -  wraps the llvm compiler-rt repository and enables users to use it in meson-based projects.

### Reusable Infrastructure

 - [project-skeleton](https://github.com/embeddedartistry/project-skeleton) - The reusable skeleton we use to start new projects using the Meson build system; comes with out-of-the-box support for a number of tools and ensures every project starts with full CI support
- [meson-buildsystem](https://github.com/embeddedartistry/meson-buildsystem) - Our reusable Meson build system modules
- [cmake-project-skeleton](https://github.com/embeddedartistry/cmake-project-skeleton) - The reusable skeleton we use to start new projects using the CMake build system; comes with out-of-the-box support for a number of tools  and ensures every project starts with full CI support
- [cmake-buildsystem](https://github.com/embeddedartistry/cmake-buildsystem) - Our reusable CMake build system modules
- [cppcheck-rules](https://github.com/embeddedartistry/cppcheck-rules) - A collection of CppCheck rules that we use on our projects
- [vale-styleguide](https://github.com/embeddedartistry/vale-styleguide) - The vale style rules that we use for documentation linting on our projects
- [jenkins-pipeline-lib](https://github.com/embeddedartistry/jenkins-pipeline-lib) - A collection of Jenkins functions that we use across our projects

### Arduino

- [arduino-logger](https://github.com/embeddedartistry/arduino-logger) - A logging framework for Arduino projects
- [arduino-printf](https://github.com/embeddedartistry/arduino-printf) - A `printf()` implementation for Arduino
- [athena-bootloader](https://github.com/embeddedartistry/athena-bootloader) - a bootloader for AVRs that supports firmware updates over Ethernet
- [AthenaEEPROM](https://github.com/embeddedartistry/AthenaEEPROM) - EEPROM management library associated with the [athena-bootloader](https://github.com/embeddedartistry/athena-bootloader) project
- [AthenaEthernetReset](https://github.com/embeddedartistry/AthenaEthernetReset) -  library that will create a server which can be used to remotely reset the device, as well as to remotely enter the [athena-bootloader](https://github.com/embeddedartistry/athena-bootloader) mode so a sketch can be uploaded via TFTP.
- [Meson build definitions for ArduinoCore-avr](https://github.com/embeddedartistry/arduinocore-avr )

## Embedded Virtual Machine

We maintain two additional GitHub organizations for our Embedded Virtual Machine project. This project aims to demonstate techniques that can be used to improve embedded software development.

- [Embedded Virtual Machine](https://github.com/embvm/)
- [Embedded Virtual Machine Drivers](https://github.com/embvm-drivers)

## Contributor Guidelines

We welcome contributions from the community for all of our projects. If you are interested in contributing, please review the following information:

- [Code of Conduct](https://embeddedartistry.com/fieldatlas/embedded-artistry-code-of-conduct/) 
- [Source Code Commit Guidelines](https://embeddedartistry.com/fieldatlas/source-control-commit-guidelines/)
- [Embedded Artistry's GitHub Process](https://embeddedartistry.com/fieldatlas/embedded-artistrys-github-process/)

If you are unfamiliar with open source development, you will want to start with our [Open Source Contribution Guide](https://embeddedartistry.com/fieldatlas/open-source-contribution-guide/).
