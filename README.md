# Minecraft server ELK analysis
### 解析 MINECRAFT SERVER LOG 及 LINUX 防火牆並進行交叉比對，鎖定網路攻擊來源。
:technologist: Data Engineer  
<br>

![minecraft1](https://user-images.githubusercontent.com/106952571/187556288-34dbcfee-586f-4fef-9f58-f055b48bae18.jpg)
![minecraft2](https://user-images.githubusercontent.com/106952571/187556296-28a7b9c9-e38a-45e8-abdd-a173bb02b3fc.jpg)
![osufw1](https://user-images.githubusercontent.com/106952571/187556303-53d70a83-3b4a-40f7-9521-a05fe5f132c3.jpg)
![osufw2](https://user-images.githubusercontent.com/106952571/187556307-1e93ec99-9551-40bf-9431-8107d1008bf9.jpg)
![cross analysis3](https://user-images.githubusercontent.com/106952571/187556315-212154ff-c3b9-4659-8fac-c3feeacb6f73.jpg)
## ELK stack
[![IMAGE ALT TEXT](http://img.youtube.com/vi/hPOUUwBsmsw/0.jpg)](https://www.youtube.com/watch?v=hPOUUwBsmsw "ELK stack")

## Skills
:wrench: Filebeat 監聽系統路徑並讀取伺服器 Log    
:wrench: Logstash 解析日誌並提取時間訊息作為時間戳記  
:wrench: Elasticsearch Mapping 後儲存索引  
:wrench: Kibana 進行資料視覺化、製作 Dashboard 交叉分析  
