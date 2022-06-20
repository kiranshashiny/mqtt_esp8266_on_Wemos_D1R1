# mqtt_esp8266_on_Wemos_D1R1
 
This code is built for Wemos D1 R1 and publishes and subscribes to mqtt messages from broker.mqtt-dashboard.com

All it needs is the user id and the password of the Home Router.

No credentials for the broker is needed.

![image](https://user-images.githubusercontent.com/14288989/174532174-a966d168-255d-4b98-84e1-5ffcc93c00d7.png)


1:07:23.643 -> WiFi connected
11:07:23.643 -> IP address: 
11:07:23.643 -> 192.168.29.129
11:07:23.643 -> Attempting MQTT connection...connected
11:07:23.996 -> Publish message: hello world #1
11:07:24.342 -> Message arrived [inTopic] 0
11:07:24.447 -> Message arrived [inTopic] 1
11:07:25.736 -> Message arrived [inTopic] 0
11:07:25.990 -> Publish message: hello world #2
11:07:26.418 -> Message arrived [inTopic] 1
11:07:28.013 -> Publish message: hello world #3
11:07:28.430 -> Message arrived [inTopic] 1
11:07:28.711 -> Message arrived [inTopic] 0
11:07:29.989 -> Publish message: hello world #4
11:07:30.445 -> Message arrived [inTopic] 1
11:07:31.721 -> Message arrived [inTopic] 0
11:07:32.012 -> Publish message: hello world #5
11:07:32.443 -> Message arrived [inTopic] 1
11:07:34.004 -> Publish message: hello world #6

The compile options are as shown:

![image](https://user-images.githubusercontent.com/14288989/174532718-a1966b5e-8dfc-476c-9477-351cee03a28c.png)
