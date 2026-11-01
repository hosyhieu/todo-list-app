# REMIND.md
# TODO-LIST APP – PROJECT VISION & GUIDELINES

## 1. Thông tin dự án

- **Tên dự án:** Todo List App
- **Tên đầy đủ:** Phần mềm quản lý công việc học tập dành cho sinh viên.
- **Lĩnh vực:** Quản lý công việc và hỗ trợ học tập.
- **Đối tượng người dùng:** Học sinh, sinh viên.
- **Nền tảng:** Windows Desktop.
- **Ngôn ngữ lập trình:** Python.
- **Hình thức phát triển:** Dự án cá nhân trong môn Công nghệ phần mềm.

## 2. Product Vision – Tầm nhìn sản phẩm

Todo List App hướng đến việc xây dựng một phần mềm quản lý công việc học tập trên máy tính, giúp sinh viên chủ động tổ chức các nhiệm vụ, theo dõi tiến độ và kiểm soát thời hạn hoàn thành công việc.

Trong quá trình học tập, sinh viên thường phải xử lý nhiều nhiệm vụ cùng lúc như làm bài tập, chuẩn bị bài thuyết trình, ôn thi và hoàn thành các bài tập lớn. Việc ghi nhớ và quản lý những công việc này một cách thủ công có thể khiến sinh viên bỏ sót nhiệm vụ, quên thời hạn hoặc chưa phân bổ thời gian hợp lý.

Xuất phát từ nhu cầu đó, Todo List App cung cấp một không gian quản lý công việc tập trung, cho phép người dùng tạo, chỉnh sửa, xóa và theo dõi trạng thái các nhiệm vụ. Bên cạnh đó, phần mềm hỗ trợ thiết lập thời hạn, phân loại mức độ ưu tiên và lọc công việc theo trạng thái, giúp sinh viên dễ dàng xác định những nhiệm vụ cần được thực hiện trước.

Sản phẩm hướng đến sự đơn giản, trực quan và dễ sử dụng. Todo List App tập trung giải quyết tốt những nhu cầu quản lý công việc thiết yếu, giúp sinh viên hình thành thói quen học tập có kế hoạch và sử dụng thời gian hiệu quả hơn.

Phần mềm được phát triển bằng Python trên nền tảng Desktop, với mục tiêu xây dựng một sản phẩm có tính ứng dụng thực tế, cấu trúc rõ ràng, dễ bảo trì và phù hợp với khả năng triển khai của một cá nhân.

## 3. Đối tượng người dùng

Đối tượng sử dụng chính là học sinh, sinh viên có nhu cầu quản lý các nhiệm vụ học tập và công việc cá nhân trên máy tính.

## 4. Product Goals – Mục tiêu sản phẩm

- Giúp sinh viên quản lý tập trung các công việc học tập và cá nhân.
- Hỗ trợ theo dõi thời hạn và mức độ ưu tiên của từng nhiệm vụ.
- Giúp người dùng dễ dàng nhận biết công việc đã hoàn thành, đang thực hiện hoặc chưa thực hiện.
- Hỗ trợ sắp xếp và lọc công việc để nâng cao hiệu quả quản lý thời gian.
- Xây dựng phần mềm có giao diện thân thiện, thao tác đơn giản và dễ tiếp cận.
- Đảm bảo sản phẩm có thể hoạt động ổn định trên máy tính cá nhân.

## 5. Phạm vi phiên bản đầu tiên (MVP)

Phiên bản đầu tiên tập trung vào các chức năng cốt lõi:

- [ ] Thêm công việc.
- [ ] Chỉnh sửa công việc.
- [ ] Xóa công việc.
- [ ] Xem danh sách công việc.
- [ ] Đánh dấu trạng thái hoàn thành.
- [ ] Thiết lập thời hạn hoàn thành.
- [ ] Phân loại mức độ ưu tiên.
- [ ] Tìm kiếm và lọc công việc.
- [ ] Lưu trữ dữ liệu bằng SQLite.

### Giới hạn phạm vi

Trong phiên bản đầu tiên, không triển khai:

- Hệ thống quản lý dự án nhóm.
- Quản lý nhiều tài khoản người dùng.
- Đồng bộ dữ liệu qua Internet.
- Tích hợp AI.
- Các chức năng phức tạp chưa thực sự cần thiết.

Ưu tiên hoàn thành tốt các chức năng cơ bản trước khi mở rộng.

## 6. Định hướng công nghệ

| Thành phần | Công nghệ dự kiến |
|---|---|
| Ngôn ngữ lập trình | Python |
| Giao diện Desktop | Tkinter |
| Cơ sở dữ liệu | SQLite |
| Quản lý mã nguồn | Git và GitHub |
| Kiểm thử | unittest |

Ưu tiên sử dụng các công nghệ dễ tiếp cận, phù hợp với trình độ hiện tại và không đòi hỏi cấu hình máy tính quá cao.

## 7. Định hướng phát triển tương lai

Sau khi phiên bản đầu tiên hoạt động ổn định, có thể xem xét phát triển thêm:

- Thống kê hiệu suất hoàn thành công việc.
- Nhắc nhở công việc sắp đến hạn.
- Lịch học và lịch công việc.
- Hỗ trợ lập kế hoạch học tập bằng AI.

Các chức năng mở rộng chỉ được triển khai khi có nhu cầu thực tế và được thống nhất về phạm vi.

## 8. Giá trị cốt lõi

**Todo List App – Quản lý công việc khoa học, chủ động học tập, sử dụng thời gian hiệu quả.**

## 9. Quy tắc dành cho AI khi hỗ trợ phát triển dự án

1. Đọc tài liệu này trước khi bắt đầu thực hiện công việc liên quan đến dự án.
2. Luôn căn cứ vào Product Vision và phạm vi dự án trước khi đề xuất hoặc triển khai chức năng.
3. Ưu tiên giải pháp đơn giản, dễ hiểu và phù hợp với người mới học Python.
4. Không tự ý mở rộng dự án thành một hệ thống phức tạp.
5. Không tự ý thay đổi công nghệ nền tảng đã thống nhất.
6. Khi đề xuất chức năng mới, cần giải thích mục đích, lợi ích và độ phức tạp.
7. Ưu tiên cấu trúc code rõ ràng, dễ đọc, dễ kiểm thử và dễ bảo trì.
8. Không tự ý xóa hoặc ghi đè dữ liệu, mã nguồn quan trọng.
9. Khi gặp vấn đề vượt quá kiến thức hiện tại, giải thích từng bước trước khi triển khai.
10. Đảm bảo chức năng mới không làm hỏng những chức năng đã hoạt động.
11. Mọi thay đổi lớn về kiến trúc hoặc phạm vi cần được trao đổi và thống nhất trước với người phát triển.
12. Không tự suy đoán yêu cầu khi thông tin chưa rõ ràng. Hãy hỏi lại trước khi thực hiện những thay đổi có ảnh hưởng lớn.