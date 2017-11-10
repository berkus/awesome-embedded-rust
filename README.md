# Embedded Rust

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a list of resources related to embedded and low-level programming in the programming language Rust.

[<img src="https://rawgit.com/berkus/awesome-embedded-rust/master/rust-embedded-logo-256x256.png" align="right" width="256">](http://www.rust-embedded.org)

## Books, blogs and training materials

-   [Discovery](https://japaric.github.io/discovery/) by japaric --- this book is an "introductory course" on microcontroller-based "embedded systems" that uses Rust as the teaching language.
-   [Exploring Rust on Teensy](https://branan.github.io/teensy/) by branan --- Beginner set of articles on getting into embedded dev in Rust.

## Platform core support
-    [cortex-m](https://github.com/japaric/cortex-m) Low level access to Cortex-M processors

#### AVR
-   [AVR Rust](https://github.com/avr-rust/rust) Fork of Rust with AVR support.

#### STM32
-   [Pragmatic Bare Metal Rust](http://www.hashmismatch.net/pragmatic-bare-metal-rust/) A starter article about starting Rust development on STM32 microcontrollers.
-   [Using Rust in an Embedded Project: A Simple Example](https://spin.atomicobject.com/2016/07/08/rust-embedded-project-example/#.V3-os-6qlZw.hackernews) Article and some links on setting up Rust cross-compiling.
-   [stm32f103xx](https://github.com/japaric/stm32f103xx) Peripheral access API for STM32F103XX microcontrollers (generated using svd2rust)
-   [stm32f30x](https://github.com/japaric/stm32f30x) Peripheral access API for STM32F30X microcontrollers (generated using svd2rust)
-   [stm32f100xx](https://github.com/japaric/stm32f100xx) Peripheral access API for STM32F100XX microcontrollers (generated using svd2rust)
-   [blue-pill](https://github.com/japaric/blue-pill) Board Support Crate for Blue Pill (STM32F103C8 board)
-   [F3 BSP](https://github.com/japaric/f3) Board Support Crate for the STM32F3DISCOVERY

#### Nordic semiconductor
-   [nrf51](https://github.com/japaric/nrf51) Peripheral access API for nRF51 microcontrollers (generated using svd2rust)
-   [nrf51822 playground](https://github.com/japaric/nrf51822) A crate to play with the nrf51822 module

#### MSP430
-   [msp430g2553](https://github.com/japaric/msp430g2553) Peripheral access API for MSP430G2553 microcontrollers (generated using svd2rust)
-   [rust on msp](https://github.com/japaric/rust_on_msp) Simple blinking LED example that runs on MSP430.
-   [msp430 quickstart](https://github.com/japaric/msp430-quickstart) some examples for msp430

#### Raspberry Pi, etc
-   [Raspberry Pi Bare Metal Programming with Rust](https://medium.com/@thiagopnts/raspberry-pi-bare-metal-programming-with-rust-a6f145e84024) A starter article on OSdev with Rust on RPi (cross-compiler setup and a very basic LED-blinking kernel).

## Peripherial libraries and drivers
-   [Embedded hal](https://japaric.github.io/embedded-hal/embedded_hal/index.html) A minimal Hardware Abstraction Layer (HAL) for embedded systems (design phase).

## Sheduling/RTOS 
-   [Fearless concurrency](http://blog.japaric.io/fearless-concurrency/) by japaric --- How to easily develop Rust programs for pretty much any ARM Cortex-M microcontroller with memory-safe concurrency.
-   [RTFM v2](http://blog.japaric.io/rtfm-v2/) Real-Time For the Masses --- Cortex-M programming framework.
-   [cortex-m rtfm](https://github.com/japaric/cortex-m-rtfm) RTFM framework for ARM Cortex-M microcontrollers
-   [msp430 rtfm](https://github.com/japaric/msp430-rtfm) RTFM framework for MSP430 MCUs
-   [FreeRTOS.rs](https://github.com/hashmismatch/freertos.rs) Rust interface for the FreeRTOS API

## Tools
-   [xargo](https://github.com/japaric/xargo) Rust package manager with support for non-default std libraries --- build rust runtime for your own embedded system.
-   [svd2rust](https://github.com/japaric/svd2rust) Generate Rust structs with register mappings from SVD files.
-   [μtest](https://github.com/japaric/utest) unit testing for microcontrollers and other no-std systems.
-   [bindgen](https://crates.io/crates/bindgen) Automatically generates Rust FFI bindings to C and C++ libraries.
-   [cortex-m semihosting](https://github.com/japaric/cortex-m-semihosting) Semihosting for ARM Cortex-M processors

## Complex projects/frameworks
-   [Robigalia](https://robigalia.org) IoT operating system in Rust running on secure seL4 microkernel.
-   [Tock](https://www.tockos.org) An embedded operating system designed for running multiple concurrent, mutually distrustful applications on low-memory and low-power microcontrollers
-   [intermezzOS](http://intermezzos.github.io) A small teaching operating system in Rust. A book with some explanations also included.

## Community
[embedded.rs](https://t.me/embedded_rs) Telegram channel about Rust, microcontrollers and catgirls [ru]
