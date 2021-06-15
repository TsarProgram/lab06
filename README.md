[![Build Status](https://travis-ci.com/TsarProgram/lab06.svg?branch=master)](https://travis-ci.com/TsarProgram/lab06)

## Homework. Lab #6

Чтобы собрать код в пaкеты необходимо: 

1. Подключить cpack:
```
 - install(TARGETS hello_world DESTINATION bin)
 - set(CPACK_PACKAGE_NAME "solver")
 - set(CPACK_PACKAGE_VENDOR "Ccccompany")
 - set(CPACK_PACKAGE_CONTACT "https://Leningrad.ru")
 - set(CPACK_DEBIAN_PACKAGE_MAINTAINER "nikita.hrapov@mail.ru")
 - set(CPACK_PACKAGE_DESCRIPTION "Not bad package :3")
 - #set(CPACK_GENERATOR "DragNDrop")
 - #set(CPACK_GENERATOR "DEB")
 - set(CPACK_GENERATOR "RPM" "DEB")
 - include(CPack)
```
2. Продкачать RPM пакет
