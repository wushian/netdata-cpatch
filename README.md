# netdata 繁體中文化檔

本更新檔以台灣中文資訊用語為主，基於 v1.12 修改。  
    
netdata 是非常實用且即時的效能監視套件，對於每項效能指標不僅標示用途，更詳細說明造成的原因以及影響，只可惜這麼棒的說明全都是英文，所以有了這個專案的產生。
  
&nbsp;&nbsp;
&nbsp;&nbsp;

## 使用說明

請將這四個檔案下載後，覆蓋至以下路徑。

  /usr/share/netdata/web/dashboard_info.js   
  /usr/share/netdata/web/dashboard.js   
  /usr/share/netdata/web/main.js   
  /usr/share/netdata/web/index.html   
    
覆蓋完成後請檢查檔案擁有者與群組是否為 netdata:netdata，若不是請使用 `chown netdata:netdata 檔名` 調整。


完成後，請重新整理網頁，或 Chrome 無效請結束所有 Chrome process 再重新開啟。
  

&nbsp;&nbsp;
&nbsp;&nbsp;

      
## 畫面範例


#### 繁體中文後介面
&nbsp;&nbsp;
系統概觀
![image](https://raw.githubusercontent.com/jasoncheng7115/netdata-cpatch/master/screenshot_01.png)
&nbsp;&nbsp;
&nbsp;&nbsp;

&nbsp;&nbsp;
KSM & NUMA
![image](https://raw.githubusercontent.com/jasoncheng7115/netdata-cpatch/master/screenshot_02.png)
&nbsp;&nbsp;
&nbsp;&nbsp;

&nbsp;&nbsp;
容器
![image](https://raw.githubusercontent.com/jasoncheng7115/netdata-cpatch/master/screenshot_03.png)
&nbsp;&nbsp;
&nbsp;&nbsp;


&nbsp;&nbsp;
設定
![image](https://raw.githubusercontent.com/jasoncheng7115/netdata-cpatch/master/screenshot_04.png)
&nbsp;&nbsp;
&nbsp;&nbsp;

