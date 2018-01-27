Home Assistant Custom Build
===========================

`Home Assistant <https://github.com/home-assistant/home-assistant>` is a home automation platform running on Python 3. It is able to track and control all devices at home and offer a platform for automating control.

This fork just adds some tools and plugins packages in the Docker build :

Shell utils
-----------
- netcat
- nmap

Usage
=====

    docker run -v ~/docker/home-assistant:/config -p 8123:8123 lspg/homeassistant