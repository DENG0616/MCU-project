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
![](https://github.com/DENG0616/MCU-project/blob/main/images/123.png?raw=true)
* **實作相片**
![](https://github.com/DENG0616/MCU-project/blob/main/images/20230423_234431.jpg?raw=true)
* **實作影片**
* **前進**
<iframe width="385" height="684" src="https://www.youtube.com/embed/vw0Oo5jidaM" title="forwork" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
* **後退**
<iframe width="385" height="684" src="https://www.youtube.com/embed/sw4PZcQTnek" title="back" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
* **右轉**
<iframe width="385" height="684" src="https://www.youtube.com/embed/fDQ0pliakaQ" title="right" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
* **左轉**
<iframe width="385" height="684" src="https://www.youtube.com/embed/8leGL-gKyak" title="left" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

* **程式碼**
* **PART1 宣告腳位及WIFI設定**
![](https://github.com/DENG0616/MCU-project/blob/main/images/PART1.png?raw=true)

* **PART2 自走車驅動方向設定**
![](https://github.com/DENG0616/MCU-project/blob/main/images/PART2.png?raw=true)

* **PART3 連結網頁設定**
![](https://github.com/DENG0616/MCU-project/blob/main/images/PART3.png?raw=true) 
