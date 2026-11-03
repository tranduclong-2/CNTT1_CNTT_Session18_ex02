# Bài 2 : Sự cố phiên làm việc trên hệ thống vận tải
## Phần 1. Phân tích

### 1. So sánh Cache và Cookies

| Tiêu chí | Cache | Cookies |
|---|---|---|
| Dung lượng | MB đến GB | Khoảng 4KB |
| Công dụng | Lưu hình ảnh, CSS, JavaScript | Lưu thông tin phiên đăng nhập |
| Thời gian lưu | Có thể lưu lâu | Theo thời hạn thiết lập |
| Mục đích | Giúp website tải nhanh hơn | Ghi nhớ người dùng |

**Kết luận:** Cache dùng để lưu dữ liệu website giúp tải nhanh hơn, còn Cookies dùng để ghi nhớ thông tin người dùng và phiên đăng nhập.

## Phần 2. Triển khai
Một mẩu tin Cookie thường bao gồm các thành phần:
- Token: Dữ liệu dùng để xác định phiên đăng nhập của người dùng.
- Max-Age: Quy định thời gian Cookie tồn tại trước khi hết hạn.
- Các cờ bảo mật giúp tăng cường bảo mật cho người dùng.

## Phần 3. Kiểm thử 
Thao tác - Hard Reload để xóa Cache đệm có 2 cách
- Sử dụng phím tắt Ctrl+F5
- F12, vào mục netwwork và bấm disable cache 
