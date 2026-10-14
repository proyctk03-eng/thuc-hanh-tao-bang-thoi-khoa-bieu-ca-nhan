# [Thực hành] Tạo bảng thời khóa biểu cá nhân

Bài thực hành xây dựng bảng thời khóa biểu cá nhân bằng các thẻ ngữ nghĩa HTML (`<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`) theo giáo trình CodeGym.

---

## Các bước thực hiện
1. **Khởi tạo tệp HTML**: Tạo file `timetable.html` với cấu trúc tài liệu HTML5 chuẩn (`lang="vi"`, tiêu đề "Thời Khóa Biểu Cá Nhân").
2. **Dựng khung bảng (`<table>`, `<thead>`)**:
   - Sử dụng `<thead>` để định nghĩa hàng tiêu đề cột gồm "Thời gian" và các ngày trong tuần từ Thứ Hai đến Thứ Bảy.
   - Thẻ `<th>` dùng cho các ô tiêu đề cột.
3. **Điền nội dung dữ liệu (`<tbody>`)**:
   - Sử dụng thẻ `<tbody>` bao bọc các hàng dữ liệu theo từng buổi (Sáng, Chiều, Tối).
   - Thẻ `<th>` tiêu đề hàng thể hiện mốc thời gian (Sáng 8:00-12:00, Chiều 13:30-17:00, Tối 18:30-21:30).
   - Thẻ `<td>` chứa hoạt động chi tiết tương ứng với mỗi ngày.
4. **Mở rộng tính năng**:
   - Bổ sung thêm hàng "Buổi Tối" và cột "Thứ Bảy" theo phần Thử thách mở rộng.
   - Định dạng bảng rõ ràng, thẩm mỹ với CSS hiện đại.
