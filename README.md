# มนูญชัยแบบ JIS

**[มนูญชัย](https://github.com/Manoonchai/Manoonchai)** แบบแมปสัญลักษณ์ให้ตรงกับเลย์เอาต์แป้นพิมพ์ญี่ปุ่น (JIS)

## หมายเหตุ

1. ปุ่ม `_` จะเป็น `_ +` บน macOS แต่จะเป็น `+ _` บนลินุกซ์ (xkb)
2. เลย์เอาต์นี้สร้างขึ้นโดยใช้ [hiohlan's forked kiimo](https://github.com/hiohlan/kiimo)  
  (แต่ `kiimo` ยังไม่รองรับปุ่มพิเศษอย่าง `¥` และ `_` จึงจำเป็นต้องแก้ไขด้วยมือไปก่อน)
3. ยังไม่สามารถใช้งานบน **วินโดวส์** ได้ เนื่องจาก MSKLC ไม่รองรับเลย์เอาต์ JIS ทำให้ไม่สามารถแมปปุ่ม `¥` กับ `_` ได้
4. ยังไม่ได้ทำสำหรับ **Chrome OS และ Android (แป้นพิมพ์จริง)** เพราะไม่มีเครื่องสำหรับทดสอบ

# Manoonchai JIS Layout

**[Manoonchai](https://github.com/Manoonchai/Manoonchai)** with symbols mapped to the JIS keyboard layout.

## Notes
1. The `_` key appears as `_ +` on macOS, but as `+ _` on Linux (xkb).
2. This layout is generated via [hiohlan's forked kiimo](https://github.com/hiohlan/kiimo).  
  (However, `kiimo` does **not yet support special keys** such as `¥` and `_`, so they need to be manually edited for now.)
3. **Windows is not supported** yet. MSKLC does not support JIS layouts, and thus this layout cannot be built for Windows (the `¥` and `_` keys cannot be mapped).
4. Chrome OS and Android physical keyboard layouts are also **not supported**, due to the lack of testing devices.

---