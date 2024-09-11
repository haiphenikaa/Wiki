#Software Development Methodologies

##Phương pháp Waterfall (thác nước)
- Đặc điểm: Tuần tự, từng giai đoạn hoàn thành mới chuyển sang giai đoạn tiếp theo.
- Các giai đoạn: Thu thập yêu cầu, thiết kế, thực hiện, kiểm thử, triển khai, bảo trì.
- Ưu điểm: Dễ hiểu, dễ quản lý, phù hợp với dự án có yêu cầu rõ ràng từ đầu.
- Nhược điểm: Ít linh hoạt, khó thay đổi yêu cầu sau khi đã bắt đầu.
Ví dụ: Dự án xây dựng một tòa nhà, nơi các giai đoạn được thực hiện theo một trình tự chặt chẽ.

##Mô hình V-shape
- Đặc điểm: Mở rộng của Waterfall, nhấn mạnh vào việc kiểm thử song song với các giai đoạn phát triển.
- Các giai đoạn: Tương tự Waterfall, nhưng mỗi giai đoạn xác minh (thu thập yêu cầu, thiết kế) đều có một giai đoạn xác nhận (kiểm thử) tương ứng.
- Ưu điểm: Đảm bảo chất lượng sản phẩm ngay từ đầu, phù hợp với dự án có yêu cầu kỹ thuật cao.
- Nhược điểm: Ít linh hoạt, khó thay đổi yêu cầu sau khi đã bắt đầu.
Ví dụ: Dự án phát triển phần mềm nhúng cho thiết bị y tế, nơi yêu cầu về độ chính xác và an toàn rất cao.

##Mô hình Agile
- Các giai đoạn: Sprint (chu kỳ phát triển ngắn), mỗi sprint bao gồm các hoạt động: lên kế hoạch, phát triển, kiểm thử, đánh giá.
- Ưu điểm: Linh hoạt, thích ứng với thay đổi, khách hàng tham gia tích cực vào quá trình phát triển.
- Nhược điểm: Khó dự báo thời gian và chi phí chính xác, yêu cầu đội ngũ có kỹ năng cao.
Ví dụ: Phát triển ứng dụng di động, nơi yêu cầu thay đổi thường xuyên và khách hàng cần thấy kết quả nhanh chóng.
- Bốn giá trị cốt lõi:
    1. **Các cá nhân và tương tác** hơn là quy trình và công cụ.
    2. **Phần mềm hoạt động** hơn là tài liệu đầy đủ.
    3. **Hợp tác với khách hàng** hơn là đàm phán hợp đồng.
    4. **Phản hồi với thay đổi** hơn là tuân theo kế hoạch.

##Bảng so sánh mô hình:
Phương pháp	    Ưu điểm	                Nhược điểm	    Phù hợp với
Waterfall	    Dễ hiểu, dễ quản lý	    Ít linh hoạt	Dự án có yêu cầu rõ ràng
V-shape	        Đảm bảo chất lượng	    Ít linh hoạt	Dự án có yêu cầu kỹ thuật cao
Agile	        Linh hoạt, thích ứng	Khó dự báo	    Dự án phức tạp, yêu cầu thay đổi thường xuyên


#Software Versions

##Giới thiệu về Phiên bản Phần Mềm
- Mục đích của phiên bản:
    1. Theo dõi lịch sử phát triển của phần mềm.
    2. Cung cấp thông tin về các cập nhật, sửa lỗi.
    3. Hỗ trợ người dùng và nhà phát triển trong việc quản lý và khắc phục sự cố.
- Cấu trúc của số phiên bản:
    1. Thường gồm các số nguyên phân cách bởi dấu chấm.
    2. Mỗi số đại diện cho một cấp độ thay đổi khác nhau (major, minor, patch, build).
Ví dụ: 1.2.3.4

##Ý Nghĩa của Các Số Phiên Bản
- Số phiên bản major:
    1. Chỉ ra những thay đổi lớn, không tương thích ngược.
    2. Thường đi kèm với việc bổ sung tính năng mới hoặc thay đổi cấu trúc phần mềm.
    3. Số phiên bản minor:
    4. Chỉ ra những thay đổi nhỏ, tương thích ngược.
    5. Thường là việc thêm tính năng mới hoặc cải tiến hiệu năng.
- Số phiên bản patch:
    1. Chỉ ra các bản vá lỗi, sửa chữa các vấn đề nhỏ.
    2. Số phiên bản build:
Chỉ ra phiên bản xây dựng cụ thể, thường được sử dụng trong quá trình phát triển.

##Cách Xác Định Phiên Bản Phần Mềm
- Vị trí thông tin:
    1. Thường được tìm thấy trong menu "Trợ giúp" hoặc "Giới thiệu".
    2. Có thể nằm trong các tệp cấu hình hoặc thông tin hệ thống.
Ví dụ: Cách xem phiên bản trình duyệt Google Chrome.

##Tầm Quan Trọng của Phiên bản Phần Mềm
- Quản lý cập nhật: Giúp người dùng biết khi nào cần cập nhật.
- Khắc phục sự cố: Dễ dàng xác định phiên bản gây ra lỗi.
- Tương thích: Đảm bảo phần mềm hoạt động đúng với các phần mềm khác.
- Bảo mật: Các phiên bản mới thường khắc phục các lỗ hổng bảo mật.
##Khả Năng Tương Thích Giữa Các Phiên Bản
- Tương thích ngược:
    1. Phiên bản mới có thể hoạt động với dữ liệu và cấu hình của phiên bản cũ.
- Không tương thích:
    1. Phiên bản mới có thể không hoạt động với phiên bản cũ, gây ra lỗi hoặc mất dữ liệu.
