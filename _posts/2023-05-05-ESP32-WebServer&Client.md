---
layout: post
title: ESP32-WebSever & Client
author: [DENG HUAI SHENG]
category: [Lecture]
tags: [jekyll, ai]
---

This homework is about a robot car controlled with smartphone by connecting to wifi.

---
## Homework Report Format 
## Server and Client
* **功能說明**
1. Webserver：架設服務器，供資料上傳
2. Client：此端為感測器，將空氣濕度及溫度資料透過WIFI上傳至WebServer
* **設計考量與所需零件**
1. 微控制器：處理無線通訊程序
2. Senser DHT11 負責收集空氣的溫度及濕度資料
3. 聯網方式：WiFi 
4. 感測裝置：ESP32＋DHT11
5. 服務器裝置：ESP32
* **系統方塊**
![](https://github.com/DENG0616/MCU-project/blob/main/images/WEBSERVER.png?raw=true)
* **實作相片**
![](https://github.com/DENG0616/MCU-project/blob/main/images/WEBSERVER1.jpg?raw=true)
* **實作結果**
![](https://github.com/DENG0616/MCU-project/blob/main/images/OUTCOME.jpg?raw=true)
