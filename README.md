# APDL_FOPLP_Debonding
## 程式碼核心介紹
### 🥑 論文題目  (交通大學 機械系固體力學組 林枋萭)
探討扇出型面板級封裝結構離型取下之機械行為  
Investigating Mechanical Behaviors of Fan-Out Panel Level Packaging Structures during De-bonding  
此處分享2.2.3節銅柱子模型應用，其他章節暫未公開  
### 使用語言
ANSYS APDL v16.0
### 合作單位
工研院產學合作  
## 實際應用
應用主模型-子模型技術分析複雜的封裝結構的應力與脫層行為  
![image](https://github.com/EureCalla/APDL_FOPLP_Debonding/blob/main/img01.png)
![image](https://github.com/EureCalla/APDL_FOPLP_Debonding/blob/main/img02.png)
### 流程圖
![image](https://github.com/EureCalla/APDL_FOPLP_Debonding/blob/main/流程.png)
## 資料介紹
main.txt 主程式碼     
global_model.txt 建立等效主模型  
sub_model.txt 建立子模型(導角鋁pad子模型)  
get_GT.txt 求解完後處理，計算破壞韌性  
