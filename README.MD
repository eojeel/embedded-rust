# Rust for raspberry Pi Pico
## Target Selection
[Pico Data Sheet](https://thepihut.com/products/raspberry-pi-pico?src=raspberrypi)
Get the required information from the datasheet.
- RP2040 microcontroller chip designed by Raspberry Pi in the United Kingdom
- Dual-core ARM Cortex M0+ processor, flexible clock running up to 133 MHz
- 264kB of SRAM, and 2MB of onboard Flash memory

[Processor info](https://developer.arm.com/Processors/Cortex-M0-Plus)
- Architecture	
  - Armv6-M
- ISA Support 
  - Thumb or Thumb-2 subset

[Platform Support](https://doc.rust-lang.org/nightly/rustc/platform-support.html)
- thumbv6m-none-eabi
  - Bare ARMv6-M
  
 Run to add the target.
``` rustup target add thumbv6m-none-ebi```

Flash 0x10000000
RAM  0x20000000


### Useful links 
- [pi-hal-repo](https://github.com/rp-rs/rp-hal?tab=readme-ov-file#getting-started)