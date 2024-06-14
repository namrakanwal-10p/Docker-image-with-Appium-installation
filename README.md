# Docker-image-with-Appium-installation
This will cover up the creation of appium image with docker and shared that image to other person for use.
How to pull docker image from already created on another person:
It is pre-requist to have docker-desktop installed on system.

**Commands:**
1.docker pull yourusername/appium-image:latest

2.docker run -d -p 4723:4723 appium-image:latest
