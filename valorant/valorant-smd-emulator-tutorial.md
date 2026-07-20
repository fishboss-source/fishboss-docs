---
hidden: true
---

# \[特戰] SMD輔助 移除反作弊 使用教學

> 本文提供《特戰英豪》SMD 輔助工具與移除反作弊模擬器的完整安裝、注入與運行教學。包含防封號的前置作業、雙金鑰（Key）獨立下載配置流程、遊戲內 F5/F7/F8 快捷鍵操作規範，以及常見的 102/5 錯誤代碼排解指南，助您穩定安全運行。

***

## 一、前置作業 (一次性準備)

為了確保安全不封號，並防止程式因環境問題無法開啟，請**務必**在首次使用前完整執行以下前置步驟：

{% stepper %}
{% step %}
### 通用前置作業第一\~三步

#### [點我前往查看](../)
{% endstep %}

{% step %}
### 環境清理與狀態檢查

* **清理殘留（強烈建議）：** 執行工具前，請先下載並清理舊有環境。\
  👉 [點我前往下載：SMD 偽裝殘留刪除工具](https://mega.nz/file/TQdk0BCb#qQuduzbxw9Dhn8s-QXGMsR0hSkZei3FLNCPCYQm0fpo) _(下載後必須「右鍵以系統管理員身分開啟」)_
* **檢查伺服器狀態：** 請在開啟前確認伺服器是否正常運行。\
  👉 [點我前往：SMD 偽裝伺服器狀態檢查](https://sckmd.xyz/status/emulator/)
{% endstep %}

{% step %}
### 獨立金鑰（Key）下載配置

根據您購買的品項，依照以下規範下載對應的登入器：

1. <mark style="color:$success;">前往您的訂單載點，分別輸入訂單內提供的</mark><mark style="color:$success;">**密鑰 (Key)**</mark><mark style="color:$success;">，點擊</mark> <mark style="color:$success;"></mark><mark style="color:$success;">**「Download」**</mark> <mark style="color:$success;"></mark><mark style="color:$success;">開始下載。</mark>
2.  **重要規範（同時購買「內部輔助 + 移除反作弊」的用戶）：**

    * 這兩個產品的密鑰是獨立的，您必須**獨立下載成兩個不同的檔案**。
    * 請分別解壓縮到不同的獨立資料夾中，切勿混在一起。
    * _(如果您只購買「移除反作弊」，則只需下載該單一檔案，並可直接忽略後續教學中的「內部輔助」部分)_

    <div align="left"><figure><img src="../.gitbook/assets/image (661).png" alt="SMD 移除反作弊 登入器下載" width="563"><figcaption></figcaption></figure></div>
{% endstep %}
{% endstepper %}

***

## 二、安裝與運行教學

請嚴格依照以下順序執行。步驟分為「階段一：內部輔助注入」**與**「階段二：移除反作弊與遊戲啟動」。

{% stepper %}
{% step %}
### 【階段一】內部輔助注入

{% hint style="info" %}
💡 注意：若您「只購買移除反作弊」，請直接跳到【階段二】
{% endhint %}

1.  **開啟並登入：** 打開內部輔助並輸入卡密登入。<mark style="color:$primary;">(只購買移除反作弊用戶可忽略)</mark>

    <div align="left"><figure><img src="../.gitbook/assets/image (662).png" alt="" width="231"><figcaption></figcaption></figure></div>
2.  **執行注入：** 點擊 **「加載」** 開始進行輔助注入。<mark style="color:$primary;">(只購買移除反作弊用戶可忽略)</mark>

    <div align="left"><figure><img src="../.gitbook/assets/image (663).png" alt="" width="327"><figcaption></figcaption></figure></div>
3.  **等待提示：** 當視窗出現 **`Waiting Valorant`** 字樣後，即代表內部輔助已準備就緒，請**不要關閉視窗**，接著進行【階段二】。

    <div align="left"><figure><img src="../.gitbook/assets/image (664).png" alt="" width="334"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### 【階段二】移除反作弊與遊戲啟動

#### 1. 配置密鑰檔案

在您存放「移除反作弊」程式的資料夾內，**按右鍵建立一個全新文字檔（TXT）**，並將該文字檔命名為 `key`（完整檔名即為 `key.txt`）。打開它，**輸入您的「移除反作弊卡密」並儲存檔案**。

<div align="left"><figure><img src="../.gitbook/assets/image (666).png" alt="" width="450"><figcaption></figcaption></figure></div>

> 📝 _提示：確保_ `key.txt` _與移除反作弊執行檔在同一個資料夾目錄下。_

#### 2. 開啟模擬器

雙擊打開 **「移除反作弊」** 登入器。此時系統會受到引導，**自動開啟 Riot Client**。

<div align="left"><figure><img src="../.gitbook/assets/image (667).png" alt="" width="344"><figcaption></figcaption></figure></div>

#### 3. 進入遊戲

Riot Client 開啟後，點擊 **「開始遊戲（Play）」** 並耐心等待遊戲載入，進入遊戲大廳。

<div align="left"><figure><img src="../.gitbook/assets/image (668).png" alt="" width="275"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
### 【階段三】遊戲內快捷鍵與對局流程（核心步驟）

#### <mark style="color:$danger;">進入遊戲大廳後，請嚴格遵守以下 F7 / F8 操作規範，</mark><mark style="color:$danger;">**頻繁或錯誤操作將會導致模擬失靈並引發封號**</mark><mark style="color:$danger;">。</mark>

```
[ 遊戲大廳 ] ➔ 按 F7 (加載偽裝) ➔ 開始匹配對戰 ➔ 遊戲結束回大廳 ➔ 按 F8 (安全卸載) ➔ 關閉遊戲重開
```

#### 步驟 1：匹配前按 F7 加載偽裝

當您在遊戲大廳**準備要開始匹配對戰時**（即使是拔場），請按下 **`F7`**。按下後系統會發出提示聲。

* 按下後，畫面上會跳出 **黃窗 / 綠窗**。
* 請耐心等待綠窗跑完並自動消失，且畫面右下角出現**成功提示**後，再正式開始點擊匹配對戰。

綠窗加載畫面:

<div align="left"><figure><img src="../.gitbook/assets/image (679).png" alt=""><figcaption></figcaption></figure></div>

綠窗完成畫面 (這個時候才可以匹配對戰):

<div align="left"><figure><img src="../.gitbook/assets/image (678).png" alt=""><figcaption></figcaption></figure></div>

* **💡 狀態辨識：**
  * **綠窗：成功，但要等右下角跳start match再開始匹配。**
  * **黃窗：** 代表輔助正在進行偽裝排隊中。
  * _例外處理：_ 如果列隊已經顯示 `queue 1` 但畫面上還是一直卡在黃框，請再補按一次 `F7`。

#### 步驟 2：對局結束回大廳按 F8 關閉與重啟

當一場完整的對局結束後回到遊戲大廳，請立即按下 **`F8`**。

* 按下後**等待 5 秒鐘**，然後關閉遊戲。
* <mark style="color:blue;">**每次下一把前，都必須重開模擬器＋重開遊戲**</mark><mark style="color:blue;">，重複上述的流程再次遊玩。</mark>

### ⚠️ 特別狀況處理：匹配時有人跳 Game（退回大廳）怎麼辦？

如果在選擇特務（英雄）時有人跳 Game，導致您被系統退回遊戲大廳並自動繼續匹配，請**立即取消匹配**，並依照時間判定處置：

* **距離第一次按下 F7 超過 5 分鐘：** 請再次按下 **`F7`**，等待綠窗消失後，重新開始尋找對戰。
* **距離第一次按下 F7 在 5 分鐘以內：** 請<mark style="color:$primary;">**完全關閉**</mark>《特戰英豪》及 RIOT 等相關所有程序，然後<mark style="color:$primary;">從頭由「步驟一」重新執行</mark>。
* ❌ **絕對警告：**<mark style="color:$danger;">**切記不能在短時間內頻繁按下 F7，否則會導致模擬失靈直接封號！**</mark>

### ⚠️ 特別狀況處理：出現102/5報錯 怎麼辦？

1. **先開模擬進去遊戲，SMD輔助等進入對戰後再開啟登入並注入。**
2. **準備兩隻帳號，一隻號玩完一場就先換號交替遊玩。**
3. **不要暴力或更加的演戲，吃舉報會加強收到102/5報錯可能。**
4. **(遇到102後再開遊戲立馬被踢處理辦法)**\
   當您遇到102/5報錯遊戲閃退時，必須先點F8直到移除反作弊的黑窗出現”ByeBye“後，不用關閉移除反作弊黑窗，直接手動**打開RIOT並**開遊戲，在**遊戲啟動的瞬間立馬按 F7**。
{% endstep %}
{% endstepper %}

***

## 三、日常功能與參數設定

* #### **🌟 內部輔助選單鍵：** **`F5`** (遊戲中按 F5 可呼叫或隱藏選單)



* **清理殘留（強烈建議）：** 執行工具前，請先下載並清理舊有環境。\
  👉 [點我前往下載：SMD 偽裝殘留刪除工具](https://mega.nz/file/TQdk0BCb#qQuduzbxw9Dhn8s-QXGMsR0hSkZei3FLNCPCYQm0fpo) _(下載後必須「右鍵以系統管理員身分開啟」)_
* **檢查伺服器狀態：** 請在開啟前確認伺服器是否正常運行。\
  👉 [點我前往：SMD 偽裝伺服器狀態檢查](https://sckmd.xyz/status/emulator/)



* **🌟 官方推薦參數下載：**
  * [點我下載：作者提供 - 穩定演戲參數](https://mega.nz/file/bYFgBAzI#xcXfS0enXj1_tw8QIOnahAJduf28kI_teFx5oVBa8lY)
  * [點我下載：作者提供 - 強大暴力參數](https://mega.nz/file/mIlVkALZ#AyhIWdBTsaYtf30xKbEbP-pmcg75I0BHqKWrtFk7i2o)

{% stepper %}
{% step %}
### 💾 參數儲存與載入教學

#### 1. 如何儲存當前設定

在遊戲中打開輔助選單 ➔ 點擊 **`CONFIG`** ➔ 點擊 **`Save Config`**。此時您的電腦桌面上會自動生成一張命名為 **`Config.png`** 的圖片檔案，這張圖片就是您當前的參數檔。

<div align="left"><figure><img src="../.gitbook/assets/image (680).png" alt=""><figcaption></figcaption></figure></div>

#### 2. 如何載入已有參數

將下載好或儲存好的參數圖片放置在**電腦桌面** ➔ 確認其檔名必須維持為 **`Config.png`** ➔ 在輔助選單內點擊 **`Load Config`**，輔助即會自動加載桌面該圖片內的參數。

#### 3. ⚠️ 參數檔案注意事項

* 請勿任意修改檔名（例如改成 `Config(1).png` 會導致無法讀取）。
* 桌面**同時只能存在一個**參數圖片檔案，以免輔助讀取衝突。
{% endstep %}
{% endstepper %}

***

## 四、常見問題與 102 / 5 報錯排解 (Troubleshooting)

遇到特戰英豪常見的 **102 / 5 錯誤代碼** 或遊戲閃退時，請透過以下防範機制與緊急處理辦法解決：

<details>

<summary>Q1：如何最大程度避免或降低 102/5 報錯機率？</summary>

* **防範對策 1（交替注入法）：** 先開啟模擬器直接進去遊戲大廳。此時先不注入 SMD 輔助，等到正式成功進入對戰局內後，再手動開啟 SMD 輔助登入器進行注入。
* **防範對策 2（雙號輪替法）：** 強烈建議準備至少兩隻帳號。一隻帳號玩完一場之後，不論輸贏都先換下一隻號，兩隻號交替遊玩能大幅降低系統檢測率。
* **防範對策 3（行為克制）：** 請務必演戲，切勿過度暴力擊殺。吃過多的玩家舉報（Report）會直接引發人工或系統針對性檢測，導致收到 102/5 報錯的可能大幅暴增。

</details>

<details>

<summary>Q2：遇到 102 報錯閃退後，重新開遊戲立馬又被踢出來，該怎麼辦？</summary>

* **原因分析：** 這是因為上一次的防作弊模擬殘留並被鎖定，需要進行「強制重洗注入」。
* **緊急應變處理步驟（必讀）：**
  1. 當遇到 102/5 報錯遊戲閃退時，**先不要關閉**當前移除反作弊的黑色主視窗。
  2. 在大廳或當前狀態下**連續按下 `F8`**，直到移除反作弊的黑窗畫面上出現 **`ByeBye`** 字樣。
  3. 出現 `ByeBye` 後，**依舊維持該黑窗開啟，不要關閉它**。
  4. 直接手動重新打開 Riot Client 並啟動《特戰英豪》。
  5. **關鍵動作：在遊戲畫面啟動（黑畫面或載入圖出現）的瞬間，立刻按下 `F7`。** 這樣就能完成緊急重洗，順利進入遊戲。

</details>
