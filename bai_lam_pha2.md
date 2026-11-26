# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 05
- **Họ tên:** Lê Hoàng Anh
- **Lớp:** CNTT2
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** ChatGPT

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé xem phim ra JSON

**KET QUA AI**

```text
[\
&#x20; {\
&#x20;   "ma_goi": "SVT",\
&#x20;   "ngay_su_kien": "2026-12-20",\
&#x20;   "nguoi_lon": 2,\
&#x20;   "tre_em": 1,\
&#x20;   "loai_ve": "thuong",\
&#x20;   "ghi_chu": null\
&#x20; },\
&#x20; {\
&#x20;   "ma_goi": "FZ",\
&#x20;   "ngay_su_kien": "2027-01-05",\
&#x20;   "nguoi_lon": 3,\
&#x20;   "tre_em": 0,\
&#x20;   "loai_ve": "thuong",\
&#x20;   "ghi_chu": "hỗ trợ xe lăn"\
&#x20; },\
&#x20; {\
&#x20;   "ma_goi": "VIP",\
&#x20;   "ngay_su_kien": null,\
&#x20;   "nguoi_lon": 4,\
&#x20;   "tre_em": 0,\
&#x20;   "loai_ve": "vip",\
&#x20;   "ghi_chu": "hỗ trợ tìm chỗ cho người khiếm thị"\
&#x20; }\
]

```

**Link trò chuyện:**  https://chatgpt.com/share/6b079ded-a66c-83ec-a9d1-e149dd68b520

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
**1. Tiền người lớn:**

5 × 1.200.000 = 6.000.000 đồng.

**2. Tiền trẻ em:**

- Trẻ 8 tuổi: 1.200.000 × 70% = 840.000 đồng.
- Trẻ 10 tuổi: 1.200.000 × 70% = 840.000 đồng.
- Trẻ 3 tuổi: Miễn phí = 0 đồng.

Tổng: 840.000 + 840.000 + 0 = 1.680.000 đồng.

**3. Tiền vé:**

6.000.000 + 1.680.000 = 7.680.000 đồng.

**4. Phụ thu:**

1 × 300.000 = 300.000 đồng.

**5. Combo (giảm 5%):**

7.680.000 × 5% = 384.000 đồng.

Tiền vé sau giảm: 7.680.000 − 384.000 = 7.296.000 đồng.

**6. Tổng tiền:**

7.296.000 + 300.000 = 7.596.000 đồng.

[RESULT: 7.596.000 đồng]
```

**Link trò chuyện:** https://chatgpt.com/share/6b079e1c-71cc-83ec-a61d-f674e6663cfd

### b) Kiểm tra kết quả AI

- Đã đúng

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{\
&#x20; "loai_su_co": "sai_khu_vuc",\
&#x20; "so_nguoi_anh_huong": 2,\
&#x20; "muc_do_uu_tien": "cao",\
&#x20; "nhan_vien_lien_quan": false\
}
```

**Link trò chuyện:**  https://chatgpt.com/share/6b079e92-b618-83ec-b6e2-63b1e156c368

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
Tiêu chí	Điểm	Minh chứng	Đề xuất sửa
Đúng thông tin (50%)	0/5	“Vé Sân Vận Động bên em giá 1.000.000đ/người” sai giá vé, giá chuẩn là 1.200.000đ/người lớn. “Anh huỷ trước 3 ngày thì được hoàn tiền đầy đủ nha anh” sai chính sách, hủy trước 3 ngày chỉ được hoàn 50%.	Sửa thành: “Vé SVT có giá 1.200.000 đồng/người lớn. Nếu hủy trước 3 ngày, khách được hoàn 50% tiền vé.”
Đầy đủ (30%)	1/3	“Anh huỷ trước 3 ngày thì được hoàn tiền đầy đủ nha anh.” Chỉ đề cập một mốc thời gian, thiếu chính sách hủy trước 7 ngày trở lên và hủy dưới 3 ngày.	Bổ sung đầy đủ cả 3 mức: trước 7 ngày trở lên hoàn 100%; trước 3–6 ngày hoàn 50%; dưới 3 ngày không hoàn tiền.
Giọng điệu (20%)	2/2	“Dạ chào anh ạ!”, “Anh cần gì cứ nhắn em nhé!” Thể hiện thái độ lịch sự, thân thiện và nhiệt tình.	Không cần sửa.
Tổng điểm	3/10	Sai thông tin giá vé và chính sách hoàn tiền, thiếu thông tin cần thiết.	Cần sửa lại nội dung tư vấn theo thông tin chuẩn.
```

**Link trò chuyện:** https://chatgpt.com/share/6b079e92-b618-83ec-b6e2-63b1e156c368
