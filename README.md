# IoT Demo for DSA Abuja

## Introduction

In this demo we will collect data from the following sensors
1. temperature and humidity sensor
1. Motion detection sensor

The data will be collected by a Nucleo board connected to the internet via low power long range (LoRa) radio.

We will also demonstrate machine learning on IoT data using Gaussian process regression. The data contained in this repository was collected at the Dedan Kimathi University of Technology coffee farm and builds on work started at DSA 2018 Nyeri. We  have Damon Civin, Jan Jongboom and Gen-Tao Chiang of ARM to thank for our introduction to IoT and long range low power communication networks. See blog posts about DSA by [Damon](https://blog.usejournal.com/arm-at-data-science-africa-2018-1071389e92d9) and [Jan](https://os.mbed.com/blog/entry/Making-tomatoes-smart-at-Data-Science-Af/).


## Coffee Monitoring Data

We have deployed the following sensors
1. Ambient Temperature
1. Relative Humidity
1. Soil Temperature 
1. Soil Moisture

The aim is to use these data to help plan farming activities such as irrigation and fungicide application.

The sensors are connected to a [Nucleo F446re](https://os.mbed.com/platforms/ST-Nucleo-F446RE/) development board running code contained in this [repo](https://github.com/ciiram/nyeri-coffee).


