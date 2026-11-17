# VIBECODE Feedback

Kho tiếp nhận lỗi và đề xuất tính năng công khai cho VIBECODE. Nội dung issue và bình luận có thể được bất kỳ ai đọc, tìm kiếm hoặc sao chép.

## Gửi phản hồi

1. Chọn **New issue** và dùng mẫu lỗi hoặc đề xuất tính năng.
2. Ghi phiên bản VIBECODE, hệ điều hành, kết quả mong đợi và kết quả thực tế.
3. Với lỗi, cung cấp ví dụ tái hiện tối thiểu, tự viết bằng dữ liệu giả. Kiểm tra nội dung trước khi gửi.

**Không đăng** token, mật khẩu, khóa API, log, mã nguồn riêng tư, tên dự án hoặc đường dẫn tuyệt đối. Không đính kèm ảnh, tệp hay đầu ra lệnh chứa những dữ liệu này. Không sao chép bằng chứng hoặc trạng thái tự sinh từ dự án vào issue. Mẫu lệnh phải dùng tên giả và đường dẫn tương đối.

Lỗi bảo mật phải theo [SECURITY.md](SECURITY.md), không tạo issue công khai.

## Báo cáo tự động: ứng viên RC3

RC2 **chưa có** lệnh cấu hình bên dưới. Đây là giao diện dự kiến cho ứng viên RC3; chỉ sử dụng khi bản RC3 đã được kiểm chứng và tài liệu của bản đó xác nhận hỗ trợ.

```text
vibecode feedback configure --repository lethach/vibecode-feedback --enable --auto-submit --capture-core-errors
```

Chế độ dự kiến là **opt-in**: người dùng chủ động bật việc tự gửi báo cáo lỗi lõi kỹ thuật lên kho công khai này. Việc bật chế độ đồng nghĩa cho phép gửi tự động trong phạm vi đó. Báo cáo phải chỉ chứa thông tin kỹ thuật đã được lọc, không chứa nội dung dự án, mã nguồn, log, bí mật, tên dự án hoặc đường dẫn tuyệt đối. Chưa có tuyên bố rằng chức năng này đã khả dụng hoặc đã vượt kiểm chứng.

## Phạm vi kho

Kho này chỉ phục vụ phản hồi. Việc công khai kho không thay đổi quyền truy cập mã nguồn chính, không quyết định giấy phép sản phẩm và không cam kết có bản tải xuống công khai. Các bản phát hành hiện có có thể yêu cầu quyền truy cập riêng.

## English

This is a **public** issue repository. Use the bug or feature template. Include versions, expected and actual behavior, and a minimal synthetic reproduction. Never post tokens, credentials, logs, private source, project names, absolute paths, or generated project evidence.

For vulnerabilities, follow [SECURITY.md](SECURITY.md); do not open a public issue. The command above is proposed for a verified RC3 candidate and is **unavailable in RC2**. Automatic technical core-error reporting requires explicit opt-in. This repository does not change product source visibility or licensing, and does not promise public release downloads.
