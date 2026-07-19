# 藍屏

1. 您的 BIOS模式 必須設定為 UEFI。
2. 修復/驗證遊戲檔案(需先關閉遊戲和輔助)
3. 停用 Hyper-V -> 以管理員身分執行 CMD 並鍵入下列命令：

```
bcdedit /set hypervisorlaunchtype off
```
