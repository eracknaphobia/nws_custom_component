# nws_custom_component
National Weather Service custom component for Home Assistant

This should be placed in your configuration folder:
```
<config directory>/custom_components/sensor/nws_alerts.py
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
