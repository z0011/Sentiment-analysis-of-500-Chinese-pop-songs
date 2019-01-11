# Sentiment-analysis-of-500-Chinese-pop-songs
NTU 107-1 EE Computer Programming final project  
__Team 24__  
__Team member__ :  
b05207045 心裡三 張倚郡  
b07901166 電機一 程騰緯<br/> 
![image](https://github.com/z0011/Sentiment-analysis-of-500-Chinese-pop-songs/blob/master/graph.PNG)  
__環境__:   
Windows 10  
Anaconda python 3.7.0
__套件__:   
SnowNLP(https://github.com/isnowfy/snownlp)  
__訓練資料來源__:  
CVAW (http://nlp.innobic.yzu.edu.tw/resources/cvaw.html)  
__簡介__:  
    -含三個demo檔分別展示 __a.__歌曲蒐集 __b.__歌曲情緒座標建立 __c.__播放介面建立，執行方式如下:  
    <br/>
    a.  __crawler.py__  
        >直接執行"python3 demo_1.py"   
        >於"Enter XXX(non grashoff桿長參考/grashoff桿長參考)"處分別輸入四根桿長，畫出運動模型   
        >輸入桿長參考:    
        >Non Grashoff: input/coupler/output/frame = 100/200/200/350     
        >Grashoff: input/coupler/output/frame = 100/250/300/200 
        <br/>  
    b. __analysis.py__   
        >直接執行"python3 demo_2_pos.py"  
        >秀出筆在0.25 , 0.5, 0.75倍coupler的位置圖  
         <br/>  
    c.__demo_3_speed.py__   
        >直接執行"python3 demo_3_speed.py"  
        >秀出筆在0.5倍coupler之位置圖，速度，加速度  
         <br/>  
         
__分工表__:  
    1.b05207045 心理三 張倚郡: crawler.py、analysis.py撰寫、github設置、ppt製作、demo主講  
    2.b07901166 電機一 程騰緯: gui.py撰寫、影片製作
    
