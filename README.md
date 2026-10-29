# ชมผลงาน (สำหรับกรรมการ)

เปิดชมได้ทันที ไม่ต้องใช้รหัสผ่าน : https://sarawut2206.github.io/LIFECRAFT-AI-Life-Competency-UP-TO-GROW/

ลิงก์เข้าตรงโหมดกรรมการ : https://sarawut2206.github.io/LIFECRAFT-AI-Life-Competency-UP-TO-GROW/app/?judge=1

โหมดกรรมการแสดงมุมมองนักเรียน ครู ผู้บริหาร 79 ห้อง และแผนภาพโครงสร้างนวัตกรรม โดยใช้ข้อมูลสมมติทั้งหมด ไม่ใช่นักเรียนจริง ไม่บันทึกข้อมูลลงเครื่อง และไม่ส่งข้อมูลออกไปที่ใด ไฟล์เว็บอยู่ในโฟลเดอร์ `docs/`

---
# LIFECRAFT AI — HyperFrames 60-second Promo

## Format
- Duration: 60 seconds
- Canvas: 1920 × 1080 (16:9)
- Language: Thai
- Audio: synthetic Thai phonetic voiceover with original generated background music
- Source basis: `source_app.html`

## Preview and render
```bash
npx hyperframes lint
npx hyperframes inspect --samples 15
npx hyperframes preview
npx hyperframes render --output LIFECRAFT_AI_PROMO_60s_TH.mp4 --quality high
```

The included rendered MP4 was produced in the current environment with FFmpeg because the HyperFrames npm package was not reachable from the local package registry. The project source follows the HyperFrames composition and timeline structure for preview/render in a HyperFrames-enabled environment.
