# nws_custom_component
National Weather Service custom component for Home Assistant

This should be placed in your configuration folder:
```
For HA .87 and lower
<config directory>/custom_components/sensor/nws_alerts.py

For HA .88 and higher (rename nws_alerts.py to sensor.py)
<config directory>/custom_components/nws_alerts/sensor.py
```


To create an sensor instance add to your sensor definitions:
```
- platform: nws_alerts
  zone_id: 'PAC049'
```
or comma separated values

```
- platform: nws_alerts
  zone_id: 'PAC049,WVC031'
```
