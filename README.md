# IRsendMeidi_ESP8266-RN02S-Midea <br>
对Arduino中IRremoteESP8266库美的空调控制的补充，主要依赖于IRremoteESP8266库的sendData()函数来实现数据的发送。<br>
需配合Arduino中的IRremoteESP8266库使用。<br>
主要控制采取的实际数据来源于美的空调RN02S13遥控器，空调型号为美的冷静星。<br>
可以控制的参数：温度（精确到0.5），模式，风速，开关机，定时，扫风，ECO，防直吹。<br>
文件为库文件，直接将文件夹IRsendMeidi放入ArduinoIDE的库文件夹中即可。<br>

参数设置
------
* 温度设置，17-30，分辨率0.5 <br>
* 设置模式，0自动，1制冷，2制热，3抽湿，4送风 <br>
* 设置风速，0自动，1为20%，2为40%，3为60%，4为80%，5为100% <br>
* ECO，扫风，防直吹，参数1为打开，参数0为关闭。<br>

其他说明
-----
对美的编码形式的问题可以参考这篇文章https://blog.csdn.net/weixin_42204837/article/details/109263771 <br>
