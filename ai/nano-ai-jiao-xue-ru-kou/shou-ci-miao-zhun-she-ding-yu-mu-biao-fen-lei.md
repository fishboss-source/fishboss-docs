# 首次瞄準設定與目標分類

## CGC NANO 首次瞄準設定與目標分類

此篇以首次操作必備項目為主；各項精細數值的單位、範圍與適用模型仍待實測，不宜直接把範例值當成通用最佳設定。

點左側選單的 **瞄準**，這裡是整個瞄準邏輯的核心。

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040508.png" alt=""><figcaption></figcaption></figure>

***

### 1. 新增瞄準按鍵

進入瞄準頁後，先點右上角 **新增按鍵**：\
按下任意按鍵後就會自動綁定熱鍵\
新增後會出現按鍵卡片（例如「滑鼠左鍵」）：

可在此設定：

* 觸發鍵
* 啟用開關
* 生效規則（例如「最後按下優先」）

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040525.png" alt=""><figcaption></figcaption></figure>

***

### 2. 控制參數（X 軸 / Y 軸）

在「控制參數」分頁可調整：

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040544.png" alt=""><figcaption></figcaption></figure>

| 參數  | 說明       |
| --- | -------- |
| 回應  | 瞄準反應速度   |
| 預測  | 目標移動預測強度 |
| 軟啟動 | 啟動時的平滑程度 |

X 軸與 Y 軸可分別調整。

***

### 3. 瞄準範圍與目標追蹤

往下捲動可看到：

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040553.png" alt=""><figcaption></figcaption></figure>

重要參數：

* **最大範圍 X / Y**：瞄準有效區域上限
* **最小範圍 X / Y**：過近時的過濾
* **無目標恢復（毫秒）**：失去目標後多久恢復
* **轉火延遲**：切換目標時的延遲時間

***

### 4. 類別設定（非常重要）

點「類別設定」分頁：

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040606.png" alt=""><figcaption></figcaption></figure>

#### <mark style="color:$success;">系統會自動讀取模型的所有類別（例如特戰</mark> <mark style="color:$success;"></mark><mark style="color:$success;">`0·0`</mark><mark style="color:$success;">、</mark><mark style="color:$success;">`1·1`</mark><mark style="color:$success;">區分敵人和隊友)</mark>

可調整項目：

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040726.png" alt=""><figcaption></figcaption></figure>

| 項目       | 說明                                     |
| -------- | -------------------------------------- |
| 參與瞄準     | 開關該類別是否被瞄準                             |
| 優先順序     | 優先級數字方向待實測確認                           |
| **X 位置** | 瞄準點水平偏移（0.5 = 中心）                      |
| **Y 位置** | 瞄準點垂直偏移（0.5 為初稿標示的中心值；實際方向應以模型標註與實測為準） |

> **實用技巧**：\
> **待確認**：不同模型的類別和 X／Y 座標方向可能不同，勿直接套用其他模型的瞄準位置數值。

***

### 5. 套用並儲存

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040742.png" alt=""><figcaption></figcaption></figure>

所有調整完成後，務必點右下角 **套用並儲存**：

未儲存的變更會顯示「有未儲存變更」提示。儲存後請確認提示已消失。

#### [**下一步：** 啟動與狀態確認。](nano-qi-dong-yu-zhuang-tai-que-ren.md)
