# [電子數據取證與Python方法](https://www.tenlong.com.tw/products/9787121321313) Python forensics
```
第1章為何使用Python進行取證
1.1本章簡介
1.2網絡空間犯罪調查的挑戰
1.3Python編程環境如何有助於應對這些挑戰
1.3.1Python的全球支持
1.3.2開源和平台獨立性
1.3.3生命週期定位
1.3 .4入門的成本和限制
1.4Python與多伯特（Daubert）證據標準
1.5本書的組織結構
1.6章節回顧
1.7問題小結
1.8補充資料

第2章建立一個Python取證環境
2.1本章簡介
2.2搭建一個Python取證環境
2.3正確的環境
2.4選擇一個Python版本
2.5在Windows上安裝Python 
2.6Python包和模塊
2.6.1Python標準庫
2.7標準庫包含什麼
2.7.1內建函數
2.7.2hex（）和bin（）
2.7.3range（）
2.7.4其他的內建函數
2.7.5內建常量
2.7.6內建類型
2.7.7內建異常
2.7.8文件和目錄訪問
2.7.9數據壓縮和歸檔
2.7.10文件格式
2.7.11加密服務
2.7.12操作系統服務
2.7.13標準庫小結
2.8第三方包和模塊
2.8.1自然語言工具包（NLTK）
2.8.2Twisted matrix（TWISTED）
2.9集成開發環境
2.9.1有哪些選擇
2.9.2運行於Ubuntu Linux上的Python 
2.10移動設備上的Python 
2.10.1iOS中的Python應用
2.10.2Windows 8 Phone 
2.11虛擬機
2.12章節回顧
2.13問題小結
2.14接下來講什麼
2.15補充資料

第3章第一個Python取證應用程序
3.1本章簡介
3.2命名慣例和其他考慮
3.2.1常量
3.2.2本地變量名
3.2.3全局變量名
3.2.4函數名
3.2.5對象名
3.2.6模塊
3.2.7類名
3.3第一個應用程序“單向文件系統哈希” 
3.3.1背景
3.3.2基本需求
3.3.3設計中的考慮
3.3.4程序結構
3.4代碼遍歷
3.4.1檢查Main—代碼遍歷
3.4.2ParseCommandLine（）
3.4.3ValidatingDirectoryWritable 
3.4.4WalkPath 
3.4.5HashFile 
3.4.6CSVWriter 
3.4.7pfish.py完整代碼清單
3.4.8_pfish.py完整代碼清單
3.5結果展示
3.6章節回顧
3.7問題小結
3.8接下來講什麼
3.9補充資料

第4章使用Python進行取證搜索和索引
4.1本章簡介
4.2關鍵字上下文搜索
4.2.1如何用Python輕鬆完成
4.2.2基本需求
4.2.3設計考慮
4.3代碼遍歷
4.3.1分析Main——代碼遍歷
4.3. 2分析_p—search函數——代碼遍歷
4.3.3分析ParseCommandLine 
4.3.4分析ValidateFileRead（theFile）
4.3.5分析SearchWords函數
4.4結果展示
4.5索引
4.6編寫isWordProbable 
4.7p—search完整代碼清單
4.7.1p—search .py 
4.7.2_p—search.py 
4.8章節回顧
4.9問題小結
4.10補充資料

第5章證據提取（JPEG和TIFF）
5.1本章簡介
5.2Python圖像庫（PIL）
5.3代碼遍歷
5.3.1Main程序
5.3.2logging類
5.3.3cvs處理器
5.3.4命令行解析器
5.3 .5EXIF和GPS處理器
5.3.6檢查代碼
5.3.7完整代碼清單
5.3.8程序的執行
5.4章節回顧
5.5問題小結
5.6補充資料

第6章時間取證
6.1本章簡介
6.2給這個環節添加時間
6.3時間模塊
6.4網絡時間協議
6.5獲得和安裝ntp庫ntplib 
6.6全世界的NTP服務器
6.7NTP客戶端創建腳本
6.8章節回顧
6.9問題小結
6.10補充資料

第7章在電子取證中使用自然語言工具
7.1什麼是自然語言處理
7.1. 1基於對話的系統
7.1.2語料庫
7.2安裝自然語言工具包和相關的庫
7.3使用語料庫
7.4用NLTK進行實驗
7.5從因特網上創建語料庫
7.6NLTKQuery應用程序
7.6.1NLTKQuery.py 
7.6.2_classNLTKQuery.py 
7.6.3_NLTKQuery.py 
7.6.4NLTKQuery例子的執行
7.6.5NLTK跟踪執行
7.7章節回顧
7.8問題小結
7.9補充資料

第8章網絡取證：第1部分
8.1網絡調查基礎
8.1.1什麼是套接字
8.1.2最簡單使用套接字的網絡客戶端和服務器連接
8.1.3server.py的代碼
8.1.4client.py的代碼
8.1.5server.py和client.py程序的執行
8.2隊長雷繆斯：再次核實我們到目標的射程…僅需一個PING 
8.2.1wxPython 
8.2.2ping.py 
8.2.3guiPing.py的代碼
8.2.4ping掃描的執行
8.3端口掃描
8.3.1公認端口的例子
8.3.2註冊端口的例子
8.4章節回顧
8.5問題小結
8.6補充資料

第9章網絡取證：第2部分
9.1本章簡介
9.2數據包嗅探
9.3Python中的原始套接字
9.3.1什麼是混雜模式或監控模式
9.3.2Linux下Python中的原始套接字
9.3.3對緩衝區進行解包
9.4Python隱蔽式網絡映射工具（PSNMT）
9.5PSNMT源代碼
9.5.1psnmt.py源代碼
9.5.2decoder.py源代碼
9.5.3commandParser.py源代碼
9.5.4classLogging.py源代碼
9.5.5csvHandler.py源代碼
9.6程序的執行和輸出
9.6.1取證日誌
9.6.2CSV文件輸出實例
9.7章節回顧
9.8問題小結
9.9補充資料

第10章多進程的取證應用
10.1本章簡介
10.2何謂多進程
10.3Python多進程支持
10.4最簡單的多進程例子
10.4.1單核的文件搜索方案
10.4.2多進程的文件搜索方法
10.5多進程文件哈希
10.5.1單核方案
10.5.2多核方案A 
10.5.3多核方案B 
10.6多進程哈希表生成
10.6.1單核口令生成器代碼
10.6.2多核口令生成器
10.6.3多核口令生成器代碼
10.7章節回顧
10.8問題小結
10.9補充資料

第11章云中的彩虹表
11.1本章簡介
11.2在雲端工作
11.3雲端服務的可選資源
11.4在雲端創建彩虹表
11.4.1單核彩虹表
11.4.2多核彩虹表
11.5口令生成計算
11.6章節回顧
11.7問題小結
11.8補充資料

第12章展望
12.1本章簡介
12.2由此我們將走向何方
12.3結束語
12.4補充資料
```
