# Trong Apache Flume, Interceptor được sử dụng để chặn, sửa đổi hoặc loại bỏ sự kiện (event) trước khi nó được gửi đến Channel.

Interceptor giúp:

Lọc dữ liệu: Loại bỏ những sự kiện không cần thiết.

Sửa đổi dữ liệu: Thêm hoặc thay đổi các giá trị trong sự kiện.

Phân loại dữ liệu: Dựa trên nội dung, có thể gán nhãn (tag) hoặc chuyển hướng sự kiện.

Trong phần này có 2 ví dụ về interceptor đó là HostInterceptor và RegexFilteringInterceptor.

Trong đó:

HostInterceptor giúp thêm thông tin máy chủ (hostname) vào sự kiện. 

RegexFilteringInterceptor giúp loại bỏ các sự kiện dựa vào biểu thức chính quy.
