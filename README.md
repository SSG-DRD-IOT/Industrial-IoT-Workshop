
# Intel Industrial IoT Workshop Setup Guide
Welcome to the Intel Industrial IoT Workshop. In this workshop, we will explore Industry 4.0 technologies through lectures and hands on labs. By the end of the workshop, you should have a solid understanding of different Industry 4.0 technologies and have some working ideas of how to implement them in your place of business.

## How Do I Use the Lab Material

The links below will guide the workshop attendee through the slides, videos and labs in the Intel Industrial IoT Workshop.

The first lab, [Setup the Up<sup>2</sup> Board Hardware](https://software.intel.com/en-us/upsquared-grove-getting-started-guide), is a preperatory lab to setup the hardware and software used in the rest of the labs, and to deploy a sample program to be sure that the attendee has correct understood the workflow to write, compile and deploy an application.

The sensor and protocol labs use the Up2 Board, the sensors from the hardware kit and the Arduino Create environment to prototype a sensor, use the MRAA and UPM libraries to create the interface between the sensor and the Up2 board and then explore several different network protocols common to the IIoT.

Next, we will spend some time talking about different types of automation and use a Juypter Notebook running Python to build a rules-based automation service.

Lastly, we will look at the smart video field, where software and hardware are merging to produce new intelligent video systems.

The Intel IoT Developer Relations team, hopes that you enjoy this IIoT Workshop.

## Social Media and Feedback

If you are posting on social media the hashtags for the event are ***IntelIoT*** and **CommercialIoT**.

Feel free to talk to any of the Intel people at this event to leave feedback.

Also if you find errors in the workshop material all of our labs are on Github. feel free to fork any repository and send us a pull request. Afterall, that's why we are on Github.

## Before Starting Workshop
Here are some tools you may require to install on your workstation to help you cover labs.

  - SSH Client for Windows: [PuTTy](https://putty.org)
  - Suggested web browser for Arduino Create is [Google Chrome](https://www.google.com/chrome/)

  *username*/*password* for UP2 Board: *upsquared*/*upsquared*

## Workshop Agenda
* **Introduction to Industrial Internet of Things**
  - Slide Deck - [Introduction to Industrial Internet of Things](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop/blob/milano-workshop/presentations/01-Introduction-to-the-Industrial-Internet-of-Things.pptx)
  - Video - [Industrial Applications](https://www.intel.com/content/www/us/en/industrial-automation/overview.html)
  - Video - [A New Industrial Revolution through the Internet of Things](https://www.intel.com/content/www/us/en/industrial-automation/industrial-vision-video.html)
  - Lab - [Setup the Up<sup>2</sup> Board Hardware](https://github.com/SSG-DRD-IOT/lab-up2-setup/tree/milano-workshop),

* **Software Defined Industrial Systems - Formalizing Industrial IoT**
  - Slide Deck - [Software Defined Industrial Systems](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop/blob/milano-workshop/presentations/02-Software-Defined-Industrial-Systems.pptx)
  - Video - [Industry 4.0 Plug&Play by Alleantia and Intel](https://vimeo.com/185239991)

* **Software Defined Industrial Systems - Sensors**
  - Slides - [Sensor and Actuators](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop/blob/milano-workshop/presentations/03-Sensors-and-Actuators.pptx)
  - Video - [Input and Output with MRAA](https://www.youtube.com/watch?v=hY4HudLuvEM)
  - Lab - [Sensors and Actuators](https://github.com/SSG-DRD-IOT/toc-sensors/tree/milano-workshop)

* **Software Defined Industrial Systems - Protocols**
  - Slides - [Industrial Protocols](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop/blob/milano-workshop/presentations/04-Industrial-Protocols.pptx)
  - Lab - [MQTT - Client Publish/Subscribe](https://github.com/SSG-DRD-IOT/lab-protocols-mqtt-arduino/)
  - Lab - [OPC-UA - Server and Client](https://github.com/SSG-DRD-IOT/lab-sensors-opc-ua)
  
* **Internet of Things - Security**
  - Slides: [IoT Security](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop/blob/milano-workshop/presentations/06-Security-Architecture.pptx) 
  - Resource: [Intel EPID Article](https://software.intel.com/en-us/articles/intel-enhanced-privacy-id-epid-security-technology)

* **Internet of Things - Computer Vision**
  - Slides: [Computer Vision](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop/blob/milano-workshop/presentations/07-Computer-Vision.pptx)
  - Video: [Introduction to the Movidius Neural Compute Stick](https://www.youtube.com/watch?v=VioTPaYcF98)
  - Video: [Mouser Product Brief on Movidius Neural Computer Stick](https://www.youtube.com/watch?v=gl_iKYr9EKk)
  - Lab: [Open CV Exercises](https://github.com/SSG-DRD-IOT/lab-opencv-examples/tree/milano-workshop)
  - Demo: [Realtime object detection](https://github.com/SSG-DRD-IOT/lab-opencv-examples/tree/milano-workshop/OpenCV_Object_Detection/real_time_object_detection) demo can be ran on UP2 board or any other system with relative setup.

* **Feedback, Survey and Conclusion**

## Hardware Used in this Workshop
Intel offers scalable hardware solutions at different power, performance and price points. During these labs we will be using two different products that have Intel hardware.

**For the first part of this workshop, we will use the Up2 Board and connect to the Arduino Create online development tool.**

### Up<sup>2</sup> Board
First is the [Up<sup>2</sup> Board](http://www.up-board.org/upsquared/). It features a 40 Pin I/O connector, multiple USB 3.0 ports, double Gigabit Ethernet, HDMI and more other features make it a perfect solution for different domains and products like Robotics, Drone, Machine Vision, Smart Home, Education, Digital Signage, Intelligent Cars, Internet Of Things. The compatibility with Linux, Android, and all the Windows 10 distributions give you great flexibility, scalability and quick time to market.

![](images/up2.png)

## Additional Material
* **IDEs**
  - Lab - [Extra Infomration - Setup Alternative IDEs](https://github.com/SSG-DRD-IOT/doc-alternative-IDEs)
  
* **Automation**
  - Slides - [Automation and the IIoT](https://github.com/SSG-DRD-IOT/Industrial-IoT-Workshop/blob/milano-workshop/presentations/05-Automation.pptx)
  - Lab - [Virtual Sensor](https://github.com/SSG-DRD-IOT/virtual-sensor)
  - Python Lab - [Building an Automation Service in Python](https://github.com/SSG-DRD-IOT/lab-automation-jupyter/) 
  - JS Lab - [Building an Automation Service in JavaScript](https://github.com/SSG-DRD-IOT/lab-iot-automation)
