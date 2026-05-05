# Motion/Craft — Blender Motion Graphics Academy

หลักสูตรไทยสำหรับเรียน Blender Motion Graphics ตั้งแต่เริ่มต้น จนถึงระดับมือโปร — เว็บสื่อการสอนแบบ step-by-step ครอบคลุม 8 โมดูล 30 บทเรียน

[เปิดเว็บเดโม่](./blender-motion-graphics-academy.html)

## สารบัญหลักสูตร

| Module | หัวข้อ | ระดับ | จำนวนบท |
|--------|--------|-------|---------|
| 01 | ปฐมบท — Setup, UI, Navigation | Beginner | 4 |
| 02 | Keyframe Animation | Beginner+ | 4 |
| 03 | Graph Editor & Easing | Intermediate | 3 |
| 04 | Drivers & Constraints | Intermediate | 3 |
| 05 | Geometry Nodes สำหรับ MG | Advanced | 5 |
| 06 | Shading & Animated Materials | Intermediate+ | 3 |
| 07 | Camera, Lighting, ภาษาภาพ | Intermediate+ | 4 |
| 08 | Render & Post-production | Pro | 4 |

## Features

- **Single-file HTML** — ไม่มี dependency ใดๆ เปิดในเบราว์เซอร์ได้เลย
- **Editorial cinematic dark theme** — ออกแบบในสไตล์ studio premium
- **Mock Blender viewport** — มี timeline + keyframe animation ในตัว
- **Cheatsheet ปุ่มลัด** — 4 หมวด พร้อมพิมพ์ติดข้างจอ
- **6 Pro Tips** — เคล็ดลับจากการทำงานจริง
- **Responsive** — ใช้งานได้ทั้ง desktop, tablet, mobile
- **ภาษาไทย 100%** — typography คู่ที่ออกแบบให้อ่านสบาย

## Tech Stack

- HTML5 + CSS3 (Custom properties, Grid, Flexbox)
- Vanilla JavaScript (IntersectionObserver สำหรับ scroll animation)
- Google Fonts: `Fraunces`, `Manrope`, `JetBrains Mono`, `IBM Plex Sans Thai`
- ไม่มี framework, ไม่มี build step

## วิธีใช้งาน

```bash
# clone repo
git clone https://github.com/<your-username>/blender-mg-academy.git
cd blender-mg-academy

# เปิดในเบราว์เซอร์
open blender-motion-graphics-academy.html
# หรือ run local server
python3 -m http.server 8000
```

## Deploy ขึ้น GitHub Pages

1. Push repo ขึ้น GitHub
2. Settings → Pages → Source: `main` branch, folder: `/ (root)`
3. รอประมาณ 1 นาที จะได้ URL เช่น `https://<username>.github.io/blender-mg-academy/`

## License

MIT License — ใช้สอน, แชร์, ดัดแปลงได้อิสระ

## Credits

ออกแบบและพัฒนาในสไตล์ editorial cinematic — สำหรับชุมชน Motion Designer ไทย

---

> _Motion Graphics ที่ดี ไม่ได้เกิดจาก plugin ราคาแพง หรือ render engine ที่ดีที่สุด — มันเกิดจาก timing, contrast และการตัดสินใจที่ละเอียดทุกเฟรม_
