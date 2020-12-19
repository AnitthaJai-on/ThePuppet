# The Puppet
* [Link](#link)
* [About](#about)
* [สิ่งที่ต้องทำ](#สิ่งที่ต้องทำ)
* หมายเหตุ
    * ใส่ภาพใน content->project->img
    * อาจมีขวดให้เก็บและถามว่า กินหรือไม่ แต่ล่ะขวดจะทำให้หน้าน้องเปลี่ยนไป แบบมีความสุข สดใส ร้องไห้ หน้ามืด หรือตัดมืดไปโพล่ห้องสมุด
    * sound ต่างๆต้องเป็น .wav
## link
**Github:** https://github.com/AnitthaJai-on/ThePuppet
 
**Drive:** https://drive.google.com/drive/folders/1-5tcEpC6WXjrFdVykOzH1vKkwnFAyXOK

Support Game
https://docs.unrealengine.com/en-US/Engine/MediaFramework/HowTo/FileMediaSource/index.html   

## About
* ฉาก 1
   * น้องฝันเห้นหนังสือเล่มหนึ่ง
   * น้องตื่นน้องเดินออกจากห้องนอน
   * ผ่านห้องต่างๆ
   * มีรูปติดผนังอยู่ด้านหลังให้เห็นเมื่อผ่าน 
   * กด F เปิดประตูเข้าห้องสมุด -> เปลี่ยนฉาก
* ฉาก 2
   * น้องเดินเข้ามาในห้องสมุด
   * ผ่านชั้นหนังสือต่างๆ โต๊ะต่างๆ
   * มีโหลแก้วเก็บของประดับไว้ 2-3 อันในห้องสมุด 1 ในนั้นเป็นหนังสือที่น้องเห็นในฝัน
   * กด F ที่โหลต่างๆจะมีคำอธิบายขึ้นมา แต่ของหนังสือจะเป็นจิ๊กซอให้ต่อ 9 ช่อง มี 2 ช่องใส่ไว้แล้ว
   * ต้องตามหาจิ๊กซอที่หายไป 7 ชิ้นในห้องสมุดจะมีกระดาษบอกที่ซ่อนอยู่ที่โหลเลย 
      * 1 'ภาพสิ่งมีชีวิต'(อยู่ตรงผนังที่น้องผ่านฉากแรก)
      * 2 ในถังขยะใกล้ๆ
      * 3-4 'ชั้นหนังสือที่มีตัวอักษรเดียวกับห้องสมุด'(มี B,A)
      * 5 'เหนือหัว' คืออยู่บนเพดานเหนือโหล หาไม้มาเขี่ยเอง
      * 6 กด F อีกทีที่โหลมันจะหล่นลงมา
      * 7 'เมื่อครบ สิ่งที่หาจะปรากฎ' เมื่อเจอครบทั้งหมด ชิ้นที่ 7 จะโพล่มาในมือน้อง(อาจมีคัดซีนตรงนี้ด้วย)
  * ต้องกลับมากดประกอบ 9 ชิ้น ที่โหลหนังสือ
* ฉาก 3
  * ห้องสมุดในโหมดดาร์ก หลังจากเก็บจิ๊กซอร์ครบ 9 ชิ้น
  * จะมีผู้เฝ้ายาม 1 คนยืนแทนที่โหลแก้ว
  * ต้องหลบไม่ให้ผู้เฝ้าประตูเห็น
  * ถ้าผู้เฝ้าประตูเห็น จะย้อนกลับไปที่ห้องนอนใหม่(ตัดฉากให้มืดไป สว่างอีกทีที่ห้องนอน)
  * เริ่มเดินจากห้องนอนใหม่ ภาพสิ่งมีชีวิตจะกลายเป็นภาพนกฮูก พอมาที่ห้องสมุดโหลแก้วจะสามารถกด F ได้ จะกลับมาฉาก 3 อีกครั้ง แต่ผู้เฝ้าจะนอนสลบอยู่ น้องสามารถเดินผ่านฉากไปได้เลย
* ฉาก 4
  * เดินเข้าในป่ามา เดินมาเรื่อยๆ จะเจอนกอูก
  * เดินเข้าไปใกล้ๆจะมีคำพูดนกฮูกโผล่ขึ้นมาแล้วก็คุย
  * ตอบคำถามนกฮูก
  * นกฮูกยอมให้ผ่านเข้าไป สามารถเดินผ่านนกฮูกได้เลย

## สิ่งที่ต้องทำ
* Cutscene
  * [ ] เริ่มต้น ประวัติความเป็นมาของน้องว่าทำไมถึงอยากหาหนังสือเล่มนี้
  * [ ] ช่วงเปลี่ยนฉาก ตอนน้องโดนดึงเข้าหนังสือ
  * [ ] ช่วงเปลี่ยนฉาก (ถ้าโดนคนเฝ้าห้องสมุดในมินิเกมจับ จะมีคัดซีนเพื่อนน้องถือหนังสืออยู่)
  
* System
  * [X] หน้าแรกของระบบ
  * [X] หน้าตั้งค่า
  * [X] กดปิดเกม
  * [ ] save/load
  * [X] ทำให้ตัวคนขยับ WASD
  * [ ] F,enter->เก็บของ เปิดประตู spanbar->อาจเป็นมินิเกมหลบ
  * [ ] มินิเกม คือให้หลบคนเฝ้าห้องสมุด
  * [ ] puzzle แรกที่เก็บจิ๊กซอ
  
* Scene
  * [X] ฉากในห้องนอน
  * [ ] ฉากที่น้องเดินผ่านห้องต่างๆ
  * [ ] ฉากบันไดลงมาข้างล่าง มีรูปติดอยู่ที่ผนัง
  * [ ] ฉากในห้องสมุดใหญ่ๆ มีชั้นหนังสือ A-H มีแท่นวางหนังสือในโหลแก้ว
  * [X] ฉากในป่านำไปสู่ตอนจบที่เป็นคำถาม
  
* Character
  * [ ] น้อง
  * [ ] คนเฝ้ายามในห้องสมุด
  * [ ] นกฮูก

* Sound


* Font
  * https://fonts.google.com/specimen/Turret+Road?query=turre
  * https://fonts.google.com/specimen/Syne+Mono?query=syne
  * https://fonts.google.com/specimen/Cabin+Sketch?query=cabin
