# Hướng dẫn đóng góp

Áp dụng cho các repo của Lĩnh Nam Group không có `CONTRIBUTING.md` riêng.

## Nhánh

| Tiền tố | Khi nào |
|---|---|
| `feature/ten-ngan` | Tính năng mới |
| `fix/ten-ngan` | Sửa lỗi |
| `chore/ten-ngan` | Nâng thư viện, dọn dẹp, tái cấu trúc |
| `docs/ten-ngan` | Chỉ tài liệu |

## Thông điệp commit

Theo [Conventional Commits](https://www.conventionalcommits.org/): `<type>(<scope>): <tóm tắt>`, với `type` là một trong `feat`, `fix`, `refactor`, `docs`, `test`, `chore`, `perf`, `ci`.

## Quy ước mã

- **Bất biến**: trả về đối tượng mới, không sửa đối tượng cũ.
- **Tệp nhỏ**: thường 200–400 dòng, tối đa 800.
- **Xử lý lỗi tường minh**: không nuốt lỗi.
- **Không có bí mật trong mã nguồn**: dùng biến môi trường.
- **Dữ liệu thật**: không đưa số liệu, nhân sự hay đối tác giả vào bản chạy thật.

## Trước khi mở pull request

- [ ] Bản build chạy xong, không lỗi.
- [ ] Có kiểm thử cho phần logic mới.
- [ ] Không có khoá, mật khẩu hay token trong thay đổi.
- [ ] Trang công khai có đủ 5 ngôn ngữ: vi, en, zh, ru, ko.
- [ ] Việc lớn có đặc tả (spec) trước khi viết mã.

## Triển khai

Dùng script triển khai của từng dự án; sao lưu trước, kiểm lại sau (cả 5 ngôn ngữ trả 200).
