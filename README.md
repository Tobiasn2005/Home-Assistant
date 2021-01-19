# Home-Assistant

[Supervised Home Assistant](https://home-assistant.io/) in a VirtualBox environment. My use case is a wall mounted Microsoft Surface Pro4 displaying Home Assistant in Full screen Chrome.

## Features

* Dynamic 3D Floorplan: Brightness mapped individual lights with custom popup controller.
* Dynamic floorplan view, adjusts brightness based on calculated brightness of the sun.
* Less cluttered interface displaying [more information](https://github.com/thomasloven/hass-browser_mod#popup) on a [long press](https://www.home-assistant.io/lovelace/picture-elements/#hold_action), inspired by [Mattias Persson](https://github.com/matt8707/hass-config).
* Custom rain card to display predicted rain in the next 2 hours - [seperate repo here](https://github.com/lukevink/home-assistant-buienradar-forecast-card)

## Floorplan with controllable lights and heating control

* A different take on designing a [Lovelace UI](https://www.home-assistant.io/lovelace/) using a [Picture Elements Card](https://www.home-assistant.io/lovelace/picture-elements/) in [panel mode](https://www.home-assistant.io/lovelace/dashboards-and-views#panel)
* Using a [swiper card](https://community.home-assistant.io/t/lovelace-swiper-card/72447) to swipe between ground and first floor

![animations](https://raw.githubusercontent.com/Tobiasn2005/Home-Assistant/main/www/ui/floorplan.gif)

![animations](https://raw.githubusercontent.com/Tobiasn2005/Home-Assistant/main/www/ui/cam&lights.gif)

## Full integration with Tesla Model 3 with history stats and HVAC controls:

![animations](https://raw.githubusercontent.com/Tobiasn2005/Home-Assistant/main/www/ui/tesla.gif)

## Devices with animated custom icons and Dutch Covid-19 stats. In the footer two buttons for updates and HA info.

* Monitor [Home Assistant](https://home-assistant.io/) and [Network Attached Storage](https://www.synology.com)
* Lists available HACS updates and release notes for Home Assistant

![animations](https://raw.githubusercontent.com/Tobiasn2005/Home-Assistant/main/www/ui/devices.gif)

## Media

Conditionally displaying media player controls based on last active device such as [Apple TV](https://www.home-assistant.io/integrations/apple_tv/), [Playstation 4](https://www.home-assistant.io/integrations/ps4/), [Google Nest Mini](https://www.home-assistant.io/integrations/cast/). If nothing is active for 15 minutes then a poster of last downloaded movie/episode is shown ([Radarr](https://github.com/Radarr/Radarr)/[Sonarr](https://github.com/Sonarr/Sonarr)). Swipe to reveal other than last active media players.

![media](https://raw.githubusercontent.com/matt8707/hass-config/master/www/img/media.gif)

## The sidebar

A [Picture Elements Card](https://www.home-assistant.io/lovelace/picture-elements/) per view to create dynamic [templates](https://www.home-assistant.io/docs/configuration/templating/).

* Time and date
* Overlay of Spotife media playing
* Temperature in and outside in minigraph
* Christmas decoration when its time :-)
* See household members presence and more-info when pressed
* Ability to deserve a crown based on your amount of steps during the day
* Other conditional alerts

![animations](https://raw.githubusercontent.com/Tobiasn2005/Home-Assistant/main/www/ui/person.gif)

## Weather

Custom card to display projected rain in the next 2 hours, using Buien Radar (Dutch weather service).
For more on this card, check out [this repo](https://github.com/lukevink/home-assistant-buienradar-forecast-card)

![animations](https://raw.githubusercontent.com/Tobiasn2005/Home-Assistant/main/www/ui/weather.gif)

***

The guys and projects I took my inspiration from are from Mattias Persson and Luke Vink (great thanks to them!)

**Mattias Home Assistant Topic**  
[https://community.home-assistant.io/t/a-different-take-on-designing-a-lovelace-ui/162594]
(https://community.home-assistant.io/t/a-different-take-on-designing-a-lovelace-ui/162594)

**Luke Vink Floorplan Topic**
[https://community.home-assistant.io/t/floorplan-ui-with-color-synced-lights/169417]
(https://community.home-assistant.io/t/floorplan-ui-with-color-synced-lights/169417)
