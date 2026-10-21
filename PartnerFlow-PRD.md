# PartnerFlow – Quản lý đối tác, hợp đồng và hoa hồng

## 1. Bài toán
Trong công việc phát triển đối tác và khách hàng, Trang cần lưu thông tin đối tác, chuẩn bị hợp đồng, theo dõi lịch hẹn và kiểm tra hoa hồng. Khi thông tin nằm ở nhiều nguồn, người dùng phải nhập lại dữ liệu, mất thời gian tra cứu và dễ bỏ sót việc cần theo dõi.

Sản phẩm hướng đến tập trung các thông tin này trên một website, giúp tạo hợp đồng nhanh hơn, chủ động theo dõi khách hàng và đối soát hoa hồng thuận tiện.

Tần suất công việc và thời gian xử lý hiện tại sẽ được xác nhận qua trải nghiệm thực tế của người dùng, không sử dụng số liệu giả định làm kết quả đã đo.

## 2. Người dùng
- Người dùng đầu tiên: Trang, phụ trách phát triển đối tác và khách hàng.
- Người dùng mở rộng: nhân sự phát triển đối tác, kinh doanh và chăm sóc khách hàng có nhu cầu tương tự.
- Nhân sự kế toán phối hợp kiểm tra thông tin chi trả và đối soát hoa hồng.

## 3. Mục tiêu
- Giảm thao tác nhập lại thông tin khi chuẩn bị hợp đồng.
- Tập trung hồ sơ đối tác để tra cứu thuận tiện.
- Giúp người dùng nhận biết các lịch hẹn và việc đến hạn.
- Hiển thị rõ căn cứ tính hoa hồng, số tiền hoa hồng được hưởng, đã chi trả và còn chờ chi trả.

## 4. Phạm vi phiên bản đầu

### Quản lý đối tác và khách hàng
- Thêm, sửa và tìm kiếm hồ sơ.
- Lưu tên đơn vị, mã số thuế, địa chỉ, người liên hệ, email và số điện thoại.
- Xem hợp đồng, hoa hồng và lịch nhắc liên quan đến từng đối tác.

### Điền thông tin hợp đồng
- Sử dụng một mẫu hợp đồng minh họa.
- Chọn đối tác để tự điền các thông tin đã lưu.
- Nhập nội dung dịch vụ, giá trị hợp đồng và thời hạn.
- Xem trước, chỉnh sửa và in hoặc lưu PDF bằng trình duyệt.

### Theo dõi lịch nhắc
- Tạo lịch hẹn hoặc việc cần thực hiện cho từng đối tác.
- Theo dõi lịch chăm sóc, kỳ đối soát hoa hồng, hạn chi trả hoa hồng và ngày gia hạn hợp đồng.
- Hiển thị việc sắp đến hạn và quá hạn trong website.
- Đánh dấu công việc đã hoàn thành.

### Theo dõi và đối soát hoa hồng
- Ghi nhận doanh số đủ điều kiện tính hoa hồng theo đối tác, hợp đồng và kỳ đối soát.
- Nhập tỷ lệ hoa hồng áp dụng cho từng bản ghi; tính hoa hồng bằng doanh số đủ điều kiện nhân với tỷ lệ hoa hồng.
- Ghi nhận hạn chi trả và các lần chi trả hoa hồng.
- Tính hoa hồng còn chờ chi trả bằng hoa hồng được hưởng trừ tổng số tiền đã chi trả.
- Tìm kiếm hoa hồng theo đối tác, hợp đồng hoặc kỳ đối soát.
- Nhập số tiền hoa hồng từ bảng đối soát để so sánh với số tiền được tính trên hệ thống trong cùng kỳ.
- Hiển thị chênh lệch và cho phép ghi chú kết quả đối soát.

## 5. Luồng sử dụng chính
1. Người dùng tạo hồ sơ đối tác.
2. Chọn đối tác và điền thông tin hợp đồng từ mẫu.
3. Kiểm tra nội dung và xuất hợp đồng.
4. Ghi nhận doanh số đủ điều kiện, tỷ lệ hoa hồng, kỳ đối soát và hạn chi trả.
5. Tạo lịch nhắc chăm sóc, đối soát hoặc theo dõi chi trả hoa hồng.
6. Cập nhật các khoản hoa hồng đã chi trả.
7. Tra cứu hoa hồng được hưởng, số tiền còn chờ chi trả và ghi nhận kết quả đối soát.

## 6. Dữ liệu
- Đối tác: thông tin đơn vị và người liên hệ.
- Hợp đồng: mã hợp đồng, đối tác, nội dung, giá trị và thời hạn.
- Lịch nhắc: đối tác, nội dung, thời điểm và trạng thái.
- Hoa hồng: đối tác, hợp đồng, kỳ đối soát, doanh số đủ điều kiện, tỷ lệ hoa hồng, số tiền được hưởng và hạn chi trả.
- Chi trả hoa hồng: bản ghi hoa hồng liên quan, ngày, số tiền và ghi chú.
- Đối soát: kỳ đối soát, số tiền hoa hồng trên hệ thống, số tiền trong bảng đối soát, chênh lệch và kết quả xử lý.

Toàn bộ dữ liệu trình diễn là dữ liệu giả tự tạo, không sử dụng thông tin khách hàng thật hoặc thông tin nội bộ.

## 7. Tiêu chí nghiệm thu
- Tạo và tìm kiếm được hồ sơ đối tác.
- Thông tin đối tác được điền đúng vào mẫu hợp đồng.
- Có thể xem trước và xuất hợp đồng.
- Lịch nhắc hiển thị đúng trạng thái đến hạn, quá hạn và hoàn thành.
- Hoa hồng được tính đúng theo doanh số đủ điều kiện và tỷ lệ đã nhập; ví dụ dữ liệu giả: 10.000.000 đồng × 5% = 500.000 đồng.
- Hoa hồng còn chờ chi trả được cập nhật đúng sau mỗi lần ghi nhận chi trả; ví dụ chi trả 200.000 đồng thì còn 300.000 đồng.
- Kết quả đối soát hiển thị đúng chênh lệch giữa số tiền hoa hồng trên hệ thống và số tiền trong bảng đối soát của cùng kỳ.
- Dữ liệu đã lưu vẫn còn sau khi tải lại trang.

## 8. Ngoài phạm vi phiên bản đầu
- Ký hợp đồng điện tử.
- Tự động lấy giao dịch ngân hàng.
- Tích hợp hệ thống kế toán.
- Gửi nhắc lịch qua email hoặc Zalo.
- Thay thế phần mềm kế toán chuyên dụng.

## 9. Công cụ và triển khai dự kiến
- Sử dụng ChatGPT/Codex bằng tài khoản AI cá nhân để hỗ trợ phân tích yêu cầu, viết code, kiểm tra và hoàn thiện sản phẩm.
- Lưu mã nguồn trong repository GitHub mới tạo cho kỳ thi.
- Triển khai website trên cloud có hỗ trợ lưu trữ dữ liệu; nền tảng cụ thể sẽ được lựa chọn khi triển khai.
- Ghi lại lịch sử commit trong quá trình phát triển.
- Dựng mới sản phẩm trong kỳ thi, không dùng lại repository hoặc mẫu sản phẩm có sẵn.

## 10. Đánh giá hiệu quả
So sánh thời gian chuẩn bị một hợp đồng trước và sau khi sử dụng sản phẩm. Kiểm tra khả năng tìm thông tin đối tác, theo dõi việc đến hạn và tính hoa hồng và xác định số tiền còn chờ chi trả bằng các tình huống giả lập.

Các chỉ số đánh giá gồm thời gian hoàn thành từng tác vụ, số thao tác nhập lại thông tin và số lỗi phát hiện trong tình huống thử nghiệm. Kết quả chỉ được ghi nhận sau khi thực hiện thử nghiệm.
