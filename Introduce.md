Đề xuất đồ án cuối kỳ : Máy Học Nguyễn Trọng Thuận - 18521471, Đinh Thanh Toàn - 18521504, Nguyễn Quang Thuận - 18521470 Lớp CS114.K21 Bài toán : Phát hiện ổ gà có trên đường trong ảnh.

Mô tả bài toán
Input: Ảnh chụp mặt đường


Output : Có hoặc không ổ gà trong ảnh.
Mô tả về bộ dữ liệu

Tự xây dựng bộ dữ liệu :
Chụp các tấm ảnh có ổ gà hoặc không, nếu có ổ gà thì ổ gà cách xa 10 - 15m. Góc chụp là dưới ngực.
Toàn bộ ảnh được chụp lúc trời sáng không chụp trong điều kiện âm u hay mờ mờ tối.

Số lượng, độ đa dạng:
2 loại ảnh (có ổ gà hoặc không), mỗi loại 150 ảnh => tổng cộng 300 ảnh.

Các thao tác tiền xử lý dữ liệu:
Dùng HOG để trích xuất đặc trưng các ổ gà có trong ảnh.

Phân chia dữ liệu 80% train / 20% test : 240 train / 60 test.

Mô tả về thuật toán máy học.

Sử dụng 2 model để huấn luyện với tập dữ liệu là Logistic Regression và Support Vector Machine.

Cài đặt, tinh chỉnh tham số.

Thực hiện xây dựng chương trình demo trên Colab.

Điều chỉnh các tham số về scale ảnh, threshold binary image, ..vv

Đánh giá kết quả, kết luận.

Sử dụng độ đo accuracy, recall, f1 và presion để tiến hành đánh giá chất lượng model.
