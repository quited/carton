# carton
> Well, if you want your cross-platform 
project to work on arduino ,that will 
 be pain in ass.

* The purpose of this project is to implement 
some daily-used containers for UWE in cpp cause
arduino platform doesn’t provide any STL support
 and STL indeed is much too heavy-weighted for 
embedded platforms.

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

### Circle CI

* [ ] configuration 

## Compiler and cpp standard

* For now the newest version of 
arm-none-eabi toolset is 8 and gcc-avr
 is 9 so we decided to target c++14.

## Code Style 

We follow [google’s cpp
 style guidelines](https://google.github.io/styleguide/cppguide.html)

## License

MIT
