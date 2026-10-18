# วิธีสร้างรายงานด้วย Microsoft Word

คู่มือ หน้า 31-49 (ภาพหน้าจอเป็น Word ภาษาอังกฤษ) ชื่อเมนูอ่านจากภาพ ข้อที่ไม่ใช่ของคู่มือติดป้ายไว้

เลขหน้าคือเลขที่พิมพ์ในคู่มือ (หน้า PDF = เลขนั้น + 1)

## ปกรายงาน — Cover Page (หน้า 31)
1. เปิดเอกสาร Word
2. แท็บ **Insert** → **Cover Page**
3. เลือกแบบปก (รายการ Built-in เช่น Austin, Banded, Facet, Filigree, Grid, Integral) ปรับแต่งหรือเพิ่มภาพได้
4. พิมพ์ข้อความบนแบบปก เช่น ชื่อเรื่อง ปี ชื่อผู้จัดทำ
- ลบปก: Insert → Cover Page → **Remove Current Cover Page**
- ตัวอย่างปกใน Word ของคู่มือ (รูปที่ 1) เป็นปกสีมีรูป ซึ่งต่างจากผังปกในหน้า 20 ที่เป็นข้อความล้วน เนื้อหาปกให้ยึดผังหน้า 20 (formatting.md)

## สารบัญอัตโนมัติ — Table of Contents (หน้า 32-34)
1. คลุมหัวข้อ แล้วกำหนดสไตล์ที่ **Home → Styles**
   - **Heading 1** = หัวข้อเรื่องใหญ่สุด เช่น 1. บทนำ
   - **Heading 2** = หัวข้อย่อย เช่น 1.1 ประโยชน์ของงานวิจัย
   - **Heading 3** = หัวข้อย่อย ๆ เช่น 1.1.1 ประโยชน์ของงานวิจัยด้านคุณภาพชีวิต
   - กำหนดต่อไปจนถึงหัวข้อย่อยสุดท้าย
2. แท็บ **References** → **Table of Contents** → เลือก **Automatic Table 1** (หัวเรื่อง "Contents") หรือ **Automatic Table 2** ("Table of Contents") (มีตัวเลือก Manual Table, Custom Table of Contents..., Remove Table of Contents ด้วย)
- ผลลัพธ์ในรูปที่ 4: หัวเรื่อง "สารบัญ" แถว "เรื่อง ... หน้า" แล้วรายการ คำนำ (ก), 1. บทนำ, ... , บทสรุป, บรรณานุกรม มีจุดไข่ปลาและเลขหน้าชิดขวา หัวข้อย่อยเยื้องเข้า
- เอาหัวข้อออกจากสารบัญ: คลุมหัวข้อ → Home → Styles → **Normal** เพิ่มหัวข้อ: คลุมแล้วกำหนด Heading
- **ทุกครั้งที่เพิ่ม ลด หรือแก้หัวข้อ ต้องอัปเดต:** References → **Update Table** หรือคลิกที่สารบัญแล้วกด **Update Table...**
- (ที่ว่าควรทำเลขหน้าในสารบัญหลังเนื้อหาเสร็จ อยู่ในหน้า 2)

## เชิงอรรถ — Footnote (หน้า 35)
ใช้เขียนคำอธิบายเพิ่มเติม หรือบอกแหล่งที่มา ท้ายหน้ากระดาษ
1. คลิกที่ข้อความที่ต้องการอธิบาย
2. **References** → **Insert Footnote**
- ลบ: คลุมตัวเลขของ Footnote แล้วกด Delete
- **หมายเหตุ:** ข้อความบอกว่าใช้เครื่องหมายดอกจัน * กำกับ แต่ภาพตัวอย่าง (รูปที่ 6) เป็นเลขยกกำกับอัตโนมัติและมีเส้นคั่นเหนือเชิงอรรถ ใช้แบบใดก็ได้ (Word ใส่เลขยกให้อัตโนมัติ) ไม่ต้องหยุดถาม

## ย่อหน้าด้วยแท็บ — Tab (หน้า 36-37)
ค่าปริยายของ Word: แท็บทุก 0.5 นิ้ว = 1.27 ซม. (ภาพรูปที่ 7 ตั้งไว้ 1.25 ซม. ซึ่งไม่ตรงข้อความ)
- วิธีที่ 1: ดับเบิลคลิกที่ไม้บรรทัด (Ruler) → ระบุ Tab stop position → ถ้าต้องการ Leader เลือกก่อน → **Set** → **OK**
- วิธีที่ 2: **Home → Paragraph (Paragraph Settings) → Tabs...** ตั้งค่าแบบเดียวกัน
- เปิดปุ่ม **Show/Hide (¶)** เพื่อดูสัญลักษณ์ Tab (ลูกศร →) และเห็นว่าย่อหน้าเยื้องด้วย Tab หรือเคาะวรรค

## ระยะห่างบรรทัด — Line Spacing (หน้า 38)
ค่ามาตรฐาน 1.0 (Single) ต้องการ 1.15: เลือกข้อความ → ปุ่ม Line and Paragraph Spacing (Home) → **1.15** (ตัวเลือกมี 1.0, 1.15, 1.5, 2.0, 2.5, 3.0)

## ระยะห่างระหว่างย่อหน้า (หน้า 39)
เลือกย่อหน้า → แท็บ **Layout (Page Layout)** → กลุ่ม **Paragraph** → **Spacing: Before / After** เช่น **6 pt**

## หัวกระดาษและท้ายกระดาษ — Header & Footer (หน้า 40)
1. แท็บ **Insert** → **Header** หรือ **Footer** → เลือกรูปแบบ (เช่น Blank, Blank (Three Columns), Austin, Banded)
2. ในโหมด Header & Footer Tools: ใส่ข้อความ รูป เลขหน้า
   - กลุ่ม Header & Footer: Header, Footer, Page Number
   - กลุ่ม Insert: Date & Time, Document Info, Quick Parts, Pictures, Online Pictures
   - กลุ่ม Navigation: Go to Header, Go to Footer, Previous, Next, Link to Previous
   - กลุ่ม Options: **Different First Page**, Different Odd & Even Pages, Show Document Text
   - กลุ่ม Position: Header from Top, Footer from Bottom (ในภาพ 1.27 ซม. เป็นค่าปริยาย ไม่ใช่ข้อกำหนด)
   - Close Header and Footer

## เลขหน้า — Page Number (หน้า 41)
**Insert → Page Number** (กลุ่ม Header & Footer) → เลือกตำแหน่ง: Top of Page / Bottom of Page / Page Margins / Current Position และรูปแบบ (เช่น Plain Number 1/2/3 ซึ่ง 3 คือชิดขวา) / **Format Page Numbers...** / Remove Page Numbers
- ตำแหน่งที่คู่มือใช้ในตัวอย่างคือ**มุมขวาบน** (ดู formatting.md)

## ลายน้ำ — Watermark (หน้า 42)
**Design → Watermark** → เลือกแบบสำเร็จรูป หรือ **Custom Watermark...** (กล่อง Printed Watermark: No watermark / Picture watermark / Text watermark; ตั้ง Language, Text, Font, Size, Color, Layout Diagonal/Horizontal, Semitransparent) → Apply/OK
- (คู่มือไม่ได้บังคับให้ใส่ลายน้ำในรายงาน)

## ตัวคั่นหน้า — Break (หน้า 43)
- **ขึ้นหน้าใหม่ (Page Break):** วางเคอร์เซอร์ → แท็บ **Layout** → **Breaks** → Page Breaks → **Page** (ใช้เมื่อต้องการขึ้นหน้าใหม่ทั้งที่ข้อความยังไม่เต็มหน้า เช่น พิมพ์คำนำไม่กี่บรรทัดแล้วขึ้นหน้าใหม่ทำสารบัญ)
- **คนละรูปแบบในไฟล์เดียว (Section Break):** Layout → Breaks → Section Breaks → **Next Page** (ตัวเลือกอื่น: Continuous, Even Page, Odd Page)
- กลุ่ม Page Breaks ยังมี Column และ Text Wrapping

## คอลัมน์ — Columns (หน้า 44)
(ไม่ใช้ในรายงานปกติ) **Layout → Columns** → One, Two, Three, Left, Right หรือ **More Columns...** (Presets, Number of columns, Width and spacing, Equal column width, Apply to: Whole document / This point forward / Selected text, Line between)

## บรรณานุกรมอัตโนมัติ (หน้า 45-46)
1. **References → Insert Citation → Add New Source...** เลือก Type of Source (เช่น Book) และ Language กรอก Author (หรือเลือก Corporate Author), Title, Year, City, Publisher แล้ว OK (กล่อง "Create Source" มี Tag name ด้วย)
2. เลือก **Style** ที่ปุ่ม Style (รายการมี APA, Chicago, GB7714, GOST, Harvard - Anglia, IEEE, ISO 690, MLA, SIST02)
3. **References → Bibliography** → เลือกรูปแบบ (Bibliography / References / Works Cited) หรือ Insert Bibliography ผลลัพธ์เป็นกล่องที่มีแถบ "Update Citations and Bibliography"
- **หมายเหตุ (ยืนยันจากภาพหน้า 46):** รายการ Style แสดง "**APA Sixth Edition**" ไม่ใช่ 7th และตัวอย่างที่ Word สร้างมี "เมือง: สำนักพิมพ์" ซึ่งไม่ตรงตัวอย่าง 7th ของคู่มือ ดูหมายเหตุใน bibliography.md (เรื่องนี้ผู้ใช้ให้ยืดหยุ่น ไม่ต้องเคร่ง)
- ที่ต้องใช้เครื่องมือ Word เพราะต้องเรียงชื่อผู้แต่งตามพจนานุกรมให้ถูกต้องและประหยัดเวลา (หน้า 45)

## แบ่งส่วนเอกสารและใส่เลขหน้าต่างกัน — Section (หน้า 47-49)
เมื่อต้องการเลขหน้าเฉพาะส่วนเนื้อหา เริ่มที่ 1 โดยคำนำและสารบัญไม่ใส่เลขหน้า หรือใช้ ก ข ... ในไฟล์เดียวกัน:
1. คลิกหน้าที่จะเริ่ม Section ใหม่
2. **Layout → Breaks → Section Breaks → Next Page**
3. ใส่ **Page Number** ในแต่ละ Section (Section 1, 2, 3 ...) ที่ Header/Footer ของแต่ละ Section (ป้าย "Same as Previous" แสดงว่าเชื่อมกับ Section ก่อนหน้า)
4. กำหนดรูปแบบที่ **Format Page Numbers...** (กล่อง Page Number Format): Number format เป็น 1, 2, 3 หรือ ก, ข, ค และเลือก **Continue from previous section** หรือ **Start at**
5. แบ่งส่วนเพิ่มได้ตามเหมาะสม

ตัวอย่างหน้า 49 (รูปที่ 24): Section 1 = ปก (Different First Page ไม่มีเลข) / Section 2 = คำนำ สารบัญ ใช้ ก, ข / Section 3 = เนื้อหา เริ่มที่ 1 เลขหน้าอยู่มุมขวาบน

**ไม่ใช่ข้อกำหนดของคู่มือ (เทคนิคทั่วไปของ Word):** ถ้า Section ใหม่ยังใช้เลขหน้าต่อจากส่วนก่อน ให้ปิด Link to Previous ใน Header/Footer ของ Section นั้น
