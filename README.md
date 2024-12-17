# travel-in-pathumthani
# git command in this project
git clone https://github.com/k-winph/travel-in-pathumthani.git
git checkout -b development
git add .
git commit -m “init project”
git checkout -b feature/home-page
git add .
git commit -m "เพิ่ม HTML พื้นฐาน"
git add .
- git commit -m "เพิ่มเนื้อหา HTML"
- git checkout development
git checkout -b feature/css
- git add .
- git commit -m "เพิ่ม style ส่วน nav"
- git add .
- git commit -m "เพิ่ม style ส่วน footer"
- git add .
- git commit -m "เพิ่ม style ส่วนข้อความ"
- git add .
- git commit -m "เพิ่ม style ส่วนกรอบรูป"
- git add .
- git commit -m "เพิ่ม style ส่วน hamburger"
- git checkout feature/home-page
- git add .
- git commit -m "เพิ่ม logo บน title"
- git add .
- git commit -m "เพิ่มปุ่ม hamburger"
- git checkout development
- git checkout -b feature/js
- git add .
- git commit -m "เพิ่ม script hamburger"
- git checkout feature/home-page
- git add .
- git commit -m "เรียกใช้งาน script"
- git checkout feature/css
- git add .
- git commit -m "style font"
- git checkout feature/home-page
- git add .
- git commit -m "เรียกใช้ font"
- git checkout development
- git checkout -b feature/about-page
- git add .
- git commit -m "สร้าง HTML พื้นฐาน"
- git add .
- git commit -m "เพิ่มเนื้อหา html"
- git add .
- git commit -m "เพิ่ม logo บน title"
- git add .
- git commit -m "เรียกใช้ font"
- git checkout development
- git checkout -b feature/travel-page
- git add .
- git commit -m "สร้าง html พื้นฐาน"
- git add .
- git commit -m "เพิ่ม html เนื้อหาและรูปภาพประกอบ"
- git add .
- git commit -m "เพิ่มรูป icon และเรียกใช้ font"
- git checkout feature/css
- git add .
- git commit -m "เพิ่ม style กล่อง"
- git checkout development
- git checkout -b feature/contact-page
- git add .
- git commit -m "สร้าง html พื้นฐาน"
- git add .
- git commit -m "เพิ่ม html เนื้อหา"
- git add .
- git commit -m "เพิ่ม icon และเรียกใช้ font"
- git checkout feature/css
- git add .
- git commit -m "เพิ่ม style transition animation"
- git add .
- git commit -m "เพิ่ม style Responsive ของ tablet และ mobile"
- git add .
- git commit -m "เพิ่ม style ปุ่ม submit"
- git checkout development
- git merge feature/js
- git merge feature/css
- git merge feature/home-page
- git merge feature/about-page
- git merge feature/travel-page
- git merge feature/contact-page
- git add .
- git commit -m "แก้ไข error style ไม่ติด"
- git commit -m "เพิ่ม comment ที่มาของรูปภาพ"
- git add .
- git commit -m "README Update"
- git push origin main