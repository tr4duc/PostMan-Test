# PostMan-Test

# Giới thiệu
Postman là một công cụ mạnh mẽ được sử dụng để kiểm thử và phát triển API. Nó cung cấp nhiều tính năng giúp bạn dễ dàng tạo, gửi và kiểm tra các yêu cầu HTTP, cũng như quản lý các bộ sưu tập API và môi trường.

# API 
Một ví dụ với API miễn phí từ JSONPlaceholder, một API giả lập thường được sử dụng cho mục đích thử nghiệm và học tập.

# API JSONPlaceholder
URL cơ bản: https://jsonplaceholder.typicode.com

# Kiểm thử API với JSONPlaceholder
1. Kiểm tra Endpoint GET /posts
![Test1](https://github.com/tr4duc/PostMan-Test/assets/96672630/0cc24a59-e18d-4817-9ebc-711eab69e891)
Mã trạng thái HTTP là 200 OK và danh sách bài viết trả về đúng định dạng JSON.

2. Kiểm tra Endpoint POST /posts
![test2](https://github.com/tr4duc/PostMan-Test/assets/96672630/103121fc-6a26-46b3-ac89-371914395a7f)
Mã trạng thái HTTP là 201 Created và dữ liệu bài viết mới được trả về kèm theo ID.

3. Kiểm tra Endpoint GET /posts/{id}
![image](https://github.com/tr4duc/PostMan-Test/assets/96672630/0973dff7-b8b1-46fa-9a3b-9e4f3d47c6a7)
Mã trạng thái HTTP là 200 OK và kết quả trả về đúng

4. Kiểm tra Endpoint PUT /posts/{id}
![image](https://github.com/tr4duc/PostMan-Test/assets/96672630/f6386de6-6d00-4901-ae3f-8e3e521a52dc)
Mã trạng thái HTTP là 200 OK và kết quả trả về cập nhật đúng

5. Kiểm tra Endpoint DELETE /posts/{id}
![image](https://github.com/tr4duc/PostMan-Test/assets/96672630/f427c9ab-e834-4bb0-b8b8-fbe3cf095088)
Mã trạng thái HTTP là 200 OK và bài viết đã được xóa

# Mục Tiêu Kiểm Thử:
- Xác định và xác thực các phản hồi của API dựa trên các truy vấn khác nhau.

# Phạm Vi Kiểm Thử:
- Các điểm cuối liên quan đến việc lấy dữ liệu.

# Kết quả Kiểm thử:
- Tất cả các trường hợp kiểm thử được thực hiện và kết quả phù hợp với mong đợi.

# Khuyến nghị:
- API hoạt động đúng như mong đợi.
