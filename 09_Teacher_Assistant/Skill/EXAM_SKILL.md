# ✏️ EXAM SKILL - Claude tự ra đề

## Mô tả

Thay vì dùng script Python, **Claude sẽ trực tiếp ra đề kiểm tra** cho bạn dựa trên ngân hàng câu hỏi có sẵn.

## Cách sử dụng

### 1. Tạo đề kiểm tra

**Lệnh:**
```
Hãy ra đề kiểm tra [số câu] [môn học]
```

**Ví dụ:**
```
Hãy ra đề kiểm tra 10 câu môn Toán
Hãy ra đề kiểm tra 5 câu môn Hóa học
Hãy ra đề kiểm tra 15 câu tất cả các môn
```

### 2. Yêu cầu đáp án

**Sau khi ra đề, bạn có thể:**
- "Hãy cung cấp đáp án" → Hiển thị đáp án
- "Hãy giải thích chi tiết câu X" → Giải thích câu hỏi cụ thể
- "Hãy chấm bài của tôi" → Chấm kết quả (nếu bạn cung cấp tờ trả lời)

## Ngân hàng câu hỏi

**File:** `questions_database.json` (39 câu hỏi)

### Phân bố:
- **Toán (30 câu)**
  - Hình học: 13 câu
  - Hàm số & Phương trình: 10 câu
  - Xác suất & Thống kê: 5 câu
  - Dữ liệu: 2 câu

- **Hóa học (6 câu)**
  - Hợp chất & Phương trình: 6 câu

- **Vật lý (3 câu)**
  - Điện & Phân tử: 3 câu

## Điểm khác biệt

| Trước | Sau |
|-------|-----|
| Dùng script Python | Claude tự ra đề |
| Cố định & Cơ bản | Linh hoạt & Trực tiếp |
| Không có giải thích | Có thể giải thích chi tiết |
| Output text tạp | Output sạch đẹp & dễ đọc |

## Ưu điểm

✅ Không cần chạy script
✅ Tương tác trực tiếp với Claude
✅ Có thể tùy chỉnh đề theo yêu cầu
✅ Đáp án được giải thích chi tiết
✅ Có thể ra đề ngoài ngân hàng nếu cần

## Lưu ý

- Câu hỏi được rút ngẫu nhiên từ ngân hàng
- Có thể yêu cầu đề khó/dễ hơn
- Có thể thay đổi kiểu, mục đích đề thi
- Claude sẽ tự chọn câu phù hợp nhất

## Ví dụ

### Request:
```
Ra đề kiểm tra 5 câu môn Toán cho bài kiểm tra 15 phút
```

### Response:
```
ĐỀ KIỂM TRA 15 PHÚT - TOÁN LỚP 8

Câu 1: ...
  A. ...
  B. ...
  C. ...
  D. ...

[Tiếp tục...]

ĐÁP ÁN
Câu 1: C
Câu 2: B
...
```

---

**Trạng thái:** ✅ Sẵn sàng
**Cập nhật:** 2026-04-08
