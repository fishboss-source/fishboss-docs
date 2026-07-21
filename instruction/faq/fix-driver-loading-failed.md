# 輔助驅動載入失敗解決辦法

## <mark style="color:$primary;">第一步 關閉安全開機(後續會啟用)</mark>

### 因每個主機板不同進入bios後的設定話會有差異(這邊用華碩來示範)  **1.電腦開機後，立刻按壓鍵盤上的“delete”鍵，進入BIOS \[Advanced Mode]**

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 203121.png" alt=""><figcaption></figcaption></figure>

#### **2.點選\[Boot]頁面**

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 203142.png" alt=""><figcaption></figcaption></figure>

**3.點選\[Secure Boot]選項**

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 203328.png" alt=""><figcaption></figcaption></figure>

#### **4. OS Type選項Default設置為Other OS** <mark style="color:$danger;">**Other OS:安全開機狀態關閉**</mark>**&#x20;**<mark style="color:$success;">**Windows UEFI mode:安全開機狀態開啟**</mark>

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 203547.png" alt=""><figcaption></figcaption></figure>

#### **5.儲存後開機 下載工具** [https://mega.nz/file/C2wXkYQS#7gahyuDtsmqPA1xRGJBffy9cVAvidpFfBgQfiT0cWUo](https://mega.nz/file/C2wXkYQS#7gahyuDtsmqPA1xRGJBffy9cVAvidpFfBgQfiT0cWUo)<br>

#### 6.下載後解壓縮到桌面並打開工具

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 204513.png" alt=""><figcaption></figcaption></figure>

#### **7.點選ESP>EFI>Microsoft>Boot>CIPolicies>Active**

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 204550.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 204649.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 204808.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 204822.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 204829.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 204837.png" alt=""><figcaption></figcaption></figure>

#### **8.將開**<mark style="color:$success;">**頭有8f**</mark><mark style="color:$danger;">**尾數e3**</mark>**的檔案刪除**

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-24 175940.png" alt=""><figcaption></figcaption></figure>

<div align="left"><figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 205339.png" alt=""><figcaption></figcaption></figure></div>

#### **9.刪除後重開機到bios開啟安全開機**

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-05-27 205448.png" alt=""><figcaption></figcaption></figure>

#### **保存後開機**

## 完成
