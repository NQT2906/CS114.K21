Đề xuất đồ án cuối kỳ : Máy Học Nguyễn Trọng Thuận - 18521471, Đinh Thanh Toàn - 18521504, Nguyễn Quang Thuận - 18521470 Lớp CS114.K21 Bài toán : Phát hiện ổ gà có trên đường trong ảnh.

Mô tả bài toán
Input: Ảnh chụp mặt đường


Output : Có hoặc không ổ gà trong ảnh.
Mô tả về bộ dữ liệu
Tự xây dựng + thu thập bộ dữ liệu :
Thu thập hoặc tự chụp các tấm ảnh trên đường hoặc trên mạng.
Toàn bộ ảnh được chụp lúc trời sáng không chụp trong điều kiện âm u hay mờ mờ tối.
Số lượng, độ đa dạng:
2 loại ảnh (có ổ gà hoặc không), mỗi loại 150 ảnh => tổng cộng 300 ảnh.
Các thao tác tiền xử lý dữ liệu:
Dùng HOG để trích xuất đặc trưng các ổ gà có trong ảnh.
Phân chia dữ liệu 2/3 train / 1/3 test : 200 train / 100 test.
Mô tả về thuật toán máy học.
Sử dụng RCNN làm bộ phân loại.
Cài đặt, tinh chỉnh tham số.
Thực hiện xây dựng chương trình demo trên Colab.
Điều chỉnh các tham số về scale ảnh, threshold binary image, epochs, ..vv
Đánh giá kết quả, kết luận.
Sử dụng độ đo MAP.
