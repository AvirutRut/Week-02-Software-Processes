# การบ้าน

1. โดยทั่วไป การพัฒนาซอฟต์แวร์แบบ incremental developement นั้น จะเหมาะกับการสร้างซอฟต์แวร์ที่ user เองก็ยังมีไอเดียไม่ชัดเจน หรือยังไม่รู้ความต้องการของตัวเอง  ในคำกล่าวข้างต้น เป็นจริงหรือไม่ จงอภิปราย
    - เป็นจริง กล่าวคือ การพัฒนาซอฟต์แวร์แบบ Incremental Developement จะเป็นการแบ่งระบบงานออกเป็นระบบย่อย ๆ ในแต่ละรอบ โดยจะมุ่งเน้นให้ระบบหลักทำงานได้ก่อน และระหว่างการพัฒนา หาก user มี idea เพิ่มเข้ามาก็สามารถนำ idea นั้นเพิ่มเข้ามาในการทำงานรอบถัดไปได้
2. จงเปรียบเทียบข้อแตกต่าง (ข้อดี-ข้อเสียหรือข้อจำกัด) ระหว่างกระบวนการพัฒนาซอฟต์แวร์แบบต่างๆ ที่ท่านรู้จัก 
    - Waterfall 
        - ข้อดี
            - สามารถกำหนดระยะเวลาของแต่ละงานได้
            - เหมาะกับงานขนาดเล็ก
        - ข้อเสีย
            - หากพบข้อผิดพลาดในขั้นตอนที่ผ่านมาแล้วจะไม่สามารถกลับไปแก้ไขได้
            - หากลูกค้าเปลี่ยน requirement จะต้องเริ่มทำงานใหม่ทั้งหมด
            - ไม่ยืดหยุ่นในการเปลี่ยนแปลง
    - Incremental
        - ข้อดี
            - สามารถต่อเติมงานได้โดยไม่ต้องรอให้ Process ทุกอย่างเสร็จสมบูรณ์ก่อน
        - ข้อเสีย 
            - มีความเสี่ยงสูง เนื่องจากมีการนำระบบย่อยมาประกอบรวมกัน
            - ระบบงานย่อยที่ใช้งานอยู่อาจจะทำให้การทำงานสะดุด
3. จงบอกข้อแตกต่างระหว่าง user requirement และ system requirement
    - user requirement ส่วนใหญ่จะอยู่ในรูป UX/UI เป็นความต้องการของผู้ใช้งาน เช่นอยากได้ font สีอะไร ให้จัด layout อย่างไร ฯลฯ
    - system requirement จะเป็นความต้องการของระบบว่าซอฟต์แวร์นั้น ๆ ต้องสามารถทำอะไรได้บ้าง
4. จงยกตัวอย่างเทคโนโลยีที่มีซอฟต์แวร์เข้ามามีส่วนร่วมในอดีต ที่ทำให้คนต้องออกจากงานจำนวนมาก และให้เหตุผลที่เป็นเช่นนั้น
    - ซอฟต์แวร์ชุมสายโทรศัพท์ เนื่องจากในอดีตจะต้องอาศัยพนักงานในการต่อสายโทรศัพท์ไปยังบุคคลที่ผู้ติดต่อต้องการ แต่ในปัจจุบันจะเห็นได้ว่าในการใช้โทรศัพท์จะเป็นการที่ผู้เรียกติดต่อถึงผู้รับโดยตรงโดยไม่ผ่านคนกลาง
5. จากข้อ 3. ในฐานะนักวิศวกรรมซอฟค์แวร์ ท่านมีโอกาสที่จะถูกให้ออกจากงานหรือไม่  และ    ถ้าไม่อยากถูกให้ออกจากงาน ท่านคิดว่าควรทำงานในส่วนใดของกระบวนการ  
    - หากเป็นวิศวกรซอฟต์แวร์ก็ถือได้ว่ามีโอกาสถูกออกจากงานอยู่ส่วนหนึ่ง และหากไม่อยากถูกออกจากงานควรทำงานในส่วนของการวิเคราะห์ระบบ เพราะเป็นการยากที่ซอฟต์แวร์จะสามารถวิเคราะห์ระบบได้ดี