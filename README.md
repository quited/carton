# carton

* The purpose of this project is to implement 
some daily-used containers for UWE in cpp cause
arduino platform doesn’t provide any STL support
 and actually STL is much too heavy-weighted for 
embedded platforms

* This project is expected to work on
 embedded devices, such as stm32 and 
perhaps arduino, so our goal is to 
write code with the low memory
 usage(as low as possible), which 
means that sometimes speed 
can be traded off.
 
## Roadmap

### Containers

* [ ] array
* [ ] vector
* [ ] map
* [ ] set
* [ ] buffer

### CI

* [ ] configuration 

## Compiler and cpp standard

* For now the newest version of 
arm-none-eabi toolset is 8 and gcc-avr
 is 9 so we decided to target c++17

## License

MIT
