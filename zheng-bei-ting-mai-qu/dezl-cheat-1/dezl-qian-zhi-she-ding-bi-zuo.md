---
description: 不照教學做 導致無法使用 請不要來開單反應
---

# Dezl 前置設定(必做)

## 一、安裝微軟套件

### 下載連結：(請兩個都下載並安裝)

1. [https://aka.ms/vs/17/release/vc\_redist.x86.exe ](https://aka.ms/vs/17/release/vc_redist.x86.exe)
2. [https://aka.ms/vs/17/release/vc\_redist.x64.exe](https://aka.ms/vs/17/release/vc_redist.x64.exe)

## 二、檢查系統資訊

{% content-ref url="../../instruction/preparation/step3.md" %}
[step3.md](../../instruction/preparation/step3.md)
{% endcontent-ref %}

## 三、關閉防毒(以Windows內建防毒為例)

{% embed url="https://www.youtube.com/watch?v=yN8a7ZDQXUs" %}

{% hint style="info" %}
### 關閉防毒工作下載：[點我下載](https://mega.nz/file/qnRnzRxD#Cqboicr01lr5QQFgk4bv2pGq3qJ6s1xahGR5L4fo32o)
{% endhint %}

## 四、核心隔離(HVCI)開啟

<figure><img src="../../.gitbook/assets/image (516).png" alt=""><figcaption></figcaption></figure>

## 五、核心DMA保護開啟

### 從這邊快速查看

<figure><img src="../../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

#### 首先進入BIOS後找到 Advanced (進階) 選單。

#### 把<mark style="color:red;">VT-d 或 IOMMU</mark>從Disabled改成Enabled&#x20;

#### 按下鍵盤上的 F10，選 Yes 並退出
