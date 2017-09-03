## Alpine Linux Docker image with GNU C library (glibc) and Oracle JDK

### Supported tags and respective Dockerfile links:

* ```3.5-2.25-8u144``` _\([3.5-2.25-8u144/Dockerfile]\)_
[![](https://images.microbadger.com/badges/image/mbe1224/alpine-oraclejdk:3.5-2.25-8u144.svg)](https://microbadger.com/images/mbe1224/alpine-oraclejdk:3.5-2.25-8u144 "")
* ```3.5-2.26-8u144``` _\([3.5-2.26-8u144/Dockerfile]\)_
[![](https://images.microbadger.com/badges/image/mbe1224/alpine-oraclejdk:3.5-2.26-8u144.svg)](https://microbadger.com/images/mbe1224/alpine-oraclejdk:3.5-2.26-8u144 "")
* ```3.6-2.26-8u144```, ```latest``` _\([3.6-2.26-8u144/Dockerfile]\)_
[![](https://images.microbadger.com/badges/image/mbe1224/alpine-oraclejdk:3.6-2.26-8u144.svg)](https://microbadger.com/images/mbe1224/alpine-oraclejdk:3.6-2.26-8u144 "")

#### All tag names follow the naming convention:

```alpine_image_tag``` + '-' + ```glibc_version``` + '-' + ```java_version```

### Usage:

Build the image
```shell
docker build -t mbe1224/alpine-oraclejdk .
```

### About this image:

- Alpine Linux image
- Signed glibc-_version_-r1.apk, glibc-bin-_version_-r1.apk and glibc-i18n-_version_-r1.apk packages
- Oracle Java SE Development Kit (JDK) addded, without MissionControl, VisualVM, JavaFX and JRE
- Oracle Java Cryptography Extension added
- SHA 256 sum checks for all downloads
- JAVA\_HOME environment variable set up

### License:

* [MIT License]
* [Oracle Binary Code License Agreement]

   [3.5-2.25-8u144/Dockerfile]: <https://github.com/MihaiBogdanEugen/alpine-oraclejdk/blob/3.5-2.25-8u144/Dockerfile>
   [3.5-2.26-8u144/Dockerfile]: <https://github.com/MihaiBogdanEugen/alpine-oraclejdk/blob/3.5-2.26-8u144/Dockerfile>
   [3.6-2.26-8u144/Dockerfile]: <https://github.com/MihaiBogdanEugen/alpine-oraclejdk/blob/3.6-2.26-8u144/Dockerfile>
   [MIT License]: <https://raw.githubusercontent.com/MihaiBogdanEugen/alpine-oraclejdk/master/LICENSE>
   [Oracle Binary Code License Agreement]: <https://raw.githubusercontent.com/MihaiBogdanEugen/alpine-oraclejdk/master/Oracle_Binary_Code_License_Agreement%20for%20the%20Java%20SE%20Platform_Products_and_JavaFX>
