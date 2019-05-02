# ANTUSD 情緒字典

每一列都包含七個欄位的資料：

1. 詞
2. 機器分數
3. 正面標記數
4. 中立標記數
5. 負面標記數
6. 非意見詞標記數
7. 非詞標記數


## 欄位說明

1. 詞

  目前資料所屬的中文詞彙。

2. 機器分數

  CopeOpi 系統所自動產生出的詞意見分數，分數範圍介於 -1 至 1 之間，-1 是最 `負面`，1 是最 `正面`。

  > CopeOpi 請見：
  >
  > Ku, Lun-Wei, Ho, Xiu-Wei and Chen, Hsin-Hsi, "Opinion Mining and Relationship Discovery Using CopeOpi Opinion Analysis System," Journal of American Society for Information Science and Technology, volume 60, number 7, pages 1486-1503, July 2009.

3. 正面標記數

4. 中立標記數

5. 負面標記數

6. 非意見詞標記數

  以上四個欄位記錄在所收集與標記的各項語料中，目前這個詞彙曾被不同標記者標為 `正面` / `中立` / `負面` / `非意見詞` 的次數。

7. 非詞標記數

  由於語料標記前皆先由斷詞系統進行斷詞，因此可能出現錯誤，此欄位記錄在所收集與標記的各項語料中，目前這個詞彙曾被標記為不是一個中文詞的次數，可用來協助校正斷詞錯誤。
