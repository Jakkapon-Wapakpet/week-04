# 🎨 Week 04 — CSS Exercises & Capstone Project

ยินดีต้อนรับสู่คลังแบบฝึกหัดพัฒนาทักษะ **CSS (Cascading Style Sheets)** ประจำสัปดาห์ที่ 4 โครงการ **JSD13** คลังนี้รวบรวมแบบฝึกหัดการแก้บั๊ก (Debug), การเติมคำคำสั่ง (Partial), และการเขียนสไตล์การจัดวางตั้งแต่เริ่มต้น (Scratch) ครอบคลุมตั้งแต่นิพจน์พื้นฐานไปจนถึงระดับสูง

---

## 📂 โครงสร้างแบบฝึกหัด (Course Structure)

บทเรียนและแบบฝึกหัดถูกแบ่งออกเป็น **9 Modules** และ **1 Capstone Project**:

### 🎯 Module 01 — Selectors & Specificity
* **Debug — Specificity:** แก้ไขลำดับการเขียนทับและความเจาะจงของ CSS Selectors
* **Partial — Selectors:** ฝึกใช้ ID, Class, Element, และ Pseudo-class เลือกแท็กที่ต้องการ
* **Scratch — Style an Article:** ตกแต่งบทความ HTML ให้ออกมาสวยงามด้วยตนเอง

### 🔗 Module 02 — Combinators & Pseudo-classes
* **Debug — Combinators:** แก้ไขการใช้ Descendant (` `), Child (`>`), และ Sibling (`+`) Combinators
* **Partial — Pseudo-classes:** ฝึกใช้ `:hover`, `:last-child`, `:nth-child()`, และ `:first-letter`
* **Scratch — Navigation Menu:** สร้างแถบเมนูนำทาง (Navbar) พร้อมเมนูดร็อปดาวน์ (Dropdown Menu)

### 🧱 Module 03 — BEM Architecture
* **Debug — BEM:** แก้ไขชื่อคลาสให้ถูกต้องตามหลักระเบียบการตั้งชื่อ Block__Element--Modifier
* **Partial — BEM:** ฝึกเติมคลาสแบบ BEM ให้กับองค์ประกอบการ์ดและปุ่มต่าง ๆ
* **Scratch — Media Object:** ออกแบบโครงสร้างชิ้นส่วนสื่อ (Media Component) ด้วย BEM ตั้งแต่เริ่มต้น

### ✍️ Module 04 — Typography
* **Debug — Fonts:** แก้ไขฟอนต์สำรอง (Font Fallback), ความหนาอักษร (Font Weight), และการเชื่อมต่อ Google Fonts
* **Partial — Typography:** กำหนดความสูงบรรทัด (Line Height), ระยะห่างตัวอักษร (Letter Spacing), และประเภทฟอนต์
* **Scratch — Blog Post:** จัดรูปแบบตัวอักษรและหน้าบทความบล็อกให้อ่านง่ายและสวยงามตามหลัก Typography

### 🎨 Module 05 — Colors & CSS Variables
* **Debug — Colors:** แก้ไขค่า Hex, RGBA, และการปรับเปลี่ยนคอนทราสต์ของสี (Contrast Ratio)
* **Partial — Color Values:** ฝึกใช้สีชื่อ (Named), Hex, RGB, RGBA, และ HSL
* **Scratch — Color Scheme:** สร้างชุดตัวแปรสี (CSS Custom Properties / Variables) สำหรับแต่งธีมเว็บ (Dark/Light Theme)

### 📦 Module 06 — Box Model
* **Debug — Box Model:** แก้ไขการคำนวณขนาดกล่องด้วย `box-sizing: border-box` และปัญหา Margin Collapse
* **Partial — Spacing:** ฝึกเติมค่า Padding, Margin, Border, และ Border Radius
* **Scratch — Testimonial Card:** สร้างการ์ดคำนิยมพร้อมรูปภาพและข้อความอธิบาย

### 📐 Module 07 — Display & Flexbox
* **Debug — Display:** แก้ไขการวางตำแหน่งแนวนอนและแนวตั้งด้วย Flexbox
* **Partial — Flexbox:** ฝึกใช้ `justify-content`, `align-items`, `flex-direction`, และ `flex-wrap`
* **Scratch — Responsive Cards:** สร้างระบบการ์ดที่ยืดหยุ่นและปรับตัวตามขนาดหน้าจอ

### 📍 Module 08 — Position
* **Debug — Position:** แก้ไขตำแหน่งแบบ `fixed`, `relative`, `absolute`, และ `sticky`
* **Partial — Badge Overlay:** ฝึกวางป้ายกำกับ (Badge) และ Tooltip ซ้อนบนองค์ประกอบ
* **Scratch — Full Page Layout:** จัดโครงสร้างหน้าเว็บที่มี Header ตรึงบนสุด และ Sidebar ด้านข้าง

### 📱 Module 09 — Responsive Design
* **Debug — Breakpoints:** แก้ไขการจัดเรียง Media Queries ตามหลัก Mobile-first
* **Partial — Tablet Layout:** ปรับเปลี่ยนเลย์เอาต์จากแนวตั้งบนมือถือเป็นแนวขนานบนแท็บเล็ต
* **Scratch — Full Responsive Page:** เขียน CSS สำหรับหน้าเว็บที่รองรับทั้ง Mobile, Tablet, และ Desktop

---

## 🍽️ 🏆 Capstone Project — Restaurant Menu Page
โปรเจกต์รวบยอดความรู้ที่นำทักษะทั้งหมดตั้งแต่ Module 1–9 มาประยุกต์ใช้เพื่อสร้างหน้าเว็บเมนูร้านอาหารภาษาไทยที่สวยงาม ยืดหยุ่น และรองรับการเปิดบนทุกอุปกรณ์

---

## 🚀 วิธีการเปิดใช้งาน (Getting Started)

1. เปิดไฟล์ `index.html` หลักด้วยเว็บเบราว์เซอร์ของคุณ หรือใช้งาน **Live Server** Extension บน VS Code
2. คลิกเลือกแบบฝึกหัดในแต่ละ Module เพื่อดูโจทย์ สไตล์ และผลลัพธ์บนหน้าจอได้ทันที

---
*จัดทำขึ้นสำหรับการศึกษาและฝึกฝนทักษะการพัฒนาเว็บไซต์ (JSD13)*
