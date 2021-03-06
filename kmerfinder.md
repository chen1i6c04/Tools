# KmerFinder 使用說明

本說明介紹如何在 Linux系統中使用KmerFinder分析菌株的菌種

## 開啟終端機

 1. 在空白處點擊右鍵，開啟右鍵選單
 2. 選擇 **在此處開啟終端機**

## 使用方式
```
在終端機中輸入：
kmerfinder_cmd.py [參數]

參數：
	-i 輸入文件的路徑
	-o 分析結果的儲存路徑
```

### 範例

```
kmerfinder_cmd.py -i file.fa -o outfolder
```

```
kmerfinder_cmd.py -i infolder -o outfolder
```

### 注意事項

 - 若要分析的檔案有兩個以上，請將檔案彙整為一個資料夾，在 ``-i`` 輸入資料夾路徑
 - 複製資料夾並在終端機中貼上，即可獲得**資料夾路徑**
 - 終端機不接受快捷鍵指令，請使用滑鼠貼上

## 分析報告

各檔案的分析結果會儲存在參數``-o``所輸入的路徑下







<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA4MTQzMzAxNV19
-->