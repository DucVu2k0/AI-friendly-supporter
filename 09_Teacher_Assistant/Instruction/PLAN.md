# Kế Hoạch Xử Lý Tài Liệu Toán & KHTN Cấp 2 (Lớp 6-9)

## 📋 Tóm Tắt Kế Hoạch
**Mục tiêu:** Tạo bộ tài liệu hỗ trợ giảng dạy và kiểm tra Toán & KHTN cho cấp 2
- Phân tích tài liệu SGK hiện có
- Trích xuất công thức, khái niệm theo lớp
- Tạo bộ Skill files cho từng môn/lớp

---

## 🔍 Các Tài Liệu Hiện Có

### Lớp 7
- **Toán**: SGK7_Chan_troi_sang_tao.pdf
  - Chủ đề: Số nguyên, phân số, hình học cơ bản

### Lớp 8
- **Toán Tập 1**: SGK_Toan_tap1_Ket_noi.pdf (Kết nối)
- **Toán Tập 2**: SGK_Toan_tap2_Ket_noi.pdf (Kết nối)
- **Toán Tập 1**: SGK_Toan_tap1_Chan_troi.pdf (Chân trời)
- **Toán Tập 2**: SGK_Toan_tap2_Chan_troi.pdf (Chân trời)
- **KHTN**: SGK_8_KHTN_Chan_troi.pdf
  - Chủ đề: Vật lý, Hóa học, Sinh học lớp 8

### Lớp 9
- **Toán Tập 1**: SGK_Toan_tap1_Chan_troi.pdf
- **Toán Tập 2**: SGK_Toan_tap2_Chan_troi.pdf
- **KHTN**: SGK_KHTN_9_Chan_troi.pdf
  - Chủ đề: Vật lý, Hóa học, Sinh học lớp 9

---

## 📝 Quy Trình Xử Lý Chi Tiết

### Bước 1: Phân Tích & Trích Xuất
**Từ file PDF → Tài liệu Skill**

#### Toán Lớp 7
- [ ] Đọc SGK7_Chan_troi_sang_tao.pdf
- [ ] Trích xuất: Số hữu tỉ, phân số, luỹ thừa, hình học phẳng
- [ ] Công thức: Cộng/trừ/nhân/chia phân số, tính diện tích, chu vi
- [ ] Output: `Skill/Toan_Lop_7.md`

#### Toán Lớp 8
- [ ] Đọc 2 tập từ cả Kết nối & Chân trời
- [ ] Trích xuất: Đa thức, phương trình, hình học (tam giác, tứ giác)
- [ ] Công thức: Khai triển đa thức, giải phương trình, định lý Pytago
- [ ] Output:
  - `Skill/Toan_Lop_8_Tap1.md`
  - `Skill/Toan_Lop_8_Tap2.md`

#### Toán Lớp 9
- [ ] Đọc 2 tập Chân trời
- [ ] Trích xuất: Bậc 2, hệ phương trình, hình học tròn
- [ ] Công thức: Công thức nghiệm, định lý Viet, đường tròn
- [ ] Output:
  - `Skill/Toan_Lop_9_Tap1.md`
  - `Skill/Toan_Lop_9_Tap2.md`

#### KHTN Lớp 8
- [ ] Đọc SGK_8_KHTN_Chan_troi.pdf
- [ ] Trích xuất: Cơ học (lực, công, năng lượng), Hóa (nguyên tắc, phản ứng), Sinh (tế bào, sinh sản)
- [ ] Output:
  - `Skill/KHTN_Lop_8_Vat_Ly.md`
  - `Skill/KHTN_Lop_8_Hoa_Hoc.md`
  - `Skill/KHTN_Lop_8_Sinh_Hoc.md`

#### KHTN Lớp 9
- [ ] Đọc SGK_KHTN_9_Chan_troi.pdf
- [ ] Trích xuất: Điện, từ, cơ học nâng cao; Hóa học nâng cao; Sinh học nâng cao
- [ ] Output:
  - `Skill/KHTN_Lop_9_Vat_Ly.md`
  - `Skill/KHTN_Lop_9_Hoa_Hoc.md`
  - `Skill/KHTN_Lop_9_Sinh_Hoc.md`

---

## 🎯 Cấu Trúc File Skill

Mỗi file Skill sẽ có format:

```markdown
# [Môn Học] Lớp [N] - [Tập/Phần]

## 1. Khái Niệm Cơ Bản
- Định nghĩa
- Các tính chất

## 2. Công Thức & Định Lý
- Công thức 1: Công dụng
- Công thức 2: Công dụng
- ...

## 3. Phương Pháp Giải Bài Tập
- Dạng bài 1
- Dạng bài 2

## 4. Ví Dụ Minh Họa
- Ví dụ 1 (có lời giải)
- Ví dụ 2 (có lời giải)

## 5. Lưu Ý Quan Trọng
```

**Yêu cầu:**
- ≤ 200 dòng/file
- Trích dẫn chính xác từ SGK (trang...)
- Công thức chuẩn LaTeX hoặc ký hiệu rõ ràng

---

## 📚 Danh Sách File Output (Dự kiến)

### Toán
- [ ] `Skill/Toan_Lop_7.md` (≤200 dòng)
- [ ] `Skill/Toan_Lop_8_Tap1.md` (≤200 dòng)
- [ ] `Skill/Toan_Lop_8_Tap2.md` (≤200 dòng)
- [ ] `Skill/Toan_Lop_9_Tap1.md` (≤200 dòng)
- [ ] `Skill/Toan_Lop_9_Tap2.md` (≤200 dòng)

### KHTN
- [ ] `Skill/KHTN_Lop_8_Vat_Ly.md` (≤200 dòng)
- [ ] `Skill/KHTN_Lop_8_Hoa_Hoc.md` (≤200 dòng)
- [ ] `Skill/KHTN_Lop_8_Sinh_Hoc.md` (≤200 dòng)
- [ ] `Skill/KHTN_Lop_9_Vat_Ly.md` (≤200 dòng)
- [ ] `Skill/KHTN_Lop_9_Hoa_Hoc.md` (≤200 dòng)
- [ ] `Skill/KHTN_Lop_9_Sinh_Hoc.md` (≤200 dòng)

**Tổng cộng: ~11 file Skill**

---

## 🔗 Trích Dẫn & Nguồn Tài Liệu

| File Input | Thư mục gốc | Ghi chú |
|-----------|-----------|--------|
| SGK7_Chan_troi_sang_tao.pdf | `09_Teacher_Assistant/Tai_Lieu/Lop_7/` | Chân trời sáng tạo |
| SGK_Toan_tap1/2_Ket_noi.pdf | `09_Teacher_Assistant/Tai_Lieu/Lop_8/` | Kết nối tri thức |
| SGK_Toan_tap1/2_Chan_troi.pdf | `09_Teacher_Assistant/Tai_Lieu/Lop_8/9/` | Chân trời sáng tạo |
| SGK_8_KHTN_Chan_troi.pdf | `09_Teacher_Assistant/Tai_Lieu/Lop_8/` | Chân trời sáng tạo |
| SGK_KHTN_9_Chan_troi.pdf | `09_Teacher_Assistant/Tai_Lieu/Lop_9/` | Chân trời sáng tạo |

---

## ✅ Tiêu Chí Hoàn Thành

1. ✅ Tạo thư mục Instruction & Skill
2. ✅ Tạo file PLAN.md (kế hoạch chi tiết)
3. ⏳ Trích xuất & tạo từng file Skill
4. ⏳ Kiểm tra: ≤200 dòng, công thức chuẩn
5. ⏳ Tạo index file trong mỗi thư mục

---

**Cập nhật lần cuối:** 2026-04-07
**Trạng thái:** Chờ phê duyệt kế hoạch

---

## 📖 Liên Kết Tài Liệu Hỗ Trợ

- **[READING_STRATEGY.md](./READING_STRATEGY.md)** - Chiến lược đọc file, lên plan, trích dẫn
- **[DEFINITION_OF_DONE.md](./DEFINITION_OF_DONE.md)** - Tiêu chí hoàn thành (không lan man, đủ chính xác)
