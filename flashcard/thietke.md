# Ý tưởng: web flashcard học lý thuyết trên lớp

## Mục đích
Tạo một web app flashcard giúp học sinh ghi nhớ lý thuyết nhanh, thuận tiện và có thể dùng ngay trên lớp hoặc khi tự học.

## Chức năng chính

### 1. Màn hình tải file lý thuyết lên
- Có một ô nhập tên bộ flashcard
- Có một ô nhập câu hỏi
- Có một ô nhập câu trả lời
- Có một ô upload file hoặc nội dung lý thuyết để tạo flashcard
- Có nút lưu bộ flashcard

### 2. Màn hình chọn bộ flashcard
- Hiển thị danh sách các bộ flashcard đã tạo
- Cho phép chọn một bộ để học
- Có thể xem số lượng câu hỏi trong mỗi bộ

### 3. Màn hình sử dụng flashcard
- Hiển thị một câu hỏi ở mặt trước và câu trả lời ở mặt sau
- Có nút “Đã nhớ” và “Chưa nhớ” để đánh dấu tiến độ học
- Có nút “Next” và “Back” để chuyển giữa các câu hỏi
- Có ô hiển thị số thứ tự câu hỏi hiện tại trên tổng số câu hỏi
- Khi học đến câu cuối, hiển thị kết quả tổng hợp các câu đã nhớ và chưa nhớ

## Luồng sử dụng đề xuất
1. Người dùng tạo bộ flashcard từ file lý thuyết hoặc nhập thủ công
2. Chọn bộ flashcard cần học
3. Học từng câu hỏi, đánh dấu đã nhớ/chưa nhớ
4. Xem kết quả cuối buổi học để biết mình còn yếu ở đâu

## Vấn đề cần cải tiến
- Cần có cách lưu dữ liệu lâu dài, tránh mất bộ flashcard khi refresh hoặc đóng trình duyệt
- Nên hỗ trợ nhập nhiều câu hỏi cùng lúc thay vì nhập từng câu riêng
- Nên cho phép upload file dạng PDF, Word hoặc txt để tự tạo flashcard dễ hơn
- Cần có chức năng chỉnh sửa và xóa bộ flashcard sau khi tạo
- Nên thêm thống kê: số câu đã nhớ, số câu còn chưa nhớ, tỷ lệ hoàn thành
- Giao diện nên tối giản, dễ dùng trên điện thoại và máy tính
- Nên có chế độ học ngẫu nhiên hoặc lặp lại câu chưa nhớ để hiệu quả hơn

## Gợi ý cải tiến ưu tiên
- Bước đầu: làm chức năng tạo, lưu, học và xem kết quả trước
- Sau đó: thêm upload file, chỉnh sửa/xóa, thống kê và học lặp lại câu chưa nhớ

## Kết luận
Ý tưởng này khá phù hợp vì vừa đơn giản, vừa có thể dùng ngay cho việc học lý thuyết trên lớp. Nếu phát triển đúng hướng, web này sẽ rất tiện cho học sinh và giáo viên.
