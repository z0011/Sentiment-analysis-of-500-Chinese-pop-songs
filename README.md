# Sentiment-analysis-of-500-Chinese-pop-songs
NTU 107-1 EE Computer Programming final project
__Team 24__
__Team member__ :  
b05207045 心裡三 張倚郡  
b07901166 電機一 程騰緯<br/> 
![image](https://github.com/nba556677go/eecp_final_four_bar_linkage/blob/master/graph.PNG)  
__環境__:   
Windows 10  
Anaconda python 3.7.0
__套件__:   
SnowNLP(https://github.com/isnowfy/snownlp)

__簡介__:  
    -含三個demo檔分別展示 __a.__歌曲蒐集 __b.__歌曲情緒座標建立 __c.__播放介面建立，執行方式如下:  
    <br/>
    1.  __demo_1.py__  
        >直接執行"python3 demo_1.py"   
        >於"Enter XXX(non grashoff桿長參考/grashoff桿長參考)"處分別輸入四根桿長，畫出運動模型   
        >輸入桿長參考:    
        >Non Grashoff: input/coupler/output/frame = 100/200/200/350     
        >Grashoff: input/coupler/output/frame = 100/250/300/200 
        <br/>  
    2. __demo_2_pos.py__   
        >直接執行"python3 demo_2_pos.py"  
        >秀出筆在0.25 , 0.5, 0.75倍coupler的位置圖  
         <br/>  
    3.__demo_3_speed.py__   
        >直接執行"python3 demo_3_speed.py"  
        >秀出筆在0.5倍coupler之位置圖，速度，加速度  
         <br/>  
    4.__demo_4_period.py__  
        >直接執行"python3 demo_4_period.py"   
        >在 "please type in Time period:" 處輸入希望幾秒轉完一圈(因週期太大可能在求加速度時xy軸繪圖時shape對不起來，建議取在1-10的數字)   
        >在"please type in pen type (coupler/center)"處填入希望的筆位置(center意指筆不在coupler上，而是在coupler上多加的三角結構中心，若希望與其他demo圖形相同結構，請輸入coupler)   
        >秀出筆在0,0.1,0.2 ... ,1倍coupler之位置圖，速度，加速度    
         <br/>  
__分工表__:  
    1.電機四 b04507025 韓秉勳:軌跡，速度，加速度程式實作，github設置  
    2.機械四 b04502076 賴昶亙:物理公式推導，公式程式實作，demo主講
    
