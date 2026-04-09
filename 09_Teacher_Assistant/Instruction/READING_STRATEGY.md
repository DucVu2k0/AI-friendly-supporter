# 📖 Chiến Lược Đọc & Lên Kế Hoạch (Reading & Planning Strategy)

## 🎯 Mục Đích File Này

**File này hướng dẫn Claude cách:**
1. ✅ Đọc những file nào từ tài liệu gốc
2. ✅ Lên kế hoạch chi tiết trước khi xử lý
3. ✅ Đưa ra output chất lượng cao cho người dùng
4. ✅ Trích dẫn chính xác nguồn tài liệu

---

## 📋 BƯỚC 1: XÁC ĐỊNH FILE CẦN ĐỌC

### Cấu trúc thư mục tài liệu gốc:
```
09_Teacher_Assistant/
│
├── Tai_Lieu/
│   ├── Lop_7/
│   │   └── SGK7_Chan_troi_sang_tao.pdf
│   │
│   ├── Lop_8/
│   │   ├── SGK_Toan_tap1_Ket_noi.pdf
│   │   ├── SGK_Toan_tap2_Ket_noi.pdf
│   │   ├── SGK_Toan_tap1_Chan_troi.pdf
│   │   ├── SGK_Toan_tap2_Chan_troi.pdf
│   │   └── SGK_8_KHTN_Chan_troi.pdf
│   │
│   └── Lop_9/
│       ├── SGK_Toan_tap1_Chan_troi.pdf
│       ├── SGK_Toan_tap2_Chan_troi.pdf
│       └── SGK_KHTN_9_Chan_troi.pdf
│
└── [các thư mục khác]
```

### Quy tắc chọn file:

| Yêu cầu | File cần đọc |
|---------|-------------|
| **Toán Lớp 7** | `09_Teacher_Assistant/Tai_Lieu/Lop_7/SGK7_Chan_troi_sang_tao.pdf` |
| **Toán Lớp 8 Tập 1** | `09_Teacher_Assistant/Tai_Lieu/Lop_8/SGK_Toan_tap1_*.pdf` (cả 2 bộ) |
| **Toán Lớp 8 Tập 2** | `09_Teacher_Assistant/Tai_Lieu/Lop_8/SGK_Toan_tap2_*.pdf` (cả 2 bộ) |
| **Toán Lớp 9 Tập 1** | `09_Teacher_Assistant/Tai_Lieu/Lop_9/SGK_Toan_tap1_Chan_troi.pdf` |
| **Toán Lớp 9 Tập 2** | `09_Teacher_Assistant/Tai_Lieu/Lop_9/SGK_Toan_tap2_Chan_troi.pdf` |
| **KHTN Lớp 8** | `09_Teacher_Assistant/Tai_Lieu/Lop_8/SGK_8_KHTN_Chan_troi.pdf` |
| **KHTN Lớp 9** | `09_Teacher_Assistant/Tai_Lieu/Lop_9/SGK_KHTN_9_Chan_troi.pdf` |

---

## 🧠 BƯỚC 2: LÊN KẾ HOẠCH (PLANNING)

### Khi Claude nhận yêu cầu xử lý tài liệu:

#### **Bước 2.1: Xác định phạm vi**
- ❓ Môn gì? (Toán / KHTN)
- ❓ Lớp mấy? (7 / 8 / 9)
- ❓ Tập nào? (Tập 1 / Tập 2 / không chia tập)
- ❓ Phần nào? (Vật Lý / Hóa Học / Sinh Học)

#### **Bước 2.2: Liệt kê file cần đọc**
```markdown
### File sẽ đọc:
1. [Tên file] - Để trích xuất [chủ đề 1], [chủ đề 2]
2. [Tên file] - Để trích xuất [chủ đề 1], [chủ đề 2]
```

#### **Bước 2.3: Kế hoạch trích xuất**
```markdown
### Kế hoạch trích xuất:
1. Đọc file + xác định các phần chính
2. Trích xuất: Khái niệm, Công thức, Ví dụ
3. Tổ chức theo cấu trúc chuẩn (xem PLAN.md)
4. Kiểm tra: ≤200 dòng + trích dẫn chính xác
```

#### **Bước 2.4: Cấu trúc output**
```markdown
### Output sẽ theo format:
# [Môn] Lớp [N] - [Tập/Phần]

## 1. Khái Niệm Cơ Bản
## 2. Công Thức & Định Lý
## 3. Phương Pháp Giải Bài Tập
## 4. Ví Dụ Minh Họa
## 5. Lưu Ý Quan Trọng
```

---

## 🔍 BƯỚC 3: TRÍCH DẪN NGUỒN (CITATION RULES)

### Nguyên tắc trích dẫn:

#### **3.1: Trích dẫn trực tiếp từ SGK**
```markdown
**Định nghĩa (SGK Toán 7, trang X):**
[Nội dung trích dẫn]

**Công thức (SGK Toán 8 Tập 1, trang X):**
[Nội dung công thức]
```

#### **3.2: Format trích dẫn chuẩn**
- **Trích từ SGK:** `(SGK [Môn] [Lớp] [Tập nếu có], trang X)`
- **Ví dụ:**
  - `(SGK Toán 7, trang 45)`
  - `(SGK Toán 8 Tập 1, trang 23)`
  - `(SGK KHTN 9, trang 78)`

#### **3.3: Khi lấy từ nhiều trang**
```markdown
**Nội dung lấy từ trang 45-47 SGK Toán 8 Tập 1:**
[Tóm tắt nội dung]
```

#### **3.4: Khi tổng hợp từ nhiều nguồn**
```markdown
**Tổng hợp từ:**
- SGK Toán 8 Tập 1, trang 23-25
- SGK Toán 8 Tập 2, trang 67-70
```

---

## 📊 BƯỚC 4: QUI TRÌNH LÀM VIỆC CHI TIẾT

### Khi xử lý 1 file Skill:

```
┌─ Bước 1: Xác định scope ─────────────────────┐
│ ❓ File nào? Lớp mấy? Tập nào? Phần nào? │
└──────────────────────────────────────────────┘
                        ↓
┌─ Bước 2: Tìm & đọc file ────────────────────┐
│ 📖 Locate file from 09_Teacher_Assistant/ │
│ 📖 Read PDF → Extract key sections        │
└──────────────────────────────────────────────┘
                        ↓
┌─ Bước 3: Phân tích & tổ chức ──────────────┐
│ 🔍 Identify: Khái niệm, công thức, VD    │
│ 🔍 Note: Trang số cho trích dẫn           │
└──────────────────────────────────────────────┘
                        ↓
┌─ Bước 4: Tạo output ───────────────────────┐
│ ✍️ Write trong format chuẩn               │
│ ✍️ Add citations: SGK, trang X            │
│ ✍️ Ensure: ≤200 dòng                      │
└──────────────────────────────────────────────┘
                        ↓
┌─ Bước 5: Kiểm tra chất lượng ──────────────┐
│ ✅ Nguồn chính xác? (SGK, trang?)         │
│ ✅ Công thức chuẩn?                       │
│ ✅ Trong 200 dòng?                        │
│ ✅ Format chuẩn?                          │
└──────────────────────────────────────────────┘
```

---

## 💡 BƯỚC 5: VÍ DỤ TRÍCH DẪN

### ✅ ĐÚNG:
```markdown
## 1. Khái Niệm Cơ Bản

**Phân số (SGK Toán 7, trang 8):**
Phân số là một cách viết a/b (b≠0) trong đó a, b là các số nguyên.

**Tính chất cơ bản của phân số (SGK Toán 7, trang 9):**
- Nếu nhân cả tử và mẫu với cùng một số nguyên khác 0 thì được phân số bằng nó
- Nếu chia cả tử và mẫu cho cùng một ước chung, ta được phân số bằng nó
```

### ❌ SAI:
```markdown
## 1. Khái Niệm
Phân số là... (không nên trích dẫn)

## Công thức
a/b = (a×m)/(b×m) (không nên chỉ công thức mà không nêu nguồn)
```

---

## 📌 BƯỚC 6: DANH SÁCH KIỂM TRA TRƯỚC KHI COMMIT

### Trước khi hoàn thành 1 file Skill:

- [ ] **File nào được đọc?** → Ghi rõ đường dẫn & tên file
- [ ] **Trang nào?** → Mỗi trích dẫn có ghi trang
- [ ] **Nguồn SGK nào?** → Kết nối / Chân trời / khác?
- [ ] **Dòng/từ?** → ≤200 dòng?
- [ ] **Công thức có cite?** → Mỗi công thức có `(SGK..., trang X)`?
- [ ] **Format chuẩn?** → Đúng cấu trúc 5 phần?
- [ ] **Ví dụ có giải?** → Mỗi ví dụ có lời giải đầy đủ?

---

## 📚 BƯỚC 7: METADATA IN FILE OUTPUT

### Mỗi file output nên có metadata:

```markdown
---
📚 **Nguồn tài liệu:**
- SGK Toán 8 Tập 1 - Bộ Kết nối tri thức (trang 10-45)
- SGK Toán 8 Tập 1 - Bộ Chân trời sáng tạo (trang 5-40)

⏰ **Tần cập nhật:** 2026-04-07
📍 **Thư mục:** `Skill/Toan_Lop_8_Tap1.md`
---
```

---

## 🎯 TÓM TẮT QUY TRÌNH

| Bước | Hành Động | Kết Quả |
|------|-----------|---------|
| 1️⃣ | Xác định scope (môn/lớp/tập) | Biết cần đọc file nào |
| 2️⃣ | Đọc PDF từ `09_Teacher_Assistant/` | Có nội dung gốc |
| 3️⃣ | Trích xuất: khái niệm, công thức, VD | Có dữ liệu thô |
| 4️⃣ | Tổ chức theo format 5 phần | Có cấu trúc |
| 5️⃣ | Thêm citations: `(SGK..., trang X)` | Có trích dẫn |
| 6️⃣ | Kiểm tra: ≤200 dòng, format, trang | Đảm bảo chất lượng |
| 7️⃣ | Lưu file + Update INDEX.md | Hoàn thành |

---

## 📞 LIÊN HỆ & HỎI ĐÁP

**Nếu gặp vấn đề:**
- ❓ Không tìm thấy file? → Check đường dẫn trong `09_Teacher_Assistant/`
- ❓ Không biết trang? → Scan PDF hoặc ghi `(SGK..., trang không xác định)`
- ❓ File quá dài? → Tách thành nhiều chủ đề nhỏ
- ❓ Thông tin mâu thuẫn? → Ưu tiên SGK Chân trời sáng tạo

---

**Cập nhật:** 2026-04-07
**Phiên bản:** 1.0
