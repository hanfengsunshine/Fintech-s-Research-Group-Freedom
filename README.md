# Fintech-s-Research-Group-Freedom
- http://vis.cse.ust.hk/groups/finvis/paper/survey.pdf <bar>
- https://www.kaggle.com/datasets?tags=11108-finance  <bar>
- https://etrading.jpmorganam.com.hk/mjfUsr/en/portfoliorisk/index.html
 - http://equalr.com/ 
  - http://cn.mikecrm.com/Q2sOt6r <bar>
 
 - https://www.jiqizhixin.com/articles/2017-11-21-3
 Exploiting Topic based Twitter Sentiment for Stock Prediction \
 
- https://www.sciencedirect.com/science/article/pii/S1084804517303247 survey   


https://lbezone.ust.hk/pdfviewer/web/viewer.php?file=aHR0cHM6Ly9sYmV6b25lLnVzdC5oay9vYmovMS9vLzk5MTAxMjY1NTY2OTIwMzQxMi85OTEwMTI2NTU2NjkyMDM0MTIucGRm#page=1  Dual-Curve Term Structure Models for Post-Crisis Interest Rate Derivatives Markets      



#### Websocket notes   
https://www.hotbak.net/key/%E4%B8%80%E6%A3%80%E6%B5%8B%E6%B5%8F%E8%A7%88%E5%99%A8%E6%98%AF%E5%90%A6%E6%94%AF%E6%8C%81websocket%E7%BD%91.html    
http://www.195440.com/1223             
https://intermediate-and-advanced-software-carpentry.readthedocs.io/en/latest/multiprocessing.html    
https://www.linuxidc.com/Linux/2019-02/156793.htm         
https://blog.csdn.net/mlj1668956679/article/details/38044369         
https://www.npmjs.com/package/jquery-simple-websocket     

https://stackoverflow.com/questions/14454949/how-to-add-more-headers-in-websocket-python-client   
https://blog.csdn.net/LOVELONG8808/article/details/52212566       
   
## broker apps 
![南华](https://www.nanhua.net/nanhuatech/download/PythonGo%E7%AD%96%E7%95%A5%E5%BC%80%E5%8F%91%E6%96%87%E6%A1%A3_Ver20180816.pdf)  

1.1 tick行情和快照行情    

tick行情又称逐笔行情，是整个市场上的逐笔数据。例如投资者一笔新的委托会形成一笔行情，交易所撮合一笔新的成交也会形成一笔行情。tick行情记录了市场的每一个事件的数据，是最精细和完整的数据。   

快照行情又称切片(snapshot)行情，如其名，是对tick行情数据的某一个时刻的切片数据。例如现在常见的期货500ms一笔的行情，就是每500ms，在这时间段内的最高价、最低价、成交量等汇总成的一笔快照行情。  

1.2 level1行情和level2行情   

level1行情又称1档行情或基本行情，字面意义上是指行情报单簿的档位只有一档，即买一价，卖一价。实际应用中一般用来指比较基础的一种行情，只包含最低层次的买卖，成交数据，更新频次也是最低。   
    
level2行情又称多档行情或者深度行情，可以认为是level1行情的升级版，体现在报单簿档位会多，数据丰富，或者更新频次更快。这种行情一般是要单独收费的。        

数据量 = 切片频率 * 单个切片数据量 
单个切片数据量 = 常数 * 品种数量500毫秒一个切片是期货市场行情。      
期货市场品种也就百把个，股票市场品种有几千个，切片时间是3秒。单位时间的数据量差别是很大的。再就是看策略本身，超高频的策略会有毫秒级别的要求。如果只是普通短线交易，没有那么追求极致。        




