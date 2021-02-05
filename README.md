# HASS AP

## The Idea
Creating an Access Point for my IoT Devices on my Raspberry Pi running Home Assistant OS


## Intro
There are multiple guides for setting up an Access Point for the Raspberry Pi for example from [raspberrypi.org](https://www.raspberrypi.org/documentation/configuration/wireless/access-point-routed.md). However these guides are made for the Raspbian/Debian OS, but Home Assistant OS is based on Alpine Lunux.

I assume most of the commands carry over.

## Goal
Creating a Script / Package / HACS Integration for setting up and configuring an Access Point with a DHCP Server and Firewall. 

 * The DHCP Server should have an easy way to set the IP addresses of certain devices to be static
 * The Firewall should have an easy way to configure access to certain websites / services. By default the devices should be able to reach the Home Assistant installation
 * Some research into WiFi adapters that offer better coverage and performance than the one onboard the Raspberry Pi
