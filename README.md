# CP352005 Computer Networks 🌐
### Template Repository สำหรับส่งงานและรายงานผลการเรียนรู้

> **คำชี้แจง:** Repository นี้เป็น **Template ตัวอย่าง** สำหรับนักศึกษารายวิชา **CP352005** ใช้เป็นแนวทางในการจัดโครงสร้างโฟลเดอร์ บันทึกประวัติการทำงาน และส่งงาน (Assignments, Labs และ Certificates) ผ่าน GitHub

---

## 👤 ข้อมูลนักศึกษา (Student Information)
> *ให้นักศึกษาแก้ไขข้อมูลส่วนนี้ให้เป็นข้อมูลจริงของตนเอง*

- **ชื่อ - นามสกุล:** นางสาวขวัญชีวา เข็มแข็ง
- **รหัสนักศึกษา:** 683380651-4
- **กลุ่มเรียน (Section):** Section 4
- **อีเมลมหาวิทยาลัย:** kwanchewa.k@kkumail.com


---

## 📂 โครงสร้าง Repository (Directory Structure)

การจัดวางไฟล์และโฟลเดอร์ใน Repository ควรจัดหมวดหมู่ให้ชัดเจนและเป็นระเบียบ ดังนี้:

```text
CP352005_68XXXXXXX-X/
├── ASSIGNMENTS/                   # โฟลเดอร์เก็บงานการบ้าน / งานที่ได้รับมอบหมาย
│   ├── ASS01/                    # งานการบ้านชุดที่ 1
│   │   └── .gitkeep
│   └── ASS02/                    # งานการบ้านชุดที่ 2 (ตัวอย่าง)
│       ├── CP352005_ASS02.pdf    # รายงานหรือเอกสารประกอบ (.pdf)
│       └── Week1_Sample1.pkt     # ไฟล์จำลองระบบเครือข่าย Cisco Packet Tracer (.pkt)
├── LABORATORY/                    # โฟลเดอร์เก็บงานปฏิบัติการในห้องเรียน (Lab)
│   ├── LAB01/                    # ปฏิบัติการที่ 1
│   └── LAB02/                    # ปฏิบัติการที่ 2
├── CERTIFICATE/                   # โฟลเดอร์เก็บใบประกาศนียบัตร / หลักสูตรอบรม
│   └── CCNA_Enterprise_Networking_Security_and_Automation.pdf
├── .gitignore                     # ไฟล์กำหนดสิ่งที่ไม่ต้องการให้อัปโหลดขึ้น Git
└── README.md                      # ไฟล์สรุปข้อมูลนักศึกษาและตารางติดตามการส่งงาน
```

### รายละเอียดแต่ละโฟลเดอร์
1. **`ASSIGNMENTS/`**: ใช้สำหรับรวบรวมงานการบ้านหรืองานมอบหมายเดี่ยว/กลุ่ม โดยแบ่งโฟลเดอร์ย่อยตามชื่องาน เช่น `ASS01/`, `ASS02/` ภายในประกอบด้วยไฟล์รายงาน PDF, ไฟล์ Cisco Packet Tracer (`.pkt`), หรือโค้ดที่เกี่ยวข้อง
2. **`LABORATORY/`**: ใช้สำหรับเก็บผลการทดลองหรือปฏิบัติการประจำสัปดาห์ เช่น `LAB01/`, `LAB02/`
3. **`CERTIFICATE/`**: ใช้สำหรับจัดเก็บไฟล์หลักฐานใบประกาศนียบัตร เช่น Cisco Networking Academy (CCNA), คอร์สออนไลน์ หรือกิจกรรมที่กำหนดในรายวิชา

---

## 📋 ตารางติดตามการส่งงาน (Submission Tracking)

### 1. การบ้าน (Assignments)
| รหัสงาน | หัวข้องาน | ไฟล์ที่ส่ง | สถานะ | ลิงก์ตรวจงาน |
| :---: | :--- | :---: | :---: | :---: |
| **ASS01** | Assignment 1: Introduction to Network Topology | PDF / PKT | 🟡 Pending | [ดูงานในโฟลเดอร์](ASSIGNMENTS/ASS01/) |
| **ASS02** | Assignment 2: Subnetting & Router Configuration | PDF, PKT | 🟢 Completed | [ดูงานในโฟลเดอร์](ASSIGNMENTS/ASS02/) |
| **ASS03** | Assignment 3: Switching & VLANs | - | ⚪ Not Started | - |

### 2. งานปฏิบัติการ (Laboratory)
| รหัสแลป | หัวข้อปฏิบัติการ | ไฟล์ที่ส่ง | สถานะ | ลิงก์ตรวจงาน |
| :---: | :--- | :---: | :---: | :---: |
| **LAB01** | Lab 1: Basic Packet Tracer & Cable Types | - | ⚪ Not Started | [ดูงานในโฟลเดอร์](LABORATORY/) |
| **LAB02** | Lab 2: IP Addressing & Configuration | - | ⚪ Not Started | [ดูงานในโฟลเดอร์](LABORATORY/) |

### 3. ใบประกาศนียบัตร (Certificates)
| ลำดับ | รายชื่อหลักสูตร / สถาบัน | สถาบันผู้ออกบัตร | สถานะ | เอกสารอ้างอิง |
| :---: | :--- | :---: | :---: | :---: |
| 1 | CCNA: Enterprise Networking, Security, and Automation | Cisco Networking Academy | 🟢 Completed | [ดูใบประกาศ](CERTIFICATE/) |

*หมายเหตุสถานะ: 🟢 Completed (ส่งแล้ว) | 🟡 In Progress / Pending (กำลังดำเนินการ) | ⚪ Not Started (ยังไม่เริ่ม)*

---

## 🚀 แนวทางและข้อกำหนดสำหรับนักศึกษา (Guidelines for Students)

### 1. การสร้างและตั้งชื่อ Repository
- ตั้งชื่อ Repository ตามรูปแบบที่รายวิชากำหนด: **`CP352005_<รหัสนักศึกษา>`**  
  *ตัวอย่าง: `CP352005_683380999-9`*
- ตั้งค่าการเข้าถึง (Repository Visibility) เป็น **`Public`** (เพื่อให้ผู้สอนและ TA เข้าตรวจงานได้)

### 2. กฎการตั้งชื่อไฟล์และจัดระเบียบ
- ห้ามใช้อักขระพิเศษหรือภาษาไทยในชื่อไฟล์และโฟลเดอร์ เช่น หลีกเลี่ยง `งาน1.pkt`, `งานใหม่(1).pdf`
- แนะนำให้ใช้ตัวอักษรภาษาอังกฤษ ตัวเลข และเครื่องหมายขีดกลาง (`-`) หรือขีดล่าง (`_`) เท่านั้น
  * ตัวอย่างที่ดี: `CP352005_ASS02_Report.pdf`, `Topology_Lab02.pkt`

### 3. คำสั่ง Git พื้นฐานสำหรับการส่งงาน

```bash
# 1. Clone repository ของตนเองลงมาที่เครื่อง
git clone https://github.com/<your-username>/CP352005_<your-student-id>.git
cd CP352005_<your-student-id>

# 2. นำไฟล์งานไปวางในโฟลเดอร์ที่ถูกต้อง เช่น ASSIGNMENTS/ASS01/

# 3. ตรวจสอบสถานะการเปลี่ยนแปลง
git status

# 4. เพิ่มไฟล์เข้า staging area
git add .

# 5. Commit พร้อมระบุข้อความอธิบายการส่งงานที่ชัดเจน
git commit -m "Submit Assignment 02: Report and Packet Tracer file"

# 6. Push งานขึ้นสู่ GitHub
git push origin main
```

### 4. ข้อพึงระวังและจริยธรรมทางวิชาการ (Academic Integrity)
- **กำหนดส่ง (Deadline):** ระบบจะยึดเวลาตาม **Timestamp ของ Git Commit สุดท้าย** บน GitHub ก่อนเวลาสิ้นสุดการส่งงาน
- **ความซื่อสัตย์:** งานทุกชิ้นต้องเป็นผลงานของตนเอง ห้ามคัดลอกไฟล์ Packet Tracer (`.pkt`) หรือรายงานของผู้อื่น การทุจริตจะมีผลต่อคะแนนความประพฤติและคะแนนรายวิชาตามเกณฑ์ของมหาวิทยาลัย

---

## 📞 ช่องทางการติดต่อ (Contact & Support)

หากพบปัญหาในการส่งงานหรือมีข้อสงสัยเกี่ยวกับโจทย์ สามารถติดต่ออาจารย์ผู้สอนหรือผู้ช่วยสอน (TA) ได้ผ่านช่องทางดังนี้:
- **ผู้ช่วยสอน (TA):** พี่ TA ประจำรายวิชา CP352005
- **ห้องเรียน / กลุ่มติดต่อ:** MS Teams / Google Classroom ประจำรายวิชา
- **วิทยาลัยการคอมพิวเตอร์ มหาวิทยาลัยขอนแก่น (College of Computing, Khon Kaen University)**
