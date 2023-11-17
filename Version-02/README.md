# WeatherFolowTempest in Home Assistant

Here's how to get the visual I created to display the data of my Tempest station.

Don't get discouraged by all the steps to take. It's a little long and complicated, but it's worth it. 😀

## Installation
 - Install [Home Assistant](https://www.home-assistant.io/installation/) on one of the platforms that is supported. Personally, I use an RPI 4 64g.
 - Install [Hacs](https://github.com/hacs/integration) integration
 - Install [Weatherflow2mqtt](https://github.com/briis/hass-weatherflow2mqtt) integration.
 - Install [Tabbed-card](https://github.com/kinghat/tabbed-card) card from Hacs.
 - Install [Mushroom](https://github.com/piitaya/lovelace-mushroom) card from Hacs.
 - Install [Layout-card](https://github.com/thomasloven/lovelace-layout-card) from hacs.
 - Install [Vertical-stack-in-card](https://github.com/ofekashery/vertical-stack-in-card) card from Hacs.
 - Install [Text-divider-row](https://github.com/iantrich/text-divider-row) card from Hacs.
 - Install [Windrose-card](https://github.com/aukedejong/lovelace-windrose-card) card from Hacs.
 - Install [Apexcharts-card](https://github.com/RomRider/apexcharts-card) card from Hacs.
 - Install [stack-in-card](https://github.com/custom-cards/stack-in-card) card from Hacs.
 - Install [tempometer-gauge-card](https://github.com/monkey-debugger/lovelace-tempometer-gauge-card). Use the manual method.
 - Install [compass-card](https://github.com/tomvanswam/compass-card) card from Hacs.
 - Install [rain-gauge-card](https://github.com/t1gr0u/rain-gauge-card) card from Hacs.
 - Install [UV-Index-card](https://github.com/t1gr0u/uv-index-card) card from Hacs.
 - Install [swiss-army-knife-card](https://github.com/AmoebeLabs/swiss-army-knife-card) card from Hacs.
 - Add the images to the following directory. If the directory does not exist, create it.
   - /config/www/mes_images/
 - Add the sensors to your dashboard. Some sensors are French translations of the station's states. If you use English, you won't need it. Il can be add in configuration.yaml or sensors.yaml files. Personally, I use Packages.
 - Copy the Swiss-Army-Knife templates files sak-layout-mjt-demi-cercle-graphique.yaml and sak-layout-mjt-meteo.yaml in the following folder.
   - /config/lovelace/sak_templates/templates/layouts/
 - Copy the Swiss-Army-Knife colorstops templates files colorstops_mjt_distance_eclaires.yaml and colostops_mjt_nb_eclaires.yaml in the following folder.
   - /config/lovelace/sak_templates/templates/colorstops/
 - Copy the code in WeatherflowTempest.yaml file.

### Captures d'écran

![image](https://github.com/MichelJourdain/WeatherFlow-Tempest-HA/assets/83040228/0624aba5-262b-430e-94dd-81cb93e6cbfc)

![image](https://github.com/MichelJourdain/WeatherFlow-Tempest-HA/assets/83040228/b5a0a06a-b85b-4ab0-a246-c94356bf2aee)
