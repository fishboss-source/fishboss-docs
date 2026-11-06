# 模型載入與畫面擷取設定

## CGC NANO 模型載入與畫面擷取設定

請依照實際取得的遊戲模型資訊設定

這是最重要的設定頁，直接影響辨識效果。

點左側選單的 **擷取**。

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040001.png" alt=""><figcaption></figcaption></figure>

***

### 1. 畫面擷取設定

**設定範例（非所有設備通用推薦）：**

| 項目       | 建議值                 | 說明                    |
| -------- | ------------------- | --------------------- |
| 擷取方式     | **DXGI 桌面複製**       | 是否較穩定依硬體及實測而定         |
| 寬度 / 高度  | 依模型輸入尺寸（常見 320×320） | 應核對模型要求，勿預設皆為 320×320 |
| 擷取上限 FPS | 120 或 **0**（不限制）    | 初稿如此描述，待實測確認          |
| 信賴度      | 0.5                 | 過低會有更多誤判，過高容易漏判       |
| NMS 閾值   | 0.45                | 控制重疊框過濾               |
| 指定區域     | 通常關閉                | 需要只擷取特定區域時再開          |

***

### 2. 載入模型

#### 選擇模型檔案

點「模型檔案」右側的資料夾圖示，會開啟檔案選擇視窗。

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040029.png" alt=""><figcaption></figcaption></figure>

「模型」資料夾：

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 040040.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/螢幕擷取畫面 2026-11-05 195255.png" alt=""><figcaption></figcaption></figure>

選擇對應的模型檔（`.cgckite` 或 `.onnx`）：

> **提示**：`.cgckite` 為已編譯/加密模型，載入效能與穩定性待實測確認。\
> 若直接載入 `.onnx`，是否自動轉換待實測確認。

#### 設定模型系列與

### <mark style="color:$danger;">載入模型後，務必選擇正確的</mark> <mark style="color:$danger;"></mark><mark style="color:$danger;">**模型系列**</mark>：

<figure><img src="../../.gitbook/assets/image (690).png" alt=""><figcaption></figcaption></figure>

常見系列包含：

* YOLO v5 / v7 / v8 / v10 / v11 / v12 / v26 等

**模型精度**：

* #### `FP16`：速度快 低負擔<mark style="color:$success;">(推薦)</mark>
* `FP32`：使用不同數值精度，效果依模型而異

設定完成後，點右下角 <mark style="color:$success;">**套用並儲存**</mark>。確認畫面保留所選模型；是否成功推論需啟動後觀察日誌。

#### [**下一步：** 移動輸出方式設定。](yi-dong-shu-chu-fang-shi-she-ding.md)
