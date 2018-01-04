
# Intel Industrial IoT Workshop Setup Guide
Welcome to the Intel Industrial IoT Workshop. In this workshop, we will explore Industry 4.0 technologies through lectures and hands on labs. By the end of the workshop, you should have a solid understanding of different Industry 4.0 technologies and have some working ideas of how to implement them in your place of business.

**Begin on the lab time by clicking on the first lab below**

## Workshop Agenda
* **Introduction to Industrial Internet of Things**
  - Slide Deck - [Introduction to Industrial Internet of Things](./presentations/01-Introduction-to-the-Industrial-Internet-of-Things.pdf)
  - Video - [Industrial Applications](https://www.intel.com/content/www/us/en/industrial-automation/overview.html)

* **Formalizing the Industrial Internet of Things**
  - Slides - [Formalizing the Industrial Internet of Things](./presentations/02-Software-Defined-Industrial-Systems.pdf)
  - Video - [A New Industrial Revolution through the Internet of Things](https://www.intel.com/content/www/us/en/industrial-automation/industrial-vision-video.html)
  - Lab - [Setup the Up<sup>2</sup> Board Hardware](https://ssg-drd-iot.github.io/lab-up2-setup),
  - Lab - [Setup Alternative IDEs](https://ssg-drd-iot.github.io/doc-alternative-IDEs)

* **Software Defined Industrial Systems - Sensors**
  - Slides - [Sensor and Actuators](./presentations/03-Sensors-and-Actuators.pptx)
  - Video - [Input and Output with MRAA](https://www.youtube.com/watch?v=hY4HudLuvEM)
  - Lab - [Sensors and Actuators](https://ssg-drd-iot.github.io/toc-sensors)

* **Software Defined Industrial Systems - Protocols**
  - Slides - [Industrial Protocols](./presentations/04-Industrial-Protocols.pptx)
  - Lab - [Publish sensor data over MQTT-TLS](https://ssg-drd-iot.github.io/lab-protocols-mqtt-c)
  - Lab - [OPC-UA Server and Client](https://ssg-drd-iot.github.io/lab-sensors-opc-ua)
  - Lab - [Virtual Sensor](https://ssg-drd-iot.github.io/virtual-sensor)

* **Software Defined Industrial Systems - Automation**
  - Slides - [Automation and the IIoT](./presentations/05-Automation.pptx)
  - Video - [Beckhoff Industrial Solutions](https://www.intel.com/content/www/us/en/industrial-automation/products-and-solutions/intel-beckhoff-industrial-solutions-video.html)
  - Lab - [Building an Automation Service](https://ssg-drd-iot.github.io/lab-iot-automation)

* **Security for IIoT**
  - Slides: [Security for IIoT](./presentations/06-Security-Architecture.pptx)
  - Videos: [Introduction to Intel Secure Device Onboard](https://www.youtube.com/watch?v=D3UqrndXs8E)
  - Lab: [Security Concepts](https://ssg-drd-iot.github.io/lab-nuc-security)

* **Computer Vision**
  - Slides: [Computer Vision](./presentations/07-Computer-Vision.pptx)
  - Video: [Introduction to the Movidious Neural Compute Stick](https://www.youtube.com/watch?v=VioTPaYcF98)
  - Video: [Mouser Product Brief on Movidious Neural Computer Stick](https://www.youtube.com/watch?v=gl_iKYr9EKk)
  - Demo: Movidius Lane Detection, OpenVX Lane Detection
  - Lab: [OpenCV Basics and Lane Detection Lab](https://github.com/SSG-DRD-IOT/lab-opencv-examples/)

* **Feedback, Survey and Conclusion**

## Hardware Used in this Workshop
Intel offers scalable hardware solutions at different power, performance and price points. During these labs we will be using two different products that have Intel hardware.

**For the first part of this workshop, we will use the Up2 Board and connect to the Arduino Create online development tool. During the second part of this workshop, we will use the Intel NUC Core i7.**


### Up<sup>2</sup> Board
First is the [Up<sup>2</sup> Board](http://www.up-board.org/upsquared/). It features a 40 Pin I/O connector, multiple USB 3.0 ports, double Gigabit Ethernet, HDMI and more other features make it a perfect solution for different domains and products like Robotics, Drone, Machine Vision, Smart Home, Education, Digital Signage, Intelligent Cars, Internet Of Things. The compatibility with Linux, Android, and all the Windows 10 distributions give you great flexibility, scalability and quick time to market.

![](images/up2.png)


### NUC Core i7
 The second is a [NUC Core i7](https://www.intel.com/content/www/us/en/products/boards-kits/nuc/kits/nuc5i5ryh.html) with powerful performance in a small package. This NUC will be used to power machine learning, computer vision and large dataset jobs anywhere in your network.

![](./images/nuc.png)
