# HCM-KS26-CNTT2_Nhap-mon-CNTT_Session10_Ex03

## Phần 1: Phân tích bài toán (Cơ chế Token)
*   **HTML:** Sử dụng hệ thống thẻ đóng/mở phức tạp (ví dụ: `<strong>...</strong>`). Điều này làm lãng phí lượng lớn Token của AI chỉ để xử lý các ký tự định dạng, làm giảm tốc độ sinh văn bản.
*   **Markdown:** Sử dụng các ký tự đặc biệt tối giản (ví dụ: `**...**`). Giúp tối ưu hóa số lượng Token, AI xử lý nhanh hơn (giảm độ trễ) và tiết kiệm trực tiếp chi phí API.

## Phần 2: So sánh Và Đánh giá

| Tiêu chí | Markdown | HTML |
| :--- | :--- | :--- |
| **Cú pháp in đậm** | `**Rau sạch**` | `<strong>Rau sạch</strong>` |
| **Tính Human-readable** | Rất cao (Đọc tốt ngay cả khi là văn bản thô) | Thấp (Rối mắt bởi các thẻ định dạng) |
| **Chi phí Token** | Thấp (Tối ưu) | Cao (Lãng phí) |
| **Tốc độ AI xử lý** | Nhanh | Chậm |

### Giải pháp tối ưu cho hệ thống "GreenTech"

**Lựa chọn chốt:** Sử dụng định dạng **Markdown**.

**Lập luận:**
1.  **Hiệu năng & Kinh tế:** Tiết kiệm lượng Token phát sinh, giúp hệ thống phản hồi các câu hỏi nông nghiệp nhanh chóng và giảm chi phí vận hành API.
2.  **Trải nghiệm người dùng (UX):** Markdown mang tính "Human-readable" cao. Trong trường hợp xấu nhất hệ thống lỗi không hiển thị được giao diện, người nông dân nhìn vào văn bản Markdown thô vẫn hoàn toàn có thể đọc hiểu thông tin, trong khi HTML sẽ hiển thị một mớ thẻ code `<br>`, `<li>` gây khó hiểu.
