# Balancing SRTG 1: 阻擋攻擊 Blocking Attack

## 中心 Centre

防護網 > 手榴彈   
炸彈 > 防護網    
手榴彈 > 炸彈    

Shield > Grenade    
Bomb > Shield   
Grenade > Bomb    

物件防護網 > 攻擊物件    
攻擊物件 > 防護網    
防護網 > 攻擊基地    
攻擊基地 > 能量值 (物件防護網)    

Object Shield > attack Object   
attack Object > Shield    
Shield > attack Base    
attack Base > Hp (Object Shield)    

**例子 Examples**   
3A > 5A   
5A > 3P’ (Object Shield)    
3P’ > 3A    

3P’ 3P’ > 3A 3A   
3A 5A > 3P’ 3P’   
3A 3A > 3A 5A   

3P’ 5A > 3A   
3A 3A > 3P’ 5A    

***

## 設計圖 Blueprints

1. 石頭 1A (d=2) Stone
2. 手榴彈 3A Grenade
3. 防護網 3P Shield
4. 物件防護網 3P Object Shield
5. 炸彈 5A/3 Bomb
<br>
10. 迫擊炮 2A/2 (d=2) Mortar   
11. 改良迫擊炮 4A/3 (d=2)    
12. 榴彈炮 3A/3 (d=3) Howitzer   
13. 維修箱 1Hp Repair Box    
14. 維修桌 3Hp Repair Desk   
15. 防護場 1P Protecting Field     
<br>
20. 物件防護場 1P object protecting field    

維修箱 0(P)/1
你可令任意角色回復 1(Hp)。
You may retrieve one character 1(Hp).

維修桌 0(P)/2
你可令：
距離為一的角色回復 3(Hp)，或
距離為二的角色回復 2(Hp)，或
距離為三的角色回復 1(Hp)。
You may retrieve one character 3(Hp) with d=1; or 2(Hp) with d=2; or 1(Hp) with d=3.

防護場 1(P)/1
任何時候，你可生產此物件。
You may produce this object at any instant.

物件防護場 1(P)/1
描述與防護場相同。
Its description is the as same as Protecting Field.
————————
基地表 Base List

* 特朗普基地 
* 金正恩基地
* 維修基地
* 鍊金術基地
* 倉庫基地
* 突擊基地
* 火藥基地
* 聯網基地

特朗普基地
你棄掉 1(W)，無視一個物件的完成標記，直至該角色回合結束。

金正恩基地
你的物件完成後不用宣告。

維修基地
你棄掉 2(W)，任意一個基地回復 3(Hp)。

鍊金術基地
你棄掉一個物件，將其資源置回倉庫。

倉庫基地
生產階段，你可使用 5(W)。若如此做，其中一條生產線最多可置上 2(W)。

突擊基地
生產階段，每條生產線最多可置上 2(W)。

火藥基地
行動階段限一次。你棄掉 2(W)，對距離為一的角色作出 3(A) 攻擊。

聯網基地
你的防護網可當作物件防護網。






Base List
* Trump Base
* Kim Jong-un Base
* Repair Base
* Alchemy Base
* Storage Base
* Raid Base
* Powder Base
* Joint Shield Base

Trump Base
You discard 1(W), ignore one completed indicator of an object, until end of turn of that current character.

Kim Jong-un Base
No completed indicators have to place when your object is completed.

Repair Base
You discard 2(W), one arbitrary base retrieve 3(Hp).

Alchemy Base
You discard one object, take its resource back to storage.

Storage Base
In the production stage, you may place 5(W). If so, one of pipelines can place 2(W).

Raid Base
In the production stage, place at most 2(W) in each pipeline.

Powder Base
Do once only in the action stage. You discard 2(W), give 3(A) attack to a character with distance within 1.

Joint Shield Base
Your Shield may treat as Object Shield. 
