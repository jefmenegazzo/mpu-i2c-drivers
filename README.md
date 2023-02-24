<div align="center">

<a href="https://github.com/jefmenegazzo/mpu-i2c-drivers">
<img
src="https://raw.githubusercontent.com/jefmenegazzo/mpu-i2c-drivers/master/img/mpujpg.jpg"
alt="MPU"
height="150"
align="center"
/>
</a>



<div>
<br />

🙌 Use [sponsors and donations](#Sponsors-and-Donations) to help support this project! 🙌

<!-- <br /> -->
</div>

<div class="not-show">

[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://img.shields.io/badge/Project_Status-Active-green?style=flat-square&color=success)](https://github.com/jefmenegazzo/mpu-i2c-drivers)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-Yes-green.svg?style=flat-square&color=success)](https://github.com/jefmenegazzo/mpu-i2c-drivers)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-MIT-lightgrey.svg?style=flat-square&color=success)](LICENSE.txt)
[![Donate](https://img.shields.io/badge/Donate-PayPal-success.svg)](https://www.paypal.com/donate/?hosted_button_id=QA7BLD3X842W6)
[![Donate](https://img.shields.io/badge/Donate-Github-success.svg)](https://github.com/sponsors/jefmenegazzo)

[![GitHub issues](https://img.shields.io/github/issues/jefmenegazzo/mpu-i2c-drivers?style=flat-square&color=blue)](https://github.com/jefmenegazzo/mpu-i2c-drivers/issues)
[![GitHub forks](https://img.shields.io/github/forks/jefmenegazzo/mpu-i2c-drivers?style=flat-square&color=blue)](https://github.com/jefmenegazzo/mpu-i2c-drivers/network/members)
[![GitHub stars](https://img.shields.io/github/stars/jefmenegazzo/mpu-i2c-drivers?style=flat-square&color=blue)](https://github.com/jefmenegazzo/mpu-i2c-drivers/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/jefmenegazzo/mpu-i2c-drivers?style=flat-square&color=blue)](https://github.com/jefmenegazzo/mpu-i2c-drivers/watchers)
[![GitHub contributors](https://img.shields.io/github/contributors/jefmenegazzo/mpu-i2c-drivers?style=flat-square&color=blue)](https://github.com/jefmenegazzo/mpu-i2c-drivers/graphs/contributors/)
</div>

</div>

# MPU I2C Drivers

The MPU-9250, MPU-9255, MPU-9150, MPU-6500, MPU-6555, and MPU-6050 are motion tracking devices equipped with a combination of accelerometer, gyroscope, and magnetometer sensors. They can operate in either 6-axis (MPU-6050) or 9-axis (MPU-9250, MPU-9255, MPU-9150, MPU-6500, MPU-6555) mode, providing high precision and low noise data for reliable performance. These sensors communicate via the I2C protocol.

This project provides a comprehensive collection of I2C driver libraries for the MPU sensors. The libraries enable easy communication and reading of sensor data on embedded devices, such as microcontrollers. Available in various programming languages, they are highly accessible to developers on different platforms and development environments. Each library comes equipped with functions to initialize the sensors, configure sampling rates, select measurement scales, calibrate the sensors, and read the raw data of motion and orientation.

To access the library documentation page in your programming language of choice, please choose from the options provided below.

<div align="center">

[![Arduíno](https://img.shields.io/static/v1?label=&message=Arduino&color=blue&url=https://github.com/jefmenegazzo/mpu-i2c-drivers-arduino&logoWidth=20&logo=arduino&style=flat-square&logoColor=white)](https://github.com/jefmenegazzo/mpu-i2c-drivers-arduino)
[![C](https://img.shields.io/static/v1?label=&message=C&color=blue&url=https://github.com/jefmenegazzo/mpu-i2c-drivers-c&logoWidth=20&logo=C&style=flat-square&logoColor=white)](https://github.com/jefmenegazzo/mpu-i2c-drivers-c)
[![C++](https://img.shields.io/static/v1?label=&message=C%2B%2B&color=blue&url=https://github.com/jefmenegazzo/mpu-i2c-drivers-cpp&logoWidth=20&logo=cplusplus&style=flat-square&logoColor=white)](https://github.com/jefmenegazzo/mpu-i2c-drivers-cpp)
[![C#](https://img.shields.io/static/v1?label=&message=C%23&color=blue&url=https://github.com/jefmenegazzo/mpu-i2c-drivers-csharp&logoWidth=20&logo=csharp&style=flat-square&logoColor=white)](https://github.com/jefmenegazzo/mpu-i2c-drivers-csharp)
[![Python](https://img.shields.io/static/v1?label=&message=Python&color=blue&url=https://github.com/jefmenegazzo/mpu-i2c-drivers-python&logoWidth=20&logo=python&style=flat-square&logoColor=white)](https://github.com/jefmenegazzo/mpu-i2c-drivers-python)
[![Java](https://img.shields.io/static/v1?label=&message=Java&color=blue&url=https://github.com/jefmenegazzo/mpu-i2c-drivers-java&logoWidth=20&logo=openjdk&style=flat-square&logoColor=white)](https://github.com/jefmenegazzo/mpu-i2c-drivers-java)
[![Javascript](https://img.shields.io/static/v1?label=&message=Javascript&color=blue&url=https://github.com/jefmenegazzo/mpu-i2c-drivers-javascript&logoWidth=20&logo=javascript&style=flat-square&logoColor=white)](https://github.com/jefmenegazzo/mpu-i2c-drivers-javascript)
[![Typescript](https://img.shields.io/static/v1?label=&message=Typescript&color=blue&url=https://github.com/jefmenegazzo/mpu-i2c-drivers-typescript&logoWidth=20&logo=typescript&style=flat-square&logoColor=white)](https://github.com/jefmenegazzo/mpu-i2c-drivers-typescript)


</div>

# Roadmap

This project is currently under development, according to the following roadmap. Along with the source code libraries, wikis will also be created that provide comprehensive support documentation for configuring RPi, I2C, VNC, SSH, and other related topics.

| Language | MPU-9250 | MPU-9255 | MPU-9150 | MPU-6500 | MPU-6555 | MPU-6050 |
| --- | --- | --- | --- | --- | --- | --- |
| [Arduino](https://github.com/jefmenegazzo/mpu-i2c-drivers-arduino) | <span style="color: orange;"><span style="color: orange;">Planned</span></span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> |
| [C](https://github.com/jefmenegazzo/mpu-i2c-drivers-c) | <span style="color: orange;"><span style="color: orange;">Planned</span></span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> |
| [C++](https://github.com/jefmenegazzo/mpu-i2c-drivers-cpp) |  <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> |
| [C#](https://github.com/jefmenegazzo/mpu-i2c-drivers-csharp) |  <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> |
| [Python](https://github.com/jefmenegazzo/mpu-i2c-drivers-python) |  <span style="color: green;">**Developing**</span> | <span style="color: green;">**Developing**</span> | <span style="color: green;">**Developing**</span> | <span style="color: green;">**Developing**</span> | <span style="color: green;">**Developing**</span> | <span style="color: green;">**Developing**</span> |
| [Java](https://github.com/jefmenegazzo/mpu-i2c-drivers-java) |  <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> |
| [Javascript](https://github.com/jefmenegazzo/mpu-i2c-drivers-javascript) |  <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> |
| [Typescript](https://github.com/jefmenegazzo/mpu-i2c-drivers-typescript) |  <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> | <span style="color: orange;">Planned</span> |

# Sponsors and Donations

By providing sponsorships and donations, you can support the continuous development of these projects and help keep them active. The more sponsors I have, the more time I can devote to both existing and new projects. As a sponsor, you can suggest new features, support for other programming languages, MPU models, and your project suggestions will be given priority.

<div align="center">

<br />

[![Github Sponsors](https://img.shields.io/static/v1?label=Donate%20with&message=Github%20Sponsors&logo=github&style=for-the-badge&color=blue&logoColor=white)](https://github.com/sponsors/jefmenegazzo)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![PayPal Sponsors](https://img.shields.io/static/v1?label=Donate%20with&message=Paypal&logo=paypal&style=for-the-badge&color=blue&logoColor=white)](https://www.paypal.com/donate/?hosted_button_id=QA7BLD3X842W6)

</div>

Maintenance of this project is made possible by all the following contributors and sponsors.

<!-- sponsors --><!-- sponsors -->
