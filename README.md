# PiCluster
Raspberry Pi Cluster project

## Introduction

This project aims to build a computer cluster of raspberry pi. Is this going to be more powerful than any modern regular computer ? No, but the goal is to learn many things during the building process, such as network, containerization, parallel programming, etc...

### Table of content

 1. [Introduction](#hntroduction)
 2. [Hardware](#hardware)
    a. [Parts](#parts)
    b. [Building the CLuster](#building-the-cluster)
 3. [Software](#software)


## Hardware

### Parts

1. The pies

I bought the raspberry pies off of Facebook market place. The SD cards were already provided

2. Network Harware

8 ports network switch, 1 port to connect to my network, 7 ports to connect to the compute nodes. Ethernet cables

3. Power source

You will need a power source that has the capacity of powering all the raspberry pies at the same time. Things to look for: Watts and Amp capacity. Power cables

4. Cluster rack

It is a good idea to have proper ventilation for your cluster in order to keep your pies under decent temperature. I bought my cluster rack from [website], but I modified it to be able to fit more pis behind the fan. I could have gone for the bigger model but it was more expensive and I wanted to keep my cluster somewhat compact. I used a soldering iron to burn extra holes in the plexiglass plate to be able to mount the pies side by side.

### Building the Cluster

Warning: Make sure you do the [step 1] of the software installation before you put the cluster together as once it is built, it is complicated to access the SD card slot without disassembling the rack.


## Software

### Raspberry Pi OS

Installing ubunter server on the sd cards 

### Network configuration

reserving ip adresses, checking to see of the pis appear on your network

### Communicating with the cluster

#### Fab

### Light Kubernetes (K3s)

#### Hadoop

#### Home Server

