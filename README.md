# z2m-moes-trv-801-converter
Zigbee2MQTT converter for ZTRV-801-EN, Zigbee MOES Tuya Smart TRV [https://www.moestech.com/blogs/news/ztrv-801](https://www.moestech.com/blogs/news/ztrv-801) Aliexpress don't usually give you the model number. This is tested on `Zigbee2MQTT 1.40.2`.

![Product Photo For Reference](https://cdn.shopifycdn.net/s/files/1/0531/3206/6981/files/1_480x480.png?v=1702610781) 
## Guide
1. (Optional) Change the `fingerprint` section, sometimes the `manufacturerName` change depending on batches, if so pair it in Zigbee2MQTT and note down the `Zigbee Manufacturer` and replace it if it is different.
2. Copy the `moes_valve_ZTRV801.js` to your Zigbee2MQTT `/data` directory (Or anywhere as long as Z2M can access it)
3. Add the relative path to the `external_converters` section in `configuration.yaml`
## Troubleshoot
- Remember to initialize the valve
- The battery reporting is a bit unstable, if you can't get battery readings, reset(remove the battery) and pair it again
