# Embedded Rust

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

This is a list of resources related to embedded and low-level programming in the programming language Rust.

[<img src="https://rawgit.com/berkus/awesome-embedded-rust/master/rust-embedded-logo-256x256.png" align="right" width="256">](http://www.rust-embedded.org)

## Books, blogs and training materials

-   [Discovery](https://japaric.github.io/discovery/) by japaric --- this book is an "introductory course" on microcontroller-based "embedded systems" that uses Rust as the teaching language.
-   [Exploring Rust on Teensy](https://branan.github.io/teensy/) by branan --- Beginner set of articles on getting into embedded dev in Rust.

## Platform core support

#### AVR
-   [AVR Rust](https://github.com/avr-rust/rust) Fork of Rust with AVR support.

#### STM32
-   [Pragmatic Bare Metal Rust](http://www.hashmismatch.net/pragmatic-bare-metal-rust/) A starter article about starting Rust development on STM32 microcontrollers.
-   [Using Rust in an Embedded Project: A Simple Example](https://spin.atomicobject.com/2016/07/08/rust-embedded-project-example/#.V3-os-6qlZw.hackernews) Article and some links on setting up Rust cross-compiling.

#### Nordic semiconductor

#### MSP430

#### Raspberry Pi, etc
-   [Raspberry Pi Bare Metal Programming with Rust](https://medium.com/@thiagopnts/raspberry-pi-bare-metal-programming-with-rust-a6f145e84024) A starter article on OSdev with Rust on RPi (cross-compiler setup and a very basic LED-blinking kernel).

## Peripherial libraries and drivers

## Sheduling/RTOS 
-   [Fearless concurrency](http://blog.japaric.io/fearless-concurrency/) by japaric --- How to easily develop Rust programs for pretty much any ARM Cortex-M microcontroller with memory-safe concurrency.
-   [RTFM v2](http://blog.japaric.io/rtfm-v2/) Real-Time For the Masses --- Cortex-M programming framework.

## Tools
-   [xargo](https://github.com/japaric/xargo) Rust package manager with support for non-default std libraries --- build rust runtime for your own embedded system.
-   [svd2rust](https://github.com/japaric/svd2rust) Generate Rust structs with register mappings from SVD files.
-   [μtest](https://github.com/japaric/utest) unit testing for microcontrollers and other no-std systems.

## Complex projects/frameworks
-   [Robigalia](https://robigalia.org) IoT operating system in Rust running on secure seL4 microkernel.
-   [Tock](https://www.tockos.org) An embedded operating system designed for running multiple concurrent, mutually distrustful applications on low-memory and low-power microcontrollers
-   [intermezzOS](http://intermezzos.github.io) A small teaching operating system in Rust. A book with some explanations also included.

## Community
[embedded.rs](https://t.me/embedded_rs) Telegram channel about Rust, microcontrollers and catgirls [ru]
