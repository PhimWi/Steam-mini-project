# Steam Games Dataset Analysis

Steam Games Dataset เป็นข้อมูลที่เกี่ยวข้องกับเกมในแพลตฟอร์ม Steam ซึ่งเป็นแพลตฟอร์มที่ได้รับความนิยมในการรวบรวมและจัดจำหน่ายเกมดิจิทัล การวิเคราะห์ข้อมูลนี้มีวัตถุประสงค์เพื่อทำความเข้าใจแนวโน้มและปัจจัยต่าง ๆ ที่ส่งผลต่อยอดขายและความนิยมของเกม โดยหวังว่าการวิเคราะห์นี้จะช่วยให้ผู้พัฒนาเกม นักการตลาด หรือผู้สนใจในวงการเกมสามารถวางกลยุทธ์และตัดสินใจได้ดีขึ้นในการพัฒนาเกมในอนาคต

Dataset imported from: https://www.kaggle.com/datasets/fronkongames/steam-games-dataset

**List of Contents**

* [Game Categories](#Categories)
* [Game Genres](#Genres)
* [Playtime](#Playtime)
* [Game Price](#Price)
* [Systems](#Systems)
* [Developer and Publisher](#DeveloperAndPublisher)
* [Correlation](#Correlation)
* [Positive and Negative Review](#PositiveAndNegative)
* [Summary](#Summary)

---

# Categories

อย่างแรกได้ทำการแบ่ง categories ของเกมว่า categories ไหนมีจำนวนเกมมากที่สุด 10 อันดับแรก พบว่า 'Single-player' มีจำนวนเกมมากที่สุด โดยมีจำนวนเกมถึง 86,889 เกม มากกว่าอันดับที่ 2 อย่าง 'Steam Achievements' 2.11 เท่า

![Number of Games in Each Category](https://github.com/wand-work/steam_year_stats/blob/main/Number%20of%20Games%20in%20Each%20Category.png)

เมื่อทำการดูแนวโน้มของ categories ในช่วง 10 ปีที่ผ่านมา พบว่า 'Single-player' มีจำนวนเกมที่มากที่สุด ซึ่งสอดคล้องกันกับกราฟด้านบน และมีแนวโน้มที่เพิ่มขึ้นเรื่อย ๆ

![Number of Games Per Category Over Time](https://github.com/wand-work/steam_year_stats/blob/main/Number%20of%20Games%20Per%20Category%20Over%20Time.png)

เมื่อทำการวิเคราะห์จำนวนการเป็นเจ้าของเกมตาม categories พบว่า 'Single-player' ยังคงเป็นหมวดหมู่ที่มีจำนวนเกมและการครอบครองสูงที่สุด โดยมียอดการซื้อสะสมสูงถึง 5.89 พันล้านครั้ง

![Top 10 Categories by Total Owners](https://github.com/wand-work/steam_year_stats/blob/main/Top%2010%20Categories%20by%20Total%20Owners.png)



# Genres

ต่อมาได้ทำการแบ่ง genres ของเกมว่า genres ไหนมีจำนวนมากที่สุด 10 อันดับแรก พบว่า 'Indie' มีจำนวนเกมมากที่สุด โดยมีจำนวนเกมอยู่ที่ 64,501 เกม มากกว่าอันดับที่ 2 อย่าง 'Casual' 1.64 เท่า

![Number of Games in Each Genre](https://github.com/wand-work/steam_year_stats/blob/main/Number%20of%20Games%20in%20Each%20Genre.png)

เมื่อทำการดูแนวโน้มของ genres ในช่วง 10 ปีที่ผ่านมา พบว่า 'Indie' มีจำนวนเกมที่มากที่สุด ซึ่งสอดคล้องกันกับกราฟด้านบน และมีแนวโน้มที่เพิ่มขึ้นเรื่อย ๆ เช่นเดียวกัน

![Number of Games Per Genre Over Time](https://github.com/wand-work/steam_year_stats/blob/main/Number%20of%20Games%20Per%20Genre%20Over%20Time.png)

เมื่อทำการวิเคราะห์จำนวนการเป็นเจ้าของเกมตาม genre พบว่าแม้ 'Indie' จะมีจำนวนเกมมากที่สุด แต่ยอดซื้อกลับน้อยกว่า 'Action' ซึ่งเป็นหมวดหมู่ที่มีจำนวนการเป็นเจ้าของสูงที่สุด โดยมียอดการซื้อสะสมถึง 4.749 พันล้านครั้ง สวนทางกับจำนวนเกมในหมวด 'Action' ที่อยู่ในอันดับที่ 3 แสดงให้เห็นว่าผู้เล่นมีความชื่นชอบในเกมประเภท 'Action' มากกว่า 'Indie'

![Top 10 Genre by Total Owners](https://github.com/wand-work/steam_year_stats/blob/main/Top%2010%20Genre%20by%20Total%20Owners.png)



# Playtime

เวลาเฉลี่ยที่ผู้เล่นใช้ในการเล่นเกมสามารถสะท้อนถึงระดับความสนใจและความชื่นชอบที่ผู้เล่นมีต่อเกมนั้น ๆ ได้เป็นอย่างดี ยิ่งผู้เล่นใช้เวลามากเท่าไร ก็ยิ่งบ่งบอกถึงปฏิสัมพันธ์ระหว่างผู้เล่นกับเกมที่เพิ่มขึ้น ไม่ว่าจะเป็นการสำรวจเนื้อหาในเกม การพัฒนาตัวละคร หรือการเข้าสู่โหมดต่าง ๆ ภายในเกม

| Year | Category | Maximum hrs of playtime in Year |
|-----------------|-----------------|-----------------|
| 2014   | Single-player    | 849.1 hrs    |
| 2015   | Single-player    | 1323.7 hrs    |
| 2016   | Single-player    | 1857.25 hrs    |
| 2017  | Single-player    | 1874 hrs    |
| 2018 | Single-player    | 2053.5 hrs    |
| 2019  | Single-player    | 2112.2 hrs    |
| 2020  | Single-player    | 2989 hrs    |
| 2021   | Single-player    | 4067.25 hrs    |
| 2022  | Single-player    | 2328.5 hrs    |
| 2023| Single-player    | 2447 hrs    |


เมื่อเปรียบเทียบสถิติหมวดหมู่เกม (Category) ย้อนหลัง 10 ปี พบว่าเกมในหมวด Single-player ยังคงครองอันดับหนึ่งมาอย่างต่อเนื่องตั้งแต่ปี 2014 ถึง 2023 โดยในปี 2021 มีเวลาเฉลี่ยในการเล่นเกมสูงกว่าปีอื่น ๆ อย่างเห็นได้ชัด ซึ่งสะท้อนให้เห็นว่าในช่วงเวลาดังกล่าวอาจมีจำนวนเกมในหมวด Single-player ที่เพิ่มมากขึ้น

นอกจากนี้ แนวโน้มเวลาเฉลี่ยที่ใช้ในการเล่นเกมที่เพิ่มมากขึ้นในทุกปี เป็นไปได้ที่น่าจะมีเนื้อเรื่องที่เข้มข้นและน่าติดตามมากยิ่งขึ้น ทำให้ผู้เล่นใช้เวลาเล่นนานกว่าเดิม การเพิ่มขึ้นของเวลาเฉลี่ยจึงอาจเป็นผลมาจากการที่ผู้พัฒนาเกมให้ความสำคัญกับการสร้างเนื้อหาที่ดึงดูดผู้เล่นให้ใช้เวลาอยู่กับเกมนานขึ้น

| Year | Genre | Maximum hrs of playtime in Year |
|-----------------|-----------------|-----------------|
| 2014   | Action    | 393.2 hrs    |
| 2015   | Indie    | 880.9 hrs    |
| 2016   | Indie   | 1065.25 hrs    |
| 2017  | Action    | 1038.71 hrs    |
| 2018 | Indie    | 1303.3 hrs    |
| 2019  | Indie    | 1330.6 hrs    |
| 2020  | Indie    | 1386.25 hrs    |
| 2021   | Adventure    | 2185 hrs    |
| 2022  | Indie    | 1232.5 hrs    |
| 2023| Action    | 1238 hrs    |


เมื่อลองเปรียบเทียบกับประเภทเกม (Genres) ย้อนหลัง 10 ปี พบว่าเกมในประเภท Indie ครอง 6 ใน 10 ของอันดับ เและมีการเพิ่มขึ้นของเวลาอย่างต่อเนื่องตลอดช่วงปี 2015 - 2020 ก่อนจะลดลงเล็กน้อยในปี 2022 ขณะที่เกมประเภท Action กลับมาได้รับความนิยมในปี 2023 ส่วนเกม Adventure มีความโดดเด่นในปี 2021 ด้วยเวลาเฉลี่ยสูงสุดที่ 2,185 ชั่วโมง



# Price

ในส่วนของราคาเกมบน Steam ได้ทำการดูการกระจายตัวของราคาเกม พบว่าราคาส่วนใหญ่อยู่ในช่วงต่ำกว่า 10 ดอลลาร์ โดยเฉพาะในช่วงราคาที่ต่ำกว่า 5 ดอลลาร์นั้นเป็นช่วงที่มีจำนวนมากที่สุด ซึ่งค่าเฉลี่ยของราคาอยู่ที่ 7.09 ดอลลาร์ แสดงให้เห็นว่าราคาส่วนใหญ่ต่ำกว่าค่าเฉลี่ยนี้ อีกทั้ง histogram มีลักษณะเบ้ขวา (Skewed Right) หมายความว่ามีเกมบางส่วนที่มีราคาสูง แต่ก็มีจำนวนที่น้อยมาก

![Histogram of Prices with Ranges](https://github.com/wand-work/steam_year_stats/blob/main/Histogram%20of%20Prices%20with%20Ranges.png)

มื่อเจาะลึกลงไปตาม genre พบว่า
* เกมประเภท Casual มีจำนวนเกมส่วนมากอยู่ที่ราคาต่ำที่สุด โดยกระจุกตัวอยู่ในช่วงราคาที่ต่ำกว่า 5 ดอลลาร์
* เกมประเภท Action และ Indie มีการกระจายตัวที่กว้างกว่าในช่วงราคา 5 - 20 ดอลลาร์ ซึ่งบ่งบอกว่าเกมในประเภทนี้มีราคาที่หลากหลายกว่าเมื่อเทียบกับ Casual
* เกมในหมวด Adventure และ Simulation มีความหนาแน่นที่ต่ำกว่าประเภทอื่น ๆ ในช่วงราคา 0 - 10 ดอลลาร์ และมีความหนาแน่นที่กระจายตัวไปจนถึงราคาประมาณ 20 ดอลลาร์ แสดงว่าเกมในหมวดนี้ มีราคาที่สูงขึ้นกว่า เกม Casual, Indie

![Distribution of Prices for Top 5 Genres](https://github.com/wand-work/steam_year_stats/blob/main/Distribution%20of%20Prices%20for%20Top%205%20Genres.png)



# Systems

ในยุคที่ผู้เล่นเกมมีความหลากหลายของอุปกรณ์ การรองรับหลายระบบปฏิบัติการถือเป็นสิ่งสำคัญสำหรับผู้พัฒนาเกม เพื่อเพิ่มโอกาสในการเข้าถึงผู้เล่นมากขึ้น จึงได้มีการตรวจสอบข้อมูลในส่วนนี้ และพบว่ามีเกมที่รองรับทั้งสามระบบปฏิบัติการเพียง 9,317 เกม ซึ่งคิดเป็นสัดส่วนเพียง 9.56% จากจำนวนเกมทั้งหมด สัดส่วนนี้ถือว่ายังไม่สูงมากนัก และไม่ตรงตามข้อสันนิษฐานที่คาดไว้เกี่ยวกับความนิยมในการรองรับหลายระบบปฏิบัติการในเกม

เมื่อวิเคราะห์ผู้พัฒนาที่ผลิตเกมรองรับทั้งสามระบบปฏิบัติการ พบว่า Choice of Games ครองอันดับสูงสุด ด้วยจำนวนเกมที่รองรับทั้งสามระบบถึง 159 เกม ซึ่งมากกว่าอันดับที่สองอย่าง Hosted Games 1.53 เท่า ข้อมูลนี้อาจบ่งชี้ว่า Choice of Games เป็นผู้พัฒนาที่มีเงินทุนสูงหรือมีจำนวนทีมงานที่มาก

![Top 10 Developers All Systems Supported](https://github.com/wand-work/steam_year_stats/blob/main/Top%2010%20Developers%20All%20Systems%20Supported.png)

เมื่อวิเคราะห์ผู้จัดจำหน่ายที่ผลิตเกมรองรับทั้งสามระบบปฏิบัติการ พบว่า Choice of Games ครองอันดับสูงสุด ด้วยจำนวนเกมที่รองรับทั้งสามระบบถึง 159 เกม ซึ่งมากกว่าอันดับที่สองอย่าง Hede 1.27 เท่า ข้อมูลนี้สอดคล้องกับการวิเคราะห์ผู้พัฒนาที่ผลิตเกมรองรับทั้งสามระบบปฏิบัติการ โดยชี้ให้เห็นว่าเกมจาก Choice of Games มีแนวโน้มสูงที่จะออกเกมใหม่ที่สามารถรองรับทั้งสามระบบปฏิบัติการได้อย่างต่อเนื่อง

![Top 10 Publishers All Systems Supported](https://github.com/wand-work/steam_year_stats/blob/main/Top%2010%20Publishers%20All%20Systems%20Supported.png)



# DeveloperAndPublisher

จากการสำรวจข้อมูล พบว่า Developer และ Publisher แต่ละรายมีจำนวนผู้ที่เป็นเจ้าของเกม ที่แตกต่างกัน ซึ่งสะท้อนให้เห็นถึงความหลากหลายของตลาดเกมและความชอบที่แตกต่างกันของผู้เล่นในแต่ละประเภทเกม

![Top 10 Developers by Total Owners](https://github.com/wand-work/steam_year_stats/blob/main/Top%2010%20Developers%20by%20Total%20Owners.png)

จากกราฟจะเห็นได้ว่า จำนวนของผู้ที่เป็นเจ้าของเกมของ Valve มีจำนวนที่สูงที่สุด โดยมีสัดส่วนจำนวนการซื้อเกมมากกว่า 9 ลำดับที่เหลืออย่างเห็นได้ชัด โดยมีสัดส่วนมากกว่าลำดับที่ 2 อย่าง Game Science ถึง 6.51 เท่า

![Top 10 Publishers by Total Owners](https://github.com/wand-work/steam_year_stats/blob/main/Top%2010%20Publishers%20by%20Total%20Owners.png)

จะเห็นได้ว่า ไม่ว่าจะเป็นผู้พัฒนา หรือผู้จัดจำหน่าย Valve ก็มีการขายเกมในจำนวนที่มากกว่าทุก ๆ เจ้า เมื่อลองทำการเจาะลึกลงไปจึงพบว่า Valve เป็นค่ายเกมที่ผลิตเกม อย่าง Counter-Strike ออกมา ซึ่งเกมนี้ที่เป็นที่นิยมเป็นอย่างมาก จึงทำให้ Valve ครองอันดับแรกของทั้ง 2 หัวข้อนี้ไปได้

---

จากการสำรวจและวิเคราะห์ข้อมูลข้างต้น ทำให้เห็นถึงแนวโน้มของตลาดบนแพลตฟอร์ม Steam ว่าเป็นอย่างไร จึงเกิดข้อสงสัยว่าอะไรคือปัจจัยที่ส่งผลต่อการเลือกซื้อเกมบนแพลตฟอร์ม Steam

---

# Correlation

คอลัมน์ที่เลือกในการดูความสัมพันธ์ ได้แก่ คอลัมน์ 'Price', 'Avg_playtime', 'Positive', 'Negative', 'Windows', 'Mac', 'Linux' และ 'owners'

![Correlation Heatmapl Owners](https://github.com/wand-work/steam_year_stats/blob/main/Correlation%20Heatmapl%20Owners.png)

จากกราฟ Correlation Heatmap แสดงให้เห็นถึงความสัมพันธ์ระหว่างตัวแปรต่าง ๆ โดยพบว่าความสัมพันธ์ของรีวิวเชิงบวกและเชิงลบมีความสัมพันธ์กันเป็นอย่างมาก ซึ่งมีค่า Correlation สูงถึง 0.78 แสดงว่าผู้เล่นที่ให้รีวิวดีมักจะมีรีวิวไม่ดีในบางกรณี

นอกจากนี้รีวิวเชิงบวกและลบยังมีความสัมพันธ์สูงกับ จำนวนผู้ใช้งาน (Owners) ที่ 0.67 และ 0.63 ตามลำดับ ซึ่งแสดงให้เห็นว่าจำนวนรีวิวมีผลต่อการเพิ่มจำนวนผู้เล่น จึงได้ข้อสงสัยว่าลักษณะเกมแบบไหนที่มักจะได้รับรีวิวเชิงบวกและลบ



# PositiveAndNegative

Correlation heatmap แสดงให้เห็นว่า คอลัมน์ 'Positive' และ 'Negative' มี positive correlation ร่วมกันที่ 0.78 จึงทำการ sort ข้อมูลและเลือกเกมที่มีคะแนน Positive อันดับแรกคือ Counter-Strike มาเพื่อ ดึงข้อมูลรีวิวของเกมเพิ่มเติม

> Positive Reviews

| Name | Genres | Positive | Negative | Released Year |
|-----------------|-----------------|-----------------|-----------------|-----------------|
| Counter-Strike: Global Offensive   | Action,Free to Play    | 5,764,420    | 766,677 | 2012 |
| Dota 2   | Action,Free to Play,Strategy    | 1,477,153    | 300,437 | 2013|
| Grand Theft Auto V| Action, Adventure | 1,171,197    | 210,154 | 2015|
| PUBG: Battlegrounds| Action,Adventure,Free to Play,Massively Multiplayer | 1,154,655 | 895,978 | 2017|
| Terraria   | Action,Adventure,Indie,RPG    | 964,983    | 21,044 | 2011|
| Tom Clancy’s Rainbow Six Siege | Action | 929,372    | 138,530 | 2015|
| Team Fortress 2   | Action,Free to Play    | 823,693    | 56,683 | 2007|
| Garry’s Mod   | Indie,Simulation    | 822,326    | 29,004 | 2006|
| Rust   | Action,Adventure,Indie,Massively Multiplayer, RPG    | 703,687    | 108,223 | 2018|
| Black Myth: Wukong   | Action,Adventure,RPG    | 663,109    | 28,700 | 2024|



> Negative Reviews

| Name | Genres | Positive | Negative | Released Year |
|-----------------|-----------------|-----------------|-----------------|-----------------|
| PUBG: Battlegrounds | Action,Adventure,Free to Play,Massively Multiplayer | 1,154,655    | 895,978 | 2017 |
| Counter-Strike: Global Offensive      | Action,Free to Play | 5,764,420   | 766,677 | 2012|
| Dota 2 | Action, Free to Play, Strategy | 1,477,153    | 300,437 | 2013|
| Grand Theft Auto V | Action,Adventure | 1,171,197 | 210,154 | 2015|
| Tom Clancy’s Rainbow Six Siege   | Action | 929,372   | 138,530 | 2015|
| Cyberpunk 2077 | RPG | 391,643    | 129,925 | 2020|
| Dead by Daylight   | Action | 494,648    | 112,924 | 2016|
| Rust   | Action,Adventure,Indie,Massively Multiplayer,RPG| 703,687    | 108,223| 2018|
| Battlefield 2042  | Action,Adventure,Casual | 39,121    | 106,038 | 2021|
| 鬼谷八荒 Tale of Immortal | Action,Adventure,Indie,RPG,Simulation,Early Access    | 105,384   | 103,661 | 2021|


เกมยอดนิยมส่วนใหญ่เป็นแนว Action และ Adventure โดย Counter-Strike: Global Offensive มีรีวิวเชิงบวกสูงสุดถึง 5.76 ล้านรีวิว ในขณะเดียวกันเมื่อดูตามรีวิวเชิงลบกลับพบว่า Counter-Strike ได้อันดับที่ 2 ของเกมที่มีรีวิวเชิงลบมากที่สุดเช่นกัน และเกม 9 จาก 10 อันดับ มาจาก Action genre

| Name | Released Year | Owners | Categories | Genres |
|-----------------|-----------------|-----------------|-----------------|-----------------|
| PUBG: Battlegrounds | 2017 | 75,000,000    | Multi-player,PvP,Online PvP,Stats,Remote Play| Action,Adventure,Free to Play,Massively Multiplayer|
| New World      | 2021 | 75,000,000   | Multi-player,MMO,PvP,Online PvP,Co-op     | Action,Adventure,Massively Multiplayer,RPG|
| Black Myth: Wukong | 2024 | 75,000,000    | Single-player,Steam Achievements| Action,Adventure,RPG|
| Tom Clancy’s Rainbow Six Siege   | 2015 | 35,000,000 | Single-player,Multi-player,PvP| Action|
| Among Us  | 2018 | 35,000,000   | Multi-player ,Online PvP, Co-op| Casual|


จาก correlation heatmap ที่แสดงถึงความสัมพันธ์เชิงบวกระหว่างจำนวนผู้เล่น (owners) และรีวิวเชิงลบ (Negative column) ทำให้เกิดคำถามว่า ทำไมจำนวนผู้เล่นที่เพิ่มขึ้นถึงสัมพันธ์กับรีวิวเชิงลบ? เมื่อเจาะลึกไปที่เกมประเภท Action ซึ่งมีรีวิวเชิงลบสูงอย่าง PUBG: Battlegrounds และ Tom Clancy's Rainbow Six Siege ที่อยู่ใน top 5 ของเกมที่มีผู้เล่นมากที่สุดในช่วง 10 ปี มีส่วนทำให้เกิดความสัมพันธ์นี้หรือไม่? หรือเป็นไปได้ว่า เมื่อมีผู้เล่นมากขึ้น การคาดหวังหรือประสบการณ์ของผู้เล่นนั้นเปลี่ยนไป ส่งผลให้เกิดการวิจารณ์ในด้านลบมากขึ้น?

ได้ทำการ scrape ข้อมูลรีวิวโดยใช้ credit : https://apify.com/

![Frequency of Sentiment Scores](https://github.com/wand-work/steam_year_stats/blob/main/Frequency%20of%20Sentiment%20Scores.png)

เมื่อนำความคิดเห็นของเกม Counter-Strike มาจับกลุ่มด้วยกันพบว่าคะแนนทางด้าน Positive นั้นมีจำนวนที่ค่อนข้างมากกว่า Negative 


## SHAP Positive vs. Negative Sentiment Classification

เนื่องจากการดึงข้อมูลข้างต้นยังไม่สามารถแสดงภาพที่ชัดเจนได้ จึงได้นำ SHAP มาใช้ในการวิเคราะห์เชิงอารมณ์ (Sentiment Analysis) เพื่อทำความเข้าใจเชิงลึกเกี่ยวกับความรู้สึกของผู้เล่นต่อเกมในแต่ละหมวดหมู่ โดย SHAP จะช่วยให้เรามองเห็นปัจจัยต่าง ๆ ที่ส่งผลต่อความชอบและความพึงพอใจของผู้เล่นอย่างชัดเจนมากยิ่งขึ้น

credit : https://shap.readthedocs.io/en/latest/example_notebooks/text_examples/sentiment_analysis/Positive%20vs.%20Negative%20Sentiment%20Classification.html#Load-the-IMDB-movie-review-dataset

โดยคำที่ไฮไลท์สีฟ้าเป็นคำที่ SHAP วิเคราะห์ออกมาว่าเป็น Negative และสีแดงเป็น Positive

![Shap Word Values](https://github.com/wand-work/steam_year_stats/blob/main/shap-negative.png)

เมื่อทำการวิเคราะห์คอมเมนต์พบว่ารีวิวที่เป็น Positive มักจะมีคำที่พบได้บ่อยดังนี้

![Shap Review Values](https://github.com/wand-work/steam_year_stats/blob/main/shapplotbar.png)



# Summary

## Conclusion

จากการวิเคราะห์ข้อมูลผู้เล่นเกมบน Steam ในช่วง 10 ปีที่ผ่านมา ค้นพบหลายปัจจัยที่ส่งผลต่อความนิยมของเกม ซึ่งสามารถสรุปออกมาเป็นประเด็นสำคัญได้ดังนี้:

**1. ปัจจัยที่ส่งผลให้เกมเป็นที่นิยม**

* ประเภทเกม (Categories): หมวด Single-player ยังคงเป็นหมวดหมู่ที่มีจำนวนเกมสูงสุดถึง 86,889 เกม และมียอดการซื้อสะสมสูงถึง 5.89 พันล้านครั้ง ทำให้เกมในหมวดนี้ได้รับความนิยมอย่างต่อเนื่อง

* แนวเกม (Genres): แม้ว่าเกมประเภท Indie จะมีจำนวนเกมมากที่สุด แต่ยอดการซื้อกลับต่ำกว่าเกมประเภท Action ซึ่งมีความนิยมสูงกว่า โดยมียอดการซื้อสะสมถึง 4.749 พันล้านครั้ง

* เวลาเล่น (Playtime): เวลาเฉลี่ยที่ผู้เล่นใช้ในการเล่นเกมบ่งบอกถึงระดับความสนใจ โดยเฉพาะในหมวด Single-player ซึ่งมีแนวโน้มเพิ่มขึ้นอย่างต่อเนื่อง ทำให้แสดงถึงการพัฒนาของเนื้อเรื่องที่เข้มข้นและน่าสนใจ

* ราคาเกม (Price): เกมที่มีราคาต่ำ มักจะเป็นที่นิยมมากกว่า โดยเฉพาะเกมในหมวด Casual ที่มีราคาต่ำกว่า 5 ดอลลาร์


**2. ปัจจัยที่ทำให้เกมไม่เป็นที่นิยม หรือได้รับ Negative Review**

* จำนวนผู้เล่น (Owners): เกมบางเกมที่มีผู้เล่นจำนวนมาก แต่กลับได้รับรีวิวเชิงลบสูง เช่น PUBG: Battlegrounds และ Tom Clancy's Rainbow Six Siege ซึ่งอาจเกิดจากความคาดหวังที่สูงขึ้นเมื่อมีผู้เล่นมากขึ้น

* การรองรับหลายระบบ (Systems): มีเกมที่รองรับทั้งสามระบบปฏิบัติการเพียง 9,317 เกม คิดเป็น 9.56% ซึ่งแสดงให้เห็นว่ายังไม่เพียงพอในการเข้าถึงผู้เล่นหลายกลุ่ม

* ความคิดเห็นในเชิงลบ: ตัวอย่างการวิเคราะห์โดย SHAP แสดงให้เห็นว่าความคิดเห็นเชิงลบเกี่ยวกับฟีเจอร์บางอย่างในเกมสามารถทำให้ผู้เล่นไม่พอใจได้


**3. เทรนด์ 5 ปี ย้อนหลังของผู้เล่นบน Steam**
* การเติบโตของ Single-player: เกมในหมวด Single-player ยังคงครองตลาดและมีแนวโน้มที่จะเพิ่มขึ้นอย่างต่อเนื่อง
  
* การเปลี่ยนแปลงใน Genres: ประเภท Action ได้รับความนิยมกลับมาในปี 2023 ขณะที่เกมประเภท Indie ดูเหมือนจะลดลงในปีที่ผ่านมา
  
* ราคาและการเข้าถึง: ราคาเกมยังคงมีความสำคัญต่อการเลือกซื้อ โดยราคาที่ต่ำกว่า 10 ดอลลาร์ เป็นปัจจัยหลักที่ทำให้เกมได้รับความนิยม


## Suggestions

การเข้าใจพฤติกรรมและความต้องการของผู้เล่นเป็นสิ่งสำคัญที่สามารถช่วยให้ทั้งผู้พัฒนาและผู้เล่นได้ประโยชน์จากการมีส่วนร่วมในตลาดเกมอย่างมีประสิทธิภาพ นอกจากนี้การมีส่วนร่วมในการสร้างเนื้อหาและฟีเจอร์ใหม่ ๆ นั้น ช่วยให้วงการสามารถพัฒนาไปในทิศทางที่ดีขึ้นต่อไปในอนาคต โดยมีคำแนะนำสำหรับผู้พัฒนาเกม ดังนี้

* เน้นการสร้างเนื้อเรื่องที่เข้มข้น: จากข้อมูลที่แสดงถึงความนิยมของเกมในหมวด Single-player ที่มีเนื้อเรื่องลึกซึ้ง ควรให้ความสำคัญกับการพัฒนาเนื้อเรื่องและตัวละครเพื่อดึงดูดความสนใจของผู้เล่นให้มากขึ้น

* สำรวจความต้องการของผู้เล่น: ควรทำการสำรวจและรับฟังความคิดเห็นจากผู้เล่นเพื่อเข้าใจความต้องการที่แท้จริง ซึ่งจะช่วยในการพัฒนาฟีเจอร์หรือเนื้อหาที่ตรงใจผู้เล่น

* พิจารณาราคาเกม: การตั้งราคาที่เหมาะสมและแข่งขันได้จะช่วยให้เกมของคุณเข้าถึงผู้เล่นได้มากขึ้น โดยเฉพาะในกลุ่มเกมที่มีราคาต่ำ เช่น เกมประเภท Casual

* รองรับหลายระบบปฏิบัติการ: ควรพัฒนาเกมให้รองรับหลายระบบปฏิบัติการเพื่อเพิ่มโอกาสในการเข้าถึงผู้เล่นที่มีอุปกรณ์หลากหลาย


---

# Reference
* https://www.kaggle.com/datasets/fronkongames/steam-games-dataset
  Kaggle dataset
* https://apify.com/
  Web scraping
* https://shap.readthedocs.io/en/latest/example_notebooks/text_examples/sentiment_analysis/Positive%20vs.%20Negative%20Sentiment%20Classification.html#Load-the-IMDB-movie-review-dataset
  SHAP Sentimental Analysis



# Members

* 6620412004 Wandita Wongsinthon
* 6620412008 Phimpatra Wibulrithi

