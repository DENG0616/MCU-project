---
layout: post
title: Innovative Project Proposal
author: [DENG HUAI SHENG]
category: [Lecture]
tags: [jekyll, ai]
---

This homework is to propose an innovative project and describe the key features, list all Design Considerations and the required technologies, then draw the System Block Diagram.

---
## Homework Report Format
## 家用手臂機器人
* **應用與功能說明**
1. 居家監控：外出時可透過鏡頭查看屋內狀況
2. 遠端控制：在外可利用網路連線控制手臂
3. 使用用途：能夠完成遠端控制或自動完成指令
4. 如何偵測：使用語音辨識以及鏡頭辨識
5. 餐飲服務：遞送飲料以及各式各樣的食物
6. 家務服務：可遠端查看家寵的飲食以及維護其生活環境
* **設計考量與所需相關技術**
1. 移動方式：履帶or輪胎
2. 供電方式：電池＋充電
3. 聯網方式：WiFi 或 BLE to中控電腦
4. 感測裝置：收音麥克風＋鏡頭
* **系統方塊圖**
![](https://github.com/DENG0616/MCU-project/blob/main/images/the%20robot%20design.png?raw=true)
* **系統類似**
![](https://github.com/DENG0616/MCU-project/blob/main/images/2016-10-17_132459.png?raw=true)
<iframe width="1115" height="697" src="https://www.youtube.com/embed/Mex-8bbIjEI" title="DUM-E SAVING TONY&#39;S LIFE - IRON MAN 1(2008) - 4K VIDEO CLIP" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### 應用功能說明
1. 操作廚具：咖啡機＋果汁機＋烤麵包機＋微波爐+烤箱+氣炸鍋
2. 存取冰箱：辨識食物, 存放食材，或取出食材, 送至廚具

### 設計考量與相關技術
**系統設計考量：**<br>
1. 操作方式:垂直升降式手臂 or 懸吊式手臂
2. 移動方式:兩輪 or 滑軌懸吊
3. 供電方式:鋰電池
4. 聯網方式:WiFi或BT to 手機

**所需相關技術：**
1. 滑軌式機器手臂 ＆ 軟式夾具
2. 食物辨識分類：Jetson-Nano + IMX219
3. 電子鼻：氣味感測與辨識 MQ2

### 系統方塊圖


---
## Market Analysis (市場分析)
![](https://blog.hubspot.com/hs-fs/hubfs/tam-sam-som.png?width=1200&name=tam-sam-som.png)

### TAM of Future Home Products
The Target Market size (TAM) of Future Home Products is the number of household.<br>

### Taiwan Households = 8.93M (台灣 9百萬戶）
* [Total number of households in Taiwan from 2010 to 2020(in 1,000s)](https://www.statista.com/statistics/330804/taiwan-national-total-number-of-households/#:~:text=By%20the%20end%20of%202020,households%20in%20the%20previous%20year.)

### Japan Households = 57.2M (日本 5千7百萬戶)
* [Number of Households in Japan](https://www.helgilibrary.com/indicators/number-of-households/japan/) 

### American Households = 129.93M (美國 1.3億戶)
* [Number of households in the U.S. from 1960 to 2021(in millions)](https://www.statista.com/statistics/183635/number-of-households-in-the-us/)<br>
* [The average American household consisted of 2.51 people in 2021.](https://www.statista.com/statistics/183648/average-size-of-households-in-the-us/)<br>

<br>
<br>

*This site was last updated {{ site.time | date: "%B %d, %Y" }}.*


