# ha_localweather
Home assistant local weather dashboard

<img src="Dashboard Screenshot 1.png" alt="Dashboard">
<img src="Dashboard Screenshot 2.png" alt="Dashboard">
<img src="40051D0D-6C12-47FE-9AA5-DF6089FEEAE8.jpeg" alt="Solar Weather Ststion">
Recently moving to Oklahoma, I realize we are more likely to be subject to extreme weather-related events. I wanted to take my weather station to the next level.

|Dependancies|
|-|
|Hardware|
|-|
|<a href="https://www.amazon.com/AcuRite-Wireless-Weather-Station-Monitoring/dp/B06XNPKKNZ/ref=sr_1_7?keywords=acurite+5in1+weather+station&qid=1678805983&sprefix=acurite+5i%2Caps%2C267&sr=8-7&ufe=app_do%3Aamzn1.fos.18ed3cb5-28d5-4975-8bc7-93deae8f9840">Acurite 5in1 weatherstation</a>|
|<a href="https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TD42S27/ref=sr_1_3?crid=1XTFUN1QN7TXM&keywords=raspberry+pi&qid=1678806232&sprefix=raspberry+p%2Caps%2C204&sr=8-3&ufe=app_do%3Aamzn1.fos.18ed3cb5-28d5-4975-8bc7-93deae8f9840)">Raspberry Pi or two, you can opt to vertualize the HA instance in HyperV or other hypervisor to save on hardware</a>|
|<a href="https://www.amazon.com/NooElec-NESDR-Mini-RTL2832-Antenna/dp/B00P2UOU72/ref=sr_1_4?keywords=sdr+dongle&qid=1678806167&sprefix=sdr%2Caps%2C263&sr=8-4">SDR Dongle</a>|
| |
|Software|
|-|
|<a href="https://www.home-assistant.io">Home Assistant</a>|
|<a href="https://github.com/dakotasnapshot/ha_localweather/tree/sdrpi"> SDR Pi Setup</a>
|https://github.com/kalkih/mini-graph-card|
|https://github.com/tomvanswam/compass-card|
|https://www.home-assistant.io/integrations/feedreader/|
|https://community.home-assistant.io/t/lovelace-rss-feed-parser-plugin-list-card/64637|
|https://github.com/custom-components/feedparser|
|<a href="https://youtu.be/dqTn-Gk4Qeo">MQTT Server Setup</a>|
|https://www.weather.gov/rss|

iOS push notifications for severe weather events as well as homekit verbal announcements via google tts. 
<a href="automations">Use this automation listed for iOS and homekit alerts</a>

