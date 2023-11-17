# WeatherFlow in Home Assistant

Display the data of my Tempest station.

## Installation
 - Install [Home Assistant](https://www.home-assistant.io/installation/) on one of the platforms that is supported. Personally, I use an RPI 4 64g.
 - Install [Hacs](https://github.com/hacs/integration) integration
 - Install [Weatherflow2mqtt](https://github.com/briis/hass-weatherflow2mqtt) integration.
 - Install [weatherflow_forecast](https://github.com/briis/weatherflow_forecast) integration.
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

 - Add the images windy-day.svg to the following directory. If the directory does not exist, create it.
   - /config/www/mes_images/
 - Add the sensors in the files previsions.yaml and weather_flow.yaml to your dashboard. 
 - Copy the code in WeatherTempest.yaml file.

### Captures d'écran

![image](https://github.com/MichelJourdain/WeatherFlow-Tempest-HA/assets/83040228/2a6058de-3042-48a4-95e1-92bbb5252878)

![image](https://github.com/MichelJourdain/WeatherFlow-Tempest-HA/assets/83040228/14450f78-6145-4173-b33e-cf9fb3ca8879)
