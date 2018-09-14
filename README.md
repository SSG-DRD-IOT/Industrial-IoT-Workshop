
# Intel Industrial IoT Workshop Setup Guide
Welcome to the Intel Industrial IoT Workshop. In this workshop, we will explore Industry 4.0 technologies through lectures and hands on labs. By the end of the workshop, you should have a solid understanding of different Industry 4.0 technologies and have some working ideas of how to implement them in your place of business.

## How Do I Use the Lab Material

The links below will guide the workshop attendee through the slides, videos and labs in the Intel Industrial IoT Workshop.

The first lab, [Setup the Up<sup>2</sup> Board Hardware](https://software.intel.com/en-us/upsquared-grove-getting-started-guide), is a preparatory lab to setup the hardware and software used in the rest of the labs, and to deploy a sample program to be sure that the attendee has correct understood the workflow to write, compile and deploy an application.

The protocol labs use the Up2 Board, the sensors from the hardware kit and the Arduino Create environment to prototype a sensor, use the MRAA and UPM libraries to create the interface between the sensor and the Up2 board and then explore several different network protocols common to the IIoT.

Next, we will spend some time talking about different types of automation and use a Juypter Notebook running Python to build a rules-based automation service.

Lastly, we will look at the smart video field, where software and hardware are merging to produce new intelligent video systems.

The Intel IoT Developer Relations team, hopes that you enjoy this IIoT Workshop.

## Social Media and Feedback

If you are posting on social media the hashtags for the event are ***IntelIoT*** and **CommercialIoT**.

Feel free to talk to any of the Intel people at this event to leave feedback.

Also if you find errors in the workshop material all of our labs are on Github. feel free to fork any repository and send us a pull request. After all, that's why we are on Github.


## Workshop Agenda
* **Intel Strategy and Developer Program for the IIoT**
  - Slides - [Deck Strategy and Developer Program for the IIoT ](./presentations/Intel-Strategy-and-Dev-Program-for-IIoT.pdf)
  - Video - [Industrial Applications](https://www.intel.com/content/www/us/en/industrial-automation/overview.html)

* **Introduction to Industrial Internet of Things**
  - Slide Deck - [Introduction to Industrial Internet of Things](./presentations/Introduction-to-the-Industrial-Internet-of-Things.pdf)
  - Video - [A New Industrial Revolution through the Internet of Things](https://www.intel.com/content/www/us/en/industrial-automation/industrial-vision-video.html)

* **The UP Squared Development Board**
  - Slide Deck - [Up2 AI Vision Kit Presentation](./presentations/2018-09-Intel-Workship-AI-Edge-UP-Series.pdf)

   [Up2 AI Vision Kit Presentation]()
  - Video - [Input and Output with MRAA](https://www.youtube.com/watch?v=hY4HudLuvEM)
  - Lab - [Connect the Up2 to the Development Computer](https://github.com/intel-iot-devkit/smart-video-workshop/blob/master/up2-vision-kit/dev_machine_setup.md)
  - Lab - [Setup the Up<sup>2</sup> Board Hardware with Arduino Create](https://github.com/SSG-DRD-IOT/lab-up2-setup)

* **Software Defined Industrial Systems - Workload Consolidation**
  - Slides - [Workload Consolidation](./presentations/Work Load Consolidation - Virtualization and Real-Time Systems.pdf)
  - Demo - IEI Tank Workload Consolidation

* **Software Defined Industrial Systems - Protocols**
  - Slides - [Industrial Protocols](./presentations/Industrial-Protocols.pdf)
  - Video - [Beckhoff Industrial Solutions](https://www.intel.com/content/www/us/en/industrial-automation/products-and-solutions/intel-beckhoff-industrial-solutions-video.html)
  - Lab - [OPC-UA Server and Client](https://github.com/SSG-DRD-IOT/lab-sensors-opc-ua)

* **Software Defined Industrial Systems - Security**
  - Slides - [TODO: Finalize Slides]()

* **Predictive Analytics and Data Modeling**
  - Slides - [Predictive Analytics and Data Modeling]()
  - Slides - [Data Modeling in Python](./presentations/predictive-analytics-bosch-lab.pdf)
  - Lab - [Exercises in Jupyter Lab](https://github.com/SSG-DRD-IOT/lab-predictive-analytics)

* **Feedback, Survey and Conclusion**

## Hardware Used in this Workshop
Intel offers scalable hardware solutions at different power, performance and price points. During these labs we will be using two different products that have Intel hardware.

**For the first part of this workshop, we will use the Up2 Board and connect to the Arduino Create online development tool. During the second part of this workshop, we will use the Intel NUC Core i7.**


### Up<sup>2</sup> Ai Vision Kit
This kit is available at [Up<sup>2</sup> Board](http://www.up-board.org/upsquared/). It features a 40 Pin I/O connector, multiple USB 3.0 ports, double Gigabit Ethernet, HDMI, Mini PCI-Express and a Movidius Mini PCI-express card which make it a perfect solution for different domains and products like Robotics, Drone, Machine Vision, Smart Home, Education, Digital Signage, Intelligent Cars, Internet Of Things. The compatibility with Linux, Android, and all the Windows 10 distributions give you great flexibility, scalability and quick time to market.

![](images/kit-contents-overlay.png)
> #### Disclaimer
> Intel and the Intel logo are trademarks of Intel Corporation or its subsidiaries in the U.S. and/or other countries.
> *Other names and brands may be claimed as the property of others
