# Analysis of World Happiness

# Introduction: 
World Happiness Report เป็นการประเมินระดับความสุขของประชาชนหลายล้านคนใน 146 ประเทศทั่วโลก ซึ่งจัดอันดับ 155 ประเทศตาม คะแนนความสุข(Happiness score) โดยพิจารณาจากปัจจัย 6ประการได้แก่ GDP, Family, Life Expectancy, Generosity, Trust in Government and Freedom ซึ่งผลรวมของปัจจัยทั้งเหล่าทำให้เกิดเป็นคะแนนความสุข(Happiness score) 

# Object : 
ต้องการวิเคราะห์เพื่อหาคำตอบที่น่าสนใจดังนี้\
1.การปรับตัวในช่วง 5 ปีของประเทศไทย และเปรียบเทียบกับ Top10 ของโลกเป็นอย่างไร?\
2.ทั้ง6ปัจจัยตามที่ Report ระบุมีผลต่อความสุขของประเทศอย่างมีนัยสำคัญหรือ?

# Data Set & Cleaning :
ชุดข้อมูลที่เลือกใช้คือชุดข้อมูล World Happiness report 2015 ซึ่งพิจารณาจากปัจจัย 6ประการด้วยกัน ได้แก่
Economy (GDP per Capita),Family,Health (Life Expectancy),Freedom,Trust (Government Corruption),Generosity\
**Dataset มีทั้งหมด5ไฟล์ : \
    2015.csv(158, 12), 2016.csv(157, 13), 2017.csv(155, 12), 2018.csv(156, 9), 2019.csv(156, 9)

![image](https://github.com/WatcharakorP/DADS5001_Midterm/blob/8b459f2196845663c865d0d39ed366c7f0028a9a/CleaningData.JPG)

![image](https://github.com/WatcharakorP/DADS5001_Midterm/blob/b9b1c4f6036bcda9c5212d42a2bec55fa379d06d/DistributionData.JPG)

# Visualization

**จำนวนประเทศในแต่ละภูมิภาคจากข้อมูลที่เราใช้

![image](https://github.com/WatcharakorP/DADS5001_Midterm/blob/dcb92e5fc64d7431343ec86e4719a664d70f61ec/Overall-01.JPG)

    Happiness score distribution in different regions คือ การเช็คการกระจายตัวของข้อมูลคะแนนของความสุข(Happiness Score) ซึ่งจะบอกช่วงของคะแนน,ค่าสูงสุด,ค่าต่ำสุดออกมาในรูปของกราฟ
    จากภาพจะเห็นว่าทวีป Middle East and Northern Africa มีช่องว่าง(Gap)ระหว่างค่าสูงสุดและค่าต่ำสุดมากที่สุด ขณะเดียวกัน Australia and New Zealand จะมีช่วงคะแนนที่แคปที่สุดเนื่องจากจำนวนข้อมูลในทวีปดังกล่าวค่อนข้างน้อยและค่าคะแนนใกล้เคียง
![image](https://github.com/WatcharakorP/DADS5001_Midterm/blob/dcb92e5fc64d7431343ec86e4719a664d70f61ec/Overall-02.JPG)

# Analyzing Thailand Happiness

![image](https://github.com/WatcharakorP/DADS5001_Midterm/blob/main/AnalyzingThailand.JPG)

# Discussion
**สงสัยหรือไม่?\
ทำไมประเทศไทยมีปัจจัยบางหัวข้อที่ดีกว่าประเทศ 10อันดับแรกของโลกแต่มีคะแนนความสุขน้อยกว่า \
หรือประเทศไทยมีปัจจัยที่ดีกว่าปสิงคโปร์ถึง 3 ปัจจัยแต่ได้คะแนน Happiness Score น้อยกว่าประเทศสิงค์โปร์

![image](https://github.com/WatcharakorP/DADS5001_Midterm/blob/fbb2846df379a5249c427495eee85b6d3826a96c/Correlation.JPG)

เฉลย: ก็เป็นเพราะความสัมพันธ์ของข้อมูลใช้ในการคิด Happiness score ในแต่ล่ะปัจจัยไม่เท่ากัน กล่าวคือการเพิ่มขึ้นหรือลดลงในปัจจัยหนึ่งๆ ส่งผลกระทบต่อ Happiness score ไม่เท่ากัน

# Conclussion

![image](https://github.com/WatcharakorP/DADS5001_Midterm/blob/fbb2846df379a5249c427495eee85b6d3826a96c/Conclussion.JPG)

