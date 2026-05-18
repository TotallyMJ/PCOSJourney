# 🌸 Bloom — PMOS Wellness Journal

> แอปบันทึกประจำวัน + ติดตามรอบเดือน + medical tracking สำหรับคน PMOS
> ออกแบบให้ใช้ง่าย ไม่กดดัน ไม่ซีเรียส และเข้าใจร่างกายตัวเองได้มากขึ้น

🌐 **เปิดใช้งานเลย:** https://totallymj.github.io/PCOSJourney/

---

## ✨ Features

### 🏠 Dashboard (หน้าแรก)
- **Greeting** เรียกชื่อ + ตามช่วงเวลา (อรุณสวัสดิ์ / บ่ายๆ / ราตรีสวัสดิ์)
- **Streak** + consistency 30 วัน · ไม่กดดัน
- **Phase awareness** — บอกว่าตอนนี้อยู่ช่วงไหนของรอบเดือน + tips สำหรับ phase นั้น (Follicular / Ovulation / Luteal / PMS / Period)
- **Period countdown** — คาดการณ์รอบถัดไป + แจ้งล่วงหน้า 3 วัน
- **Smart reminders** — แจ้งเตือนแบบ context-aware:
  - ดึกเกินไป → ลองนอนก่อน 23:00
  - นอนน้อย 3+ วัน → ลองนอนเพิ่ม 30 นาที
  - ไม่ออกกำลังกาย → เดิน 10 นาทีก็ดี
  - ไม่บันทึก 3+ วัน → caring welcome back
  - PMS + craving → ลอง protein ก่อนของหวาน
- **Health overview** — น้ำหนัก + BMI + เป้าหมาย · TDEE · mood เฉลี่ย · ชั่วโมงนอน
- **Insights** — auto-generated จากข้อมูล (เช่น "วันที่นอน ≥ 7 ชม. พลังงานดีกว่า 1.5 จุด")
- **Doctor prep banner** — แสดงเมื่อมีนัดในอีก 3 วัน (ซ่อนเมื่อนัดผ่านไป)

### 🌸 บันทึกวันนี้ (Daily — Accordion)
- **12 modules** เรียงตาม PMOS priority (period → symptoms → pain → mood → energy → sleep → weight → meals → water → exercise → meds → journal)
- **Accordion UI** — ขยาย/ปิดได้ · ค้างเปิดข้ามการ render
- **Tap-first** กรอกได้ใน 2 นาที · summary ในหัวการ์ดทุกอัน
- **Date navigator** ← / → / picker → **ดูและแก้ไขย้อนหลังได้ทุกวัน**
- **Auto-save** อัตโนมัติ · ไม่ต้องกดบันทึก
- **Modules ปรับเองได้** — drag-drop เรียง + toggle on/off ใน Settings

#### Module details:
- 🩸 **ประจำเดือน** — flow (ไม่มี / กระปริดกระปรอย / น้อย / ปานกลาง / มาก)
- 🌡️ **อาการ** — preset 9 อาการ + เพิ่ม custom · ความรุนแรง 3 ระดับ (แตะซ้ำเพื่อปรับ)
- 💊 **ระดับความปวด** 0-5 + note
- 😊 **อารมณ์** — 8 mood แบ่งกลุ่ม "รู้สึกดี" / "รู้สึกไม่ดี"
- ⚡ **พลังงาน** 1-5 พร้อม visual scale "หมดแรง → เต็มที่"
- 🌙 **การนอน** — time picker เข้านอน / ตื่น → คำนวณชั่วโมง auto
- ⚖️ **น้ำหนัก** — ± buttons · แสดง BMI ทันที
- 🥗 **อาหาร** — **chip input** แต่ละ chip = 1 เมนู (พิมพ์ + Enter) · autocomplete จากประวัติทั้งหมด · ลบประวัติได้
- 💧 **น้ำดื่ม** — เป้าคำนวณจาก น้ำหนัก × 30-35 ml/kg
- 🏃 **ออกกำลังกาย** — type + นาที (optional) + intensity
- 💊 **ยา/supplement** — checklist · multi-time slots · ก่อน/หลังอาหาร
- 📝 **journal** — เขียนอิสระ + prompts (สิ่งดี / สังเกต / พรุ่งนี้)

### 📊 รายสัปดาห์
- **Trend line charts** 4 metrics × 7 วัน (mood / energy / sleep / pain) — tap/hover dot เห็นค่าและวันที่
- **Insights** auto-generated
- ค่าเฉลี่ย · symptom frequency · exercise log
- **Meds adherence** % per med (filter ตาม active dates)

### 📅 รายเดือน
- **🎯 3 Takeaways** — auto-detect 3 ข้อสำคัญ (ดีขึ้น / ต้องสังเกต / ทำได้ดี)
- **📅 Calendar heatmap** — สีตามพลังงาน · จุดม่วง = มีบันทึก · **แตะวันใดก็ได้ดูบันทึกเต็ม**
- **🌟 PMOS Cycle Regularity Score** — เกรด A/B/C/D + คำแนะนำ
- **🔬 Phase × Symptom** — อาการแยกตามช่วงรอบเดือน
- **📊 ภาพรวม + เทียบเดือนก่อน** (delta chips: ▲ ดีขึ้น / ▼ แย่ลง)
- **😊 Mood distribution** — segmented bar
- **🥗 Food correlation** — auto-detect อาหารที่กินวันพลังงานดี/ต่ำ
- **💊 Meds adherence** — day-dot grid (เหมือน GitHub contributions)
- **📈 Trends 6 เดือน** — พลังงาน · symptom top 3 · cycle length · น้ำหนัก

### 🌙 รอบเดือน + Medical
- **ปฏิทินรอบ** + 3-month mini calendar overview
- **🏥 นัดหมอ** — แบ่ง section: 🩷 วันนี้ / 🔮 ที่กำลังจะมา / 🕘 ที่ผ่านมา
  - เพิ่มเวลานัด (HH:MM) · color-code วันนี้/อนาคต/อดีต · แก้ไขได้
  - Autocomplete จากประวัติ (ชื่อหมอ + คลินิก) · ลบประวัติได้
- **💉 ผลแล็ป** — auto-flag จาก ref range · trend detection (วัดซ้ำ ≥ 2 ครั้ง)
  - 20 PMOS labs preset + custom names · autocomplete ครบ
- **📝 บันทึกการแพทย์** — คำถาม / ข้อสังเกต / อื่นๆ
- **📋 Doctor Prep View** — printable PDF summary (ข้อมูล 30 วัน + lab + คำถามค้าง)

### ☁️ Cloud Sync (GitHub Gist) — **NEW**
- ตั้งค่าครั้งเดียวด้วย Personal Access Token (5 นาที)
- **Auto-backup** ทุกครั้งที่บันทึก
- **Sync ข้าม device** — มือถือ ↔ PC
- ใช้ Gist ส่วนตัวบน GitHub · ฟรี 100%
- ลบ token / ลบ Gist ในคลาวด์ได้ทุกเมื่อ

### 📤 Manual Backup
- **Export JSON** — โหลดไฟล์ backup เก็บไว้
- **Import JSON** — โหลดกลับมาทับข้อมูลปัจจุบัน

### ⚙️ Settings
- **Profile** — ชื่อ (ใช้ใน greeting) · ตั้งใจ · DOB → คำนวณอายุ
- **น้ำหนัก** — preserve baseline + แสดง progress ↑/↓ จากตอนเริ่ม
- **น้ำหนักเป้าหมาย** + progress bar
- **ส่วนสูง** · **รอบเอว/สะโพก** (WHR auto)
- **เป้าหมายสุขภาพ** → คำนวณ TDEE + protein target
- **รอบเดือนเฉลี่ย** (วัน)
- **ยา/supplement** — multi-time slots · before/after meal · **⏸️ หยุดยา** (preserve past data) · ▶️ เริ่มใหม่ได้
- **Module reorder** — drag-drop ลำดับ
- **Theme** light / dark (auto จาก system)
- **Sample data** 60 วันสำหรับลองดู
- **Reset / Clear data** (preserve sync token)

---

## 📱 ใช้บนมือถือ
1. เปิด URL บน Safari (iOS) หรือ Chrome (Android)
2. Add to Home Screen → ไอคอน 🌸 ขึ้นบนหน้าจอ
3. ใช้ได้เหมือนแอป native
4. **Offline ได้** ผ่าน service worker
5. **Auto-update** เมื่อมีเวอร์ชันใหม่

---

## 🚀 Run

### วิธี 1: ใช้ผ่านเว็บ (แนะนำ)
เปิด https://totallymj.github.io/PCOSJourney/ บนเบราว์เซอร์ → ใช้ได้เลย

### วิธี 2: รันบนเครื่องตัวเอง
ดับเบิลคลิกเปิด `index.html` ในเบราว์เซอร์ → ใช้ได้ทันที ไม่ต้องลงอะไร

ข้อมูลทั้งหมดเก็บใน `localStorage` ของเบราว์เซอร์ (และถ้าเปิด Cloud Sync จะ sync ขึ้น GitHub Gist ส่วนตัวด้วย)

---

## 🔒 Privacy

- **100% local-first** — ข้อมูลเก็บในเครื่องเป็นหลัก
- ไม่มี server centralized · ไม่มี analytics · ไม่มี tracking
- **Cloud sync เป็น opt-in** (ใช้ Gist ส่วนตัวของคุณเอง)
- **Token** เก็บใน localStorage ของเครื่องเท่านั้น · ไม่ sync ไปไหน · ไม่ถูก export
- **PWA Offline** — ใช้งานได้แม้ไม่มีเน็ต

---

## 📜 Changelog (Major Updates)

### v1.5 (PMOS rename + UX polish)
- Renamed PCOS → PMOS (per new medical terminology)
- Tab persistence (reload stays on same page)
- Auto-mark saved · removed manual save button
- Appointment time field + filter passed appointments
- Suppressed password manager popup on text inputs
- Fixed multi-word food names ("chia seed water" = 1 chip)

### v1.4 (Med lifecycle + autocomplete history)
- ⏸️ หยุดยา / ▶️ เริ่มใหม่ (preserve past data)
- Edit appointments / labs / notes
- Autocomplete history for doctor / clinic / lab names
- Manage history with deletable chips
- Chip-style meal input
- Accordion + history panel persist across re-renders

### v1.3 (Visualization upgrade)
- Trend line charts (replace heatmap)
- Tooltips on chart dots
- Phase × Symptom correlation
- PMOS Cycle Regularity Score (A/B/C/D)
- 3 Takeaways monthly
- Color-coded medical sections (today/past/future)
- Meal autocomplete + history management

### v1.2 (Cloud sync + Smart reminders)
- ☁️ Cloud Sync via GitHub Gist (auto-backup + cross-device)
- Import/Export JSON
- Smart reminders (time-of-day + cycle-aware)
- Personalization (name in greetings)
- Date navigator (browse + edit past entries)
- Doctor Prep view (printable PDF)

### v1.1 (PWA + UX restructure)
- PWA support (manifest, service worker, install to home screen)
- Quick Log on home (4-tap, 30 sec)
- Accordion daily log
- Phase tips on home banner
- Help icons on every section
- Restructured monthly summary

### v1.0 (Initial)
- Daily log with 15 modules
- Weekly + Monthly summaries
- Cycle tracker (3-month overview)
- Medical tracking (appointments, labs, notes)
- Settings + onboarding

---

## 🩺 Disclaimer

ข้อมูลในแอปนี้ไม่ใช่คำแนะนำทางการแพทย์ · ปรึกษาแพทย์ของคุณเสมอก่อนเปลี่ยนแปลงการรักษา

แอปนี้เป็นเครื่องมือสำหรับ self-tracking + เอาข้อมูลไปคุยกับหมอ · ไม่ใช่อุปกรณ์การแพทย์

---

Made with care 🌸 for understanding rather than productivity.
