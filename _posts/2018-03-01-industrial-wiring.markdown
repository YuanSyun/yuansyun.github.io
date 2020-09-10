---
layout: post
title:  "利用虛擬實境進行工業配線證照訓練"
description: ""
date:       2018-03-01 09:00:00
author:     "Yuan-Syun Ye"
header-img: assets/images/industrial wring-partical training.png
---

傳統的工業配線的練習需要專業的硬體設備以及老師的專業指導，若不當的操作可能會造成線路短路或是設備損毀，此作品則是透過虛擬實境將配線的過程轉移到虛擬世界，讓學生能夠專注在配線的過程。另外學生會依照教學的指示將線路連接在一起，若接錯線系統則會提示學生，讓學生可以透過此系統自行學習。
![partical training](/assets/images/industrial wring-partical training.png)

## 真實工業配電證照考題 ##
由於要讓使用者可以將學習的經驗應用於實際應用上，因此實際電路是參考真實工業配線考試的配置。該題目為採用兩個三相電磁開關來控制一個馬達的正反轉，並且使用三個按鈕來控制該馬達正轉、反轉及停止。
![real test](/assets/images/industrial wring-real test.jpg)

## 元件功能說明及模擬 ##
為了可以在體驗的過程中學習各個元件，在體驗中會設置一個教學的區域，當使用者觸碰該區域內的元件時就會顯示該物件的圖示以及說明。除了透過影片的方式向學生教學，在接線的過程中每個元件都能運行自己的功能，像是保險絲可以保護電路中電流不會過載、三相電磁開關AB接點連通時則會連接上下方的三相電流、按鈕按下後會連接兩端的電流等。
![scene view](/assets/images/industrial wring-scene view.jpg)

## 配線圖及操作錯誤提示 ##
傳統的考證過程中施工人員會按照圖施工，其中為了引導學生進行配線，該作品會在配線圖上閃爍該目前的配線線段，當學生配完該線段後會進入到下一個目標，直到最後完成施工。其過程中若學生配線錯誤，該配線盤會給予提示音效，讓學生重新檢視配線的位置。
<iframe style="width: 560; height: 310" src="https://www.youtube.com/embed/8u3bs3799Yg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>