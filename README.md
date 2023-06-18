# cathyBK_DataEnginner_quiz
國泰銀行 -- 資料科學工程師考題  
程式語言: Python   
data:  https://drive.google.com/drive/folders/17dZ0KMLadqqnlc6dRUmevBx0sq9DAQ5-?usp=drive_link  
output(result):  
[filter.csv](https://drive.google.com/file/d/1HZDWtrKPnzph9b3brmdZtExQMikoIanV/view?usp=drive_link)  
[count.csv](https://drive.google.com/file/d/1u9BObKA23wn7PyOLmPJkTkN3bYEQ5fPo/view?usp=drive_link)  


1. 不限制方式下載【內政部不動產時價登錄網】中，【106年第1季】~【109年第4季】、位於【臺北市/新北市/高雄市】的
【不動產買賣】資料，【桃園市/臺中市】的【預售屋買賣】資料，下載檔案格式選擇【CSV格式】，請選擇【非本期下載】。
2. 使用【Pandas】，讀取所有檔名【?_lvr_land_? 】的資料集，分別建立dataframe物件，設定以【第二列英文】做為
dataframe欄位標頭，並新增欄位【df_name】(內容請用程式將資料補齊，例如: 106年第1季/新北市/不動產買賣-> 106_1_F_A、
107年第2季/台中市/預售屋買賣-> 107_2_B_B)。
3. 操作dataframe物件，將所有物件合併成【df_all】。
4. 以下列條件從【df_all】使用【Pandas】篩選/計算出結果，並分別輸出【csv 檔案】:
• filter.csv
ü 【主要用途】為【住家用】
ü 【建物型態】為【住宅大樓】
ü 【總樓層數】需【大於等於十三層】
• count.csv
ü 計算【總件數】
ü 計算【總車位數】
ü 計算【平均總價元】
ü 計算【平均車位總價元】
5. 將以上題目【2】【3】【4】之處理流程，透過【Airflow】建立起整體workflow。

繳交內容與方式
• 請準備簡報，呈現以下內容：
1. 簡述實作架構與過程說明
2. 簡述Airflow 的概念
3. 過程中遇到的問題與解決方法
• 請將包含註解的.py專案程式碼，上傳至個人github，並提供連結。




