---
hidden: true
---

# TOP AI 雙機功能使用教學

## **1.原理介紹**

[OBS下載點我](https://obsproject.com/)

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 205830.png" alt=""><figcaption></figcaption></figure>

## **2.設定OBS**

1.在<mark style="color:$danger;">來源</mark>的位置<mark style="color:$danger;">右鍵新增</mark> <mark style="color:yellow;">🖥️顯示器擷取</mark>

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 105801.png" alt=""><figcaption></figcaption></figure>

2.右鍵點擊<mark style="color:$danger;">濾鏡</mark>

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 110925.png" alt=""><figcaption></figcaption></figure>

3.空白處點擊右鍵><mark style="color:$primary;">新增</mark>><mark style="color:$danger;">剪裁/填充</mark>

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 120009.png" alt=""><figcaption></figcaption></figure>

4.調整擷取範圍

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 122023.png" alt=""><figcaption></figcaption></figure>

第二步\
🖥️<mark style="color:$primary;">**計算解析度**</mark>\
&#x20;     _X 的計算公式 <mark style="background-color:blue;">( 解析度寬度 - 320 ) / 2</mark>_ \
&#x20;     _Y 的計算公式 <mark style="background-color:purple;">( 解析度高度 - 320 ) / 2</mark>_\
_<mark style="background-color:green;">--------------------------------------</mark>_\
&#x20;     <mark style="color:$success;">**以2k解析度舉例**</mark>\
&#x20;      **2560x1440**\
&#x20;      **X(2560-320)/2=1120**\
&#x20;      **Y(1440-320)/2=560**

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 123942.png" alt=""><figcaption></figcaption></figure>

### 常用解析度預設值

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 125054.png" alt=""><figcaption></figcaption></figure>

5.點擊 檔案>設定

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 125221.png" alt=""><figcaption></figcaption></figure>

6.選擇 輸出

<div align="left"><figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 125328.png" alt=""><figcaption></figcaption></figure></div>

7.輸出模式選擇 進階

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 130118.png" alt=""><figcaption></figcaption></figure>

8.到 <mark style="color:$primary;">錄影</mark> 設定中更改 <mark style="color:$danger;">類型</mark>

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 130940.png" alt=""><figcaption></figcaption></figure>

9.更改以下設定如圖所示<br>

1. FFmpeg 輸出類型 選擇 <mark style="color:$danger;">輸出到URL</mark>
2. 檔案路徑或URL 填入 <mark style="background-color:$info;">udp://</mark><mark style="color:$success;background-color:$info;">副機的IPV4</mark><mark style="background-color:$info;">:7777</mark>\
   <mark style="color:$danger;">**切換到副機**</mark> <mark style="color:$success;">按下 Win + R</mark> 搜尋 <mark style="color:blue;">cmd</mark> 並按下 <mark style="color:$danger;">Enter</mark> \
   在小黑窗輸入 ipconfig 並按下 Enter\
   找到 <mark style="color:$success;">乙太網路</mark> 的 <mark style="color:$success;">IPV4</mark> 位址 通常開頭為 <mark style="color:$success;">192.168.x.x</mark> \
   <mark style="color:$danger;">**切換到遊戲機**</mark> 將此IP位址填入到的OBS 取代掉<mark style="color:$success;">副機的IPV4</mark>\
   **範例展示**\
   我副機ip是 192.168.1.1\
   所以我遊戲機上的OBS中就填入\
   <mark style="background-color:$info;">udp://</mark><mark style="color:$success;background-color:$info;">192.168.1.1</mark><mark style="background-color:$info;">:7777</mark>
3. 封裝格式 選擇 mjpeg (影像)
4. 影像位元率 10000 Kbps
5. 關鍵訊框間隔 (訊框) 務必調整 0
6. 設定完 右下套用

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 131058.png" alt=""><figcaption></figcaption></figure>

10.停用所有音效

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 132307.png" alt=""><figcaption></figcaption></figure>

11.到影像照圖設定

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 132631.png" alt=""><figcaption></figcaption></figure>

12.選擇 主要玩遊戲畫面的顯示畫器

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 132855.png" alt=""><figcaption></figcaption></figure>

將紅色框框對齊

<div align="left"><figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 133208.png" alt=""><figcaption></figcaption></figure></div>

按下開始錄製後就能擷取到主遊戲機的畫面

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 133325.png" alt=""><figcaption></figcaption></figure>

## 1.MAKCU雙機設定教學

<mark style="color:$success;">副機下載MAKCU驅動</mark>\
[點我下載驅動](https://mega.nz/file/WjYlmbCZ#UIRcAeeGYsbyL89e_KkAFvG2Km5T3BZL_PVU58XayUU)\
下載後如圖安裝

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 133746.png" alt=""><figcaption></figcaption></figure>

## 2.MAKCU接線方式

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 205509.png" alt=""><figcaption></figcaption></figure>

## 3.副機MAKCU移動設定

**副機開啟裝置管理員設定COM**\
**COM設定完之後**<mark style="color:$success;">**副機開啟TOP AI**</mark>

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 135602.png" alt=""><figcaption></figcaption></figure>



## 4.最後一步副機TOP AI選擇雙機串流

<mark style="color:$success;">1. IPv4填入副機剛剛查詢的IPv4</mark>\ <mark style="color:$warning;">2. 服務器端口填入 7777</mark>\
3.服務端編號預設1<mark style="color:$tint;">即可</mark>\
<mark style="color:$warning;">4.點擊連接</mark>

<figure><img src="../.gitbook/assets/螢幕擷取畫面 2026-03-09 134528.png" alt=""><figcaption></figcaption></figure>

#### 以上教學有問題都可以開單問:)
