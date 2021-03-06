# 設計圖及角色: 第三版新增規則
![CI status](https://img.shields.io/badge/Star%20Road%20the%20Gathering%20-Rules%20ver3-blue.svg)


## 目錄
 - 一般基地
 - 地面基地
 - “你” 
 - 基地或 “你” 被消滅
 - 基地權力真空
 - 地面物件
 - [g]。[p]。[v]。[r]
 - 座標棋子
 - 近身攻擊
 - 地面防具
 - (物件)置於地面
 - 虛擬地面。座標

*** 

## 一般基地
用作生產一般物件。


## 地面基地
用作生產地面物件。


## “你” 
 - 遊戲開始時，”你“ 視作與 <br>
基地分享能量值。
 - “你” 完成後，視作與基地分離。<br>
同時擁有 攜離 和 閃避 能力。<br>

> **攜離：**
> ”你” 可任意轉換與 “你”<br>
> 座標相同的 [p] 物件<br>
> 於生產線上的位置。<br>
> “你” 生產線上的物件 (v) <br>
> 將與 “你” (v) 相同。<br>

> **閃避：**
> ”你” 在地面時，不能成為<br>
> 非 [p] 物件的目標。<br>

 - “你” 移回基地，可與基地復合。<br>
重新分享能量值。<br>
(將所有 [W] 從你身上移回基地。<br>
然後將 “你” 移出遊戲。)<br>
 - “你” 只能有一個。<br>
若你被消滅，視作你死亡。<br>

> 你即使移離基地，仍能生產<br>
> 及使用該基地的物件。<br>
> 直至你被消滅。


## 基地或 “你” 被消滅

若 “你” 移離基地，<br>
兩者能量值分開結算。

 1. 基地能量值為 0，<br>
基地被消滅，<br>
其生產線失去生產能力。<br>
但其物件仍能使用，<br>
你仍能繼續遊戲。<br>
(基地不能重建)<br>
 2. 你的能量值為 0，<br>
你被消滅，<br>
基地視作權力真空。


## 基地權力真空

當某角色移離基地時被消滅，<br>
視作權力真空。<br>
其物件全部被消滅。


## 地面物件

若該物件屬地面空間 {G}，<br>
其即地面物件。<br>
其須於 地面基地 生產。<br>

**地面物件新增以下功能：**
 1. [g] 可使用地面
 2. [p] 可攜離基地
 3. [v] 速度
 4. [r] 有效範圍 (結算)

**可使用地面 [g]** 
**(Ground Use Objects)** \
地面物件預設\
只可使用地面空間。\
一般物件預設\
不可使用地面空間。

**可攜離基地 [p]** 
**(Portable Objects)** 
- 若地面物件擁有 [p]，\
其可置於 “你” 的生產線上。\
(其 (v) 將與 “你” (v) 相同)
- 一般 [p] 物件須與 “你” \
座標相同才能使用。

**速度 [v]**
 - 即其於行動階段，在地面每次 \
最遠可移動格數。 \
[v] 預設為 0。
 - 若其 (v) 大於 0，可自行移動。<br>
(否則須透過其他方法移動) <br>
當其位置不在原位， <br>
(你遊戲開始時的位置) <br>
須以座標棋子標示。

> **座標棋子** \
> 首次移動前，獲得 \
> 兩個相同的座標棋子。\
> 分別置於該底座 及 “虛擬地面”。\
> 其後移動時，改變地面上棋子的位置。\
> (若棋子用盡，須待場上棋子移走才能重用。)

**有效範圍 [r]** (結算)\
即以自身為中心起的距離格數。\
[r] 預設為 0。\
你可在任何時候使用地面物件，\
唯必須滿足其有效範圍 [r]，\
才可觸發效果，進行結算。\
(武器須在行動階段使用)


## 近身攻擊
若使用地面武器，\
其傷害結算改為近身傷害結算。\
\
**將傷害結算的描述按下述更改。**
 1. 物件改為地面物件。\
(武器改為地面武器)
 2. 目標角色的基地改為角色本身。

你另可指定置於地面的\
非 [p] 物件為目標。


> **傷害結算原文**
> 1) 宣告使用任意個武器，\
> 將其底座正面對外展示，\
> 並指定目標角色。
> 2) 若目標角色多於一人，\
> 則依順序結算。
> 3) 目標角色可選擇\
> 任意個物件阻擋任意個武器。\
> (可將其底座正面對外展示)
> 4) 若沒有物件阻擋，\
> 武器對目標角色的基地\
> 直接造成傷害。
> 5) 若有物件阻擋，\
> 武器對其物件造成傷害。
> 6) 傷害以 1(W) 抵銷 1(A) 結算。\
> 被抵銷的 [W] 須從該物件移走。
> 7) 若阻擋後仍有攻擊剩餘，\
> 其對目標角色的基地造成傷害。
> 8) 武器使用一次後消滅。


## 地面防具
阻擋結算時跟一般防具相同。


## (物件)置於地面
即將 “你” 生產線上的物件\
轉換至其他生產線。\
(轉換時同時轉移座標棋子)

> 當物件置上座標棋子，\
> 即使其置於生產線上，\
> 亦不代表其置於基地。


## 虛擬地面
地面空間以 “虛擬地面” 表示。\
虛擬地面 為極座標系統。\
所有角色的基地平均分佈\
在徑距為 4 的外圍。

**座標** <br>
第四圍：(01,04), (02,04)...\
第三圍：(01,03), (02,03)...\
第二圍：(01,02), (02,02)...\
第一圍：(01,01), (02,01)...\
中心：0

***
