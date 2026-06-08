# ExamScan

**Phần mềm chấm bài thi trắc nghiệm tự động** — quét phiếu trả lời bằng camera hoặc scanner, có kết quả ngay lập tức.

*Multi-platform automatic answer-sheet grader for paper-based multiple-choice exams. Scan with your camera, get results in seconds — no internet upload, all processing on-device.*

## 🌐 Các nền tảng / Platforms

| Nền tảng | Trạng thái | Tải về / Download |
|---|---|---|
| 🪟 **Windows** 10/11 (64-bit) | ✅ Đang phát hành | [Releases](https://github.com/viettien117/ExamScan_Windows_updates/releases/latest) tab bên dưới (file `.msi`) |
| 🤖 **Android** | 🚧 Sắp ra mắt trên Google Play | Đang trong giai đoạn beta — liên hệ `Rubi.ExamScan@gmail.com` để tham gia thử nghiệm |
| 🍎 **iOS** | 🚧 Đang phát triển | Coming soon |

Tất cả nền tảng dùng chung **một thuật toán OpenCV C++ core** — kết quả chấm bài hoàn toàn giống nhau trên Windows, Android và iOS.

---

Repo này host **bản cài đặt Windows mới nhất** và **kênh cập nhật tự động** cho phần mềm ExamScan.

> Trước đây phần mềm có tên "AnswerSheetGrader". Kênh cập nhật cũ tại
> [AnswerSheetGrader-updates](https://github.com/viettien117/AnswerSheetGrader-updates)
> sẽ ngừng dùng sau khi tất cả người dùng đã cập nhật sang phiên bản mới.

---

## Tải xuống bản mới nhất

1. Vào trang [**Releases**](https://github.com/viettien117/ExamScan_Windows_updates/releases/latest)
2. Trong mục **Assets**, tải file `ExamScan-x.y.z-x64.msi` (cuối trang)
3. Double-click file `.msi` vừa tải → đi qua wizard cài đặt
4. Sau khi cài xong, mở phần mềm từ **Start Menu** → tìm "ExamScan"

> Nếu Windows SmartScreen cảnh báo *"Windows protected your PC"*, bấm **More info** → **Run anyway** (file đã được ký bằng EdDSA của nhà phát triển — an toàn).

## Yêu cầu hệ thống

- Windows 10 (build 1803+) hoặc Windows 11
- Kiến trúc **64-bit (x64)**
- ~50 MB dung lượng ổ cứng

## Cập nhật tự động

Sau khi đã cài bản đầu tiên, **bạn không cần truy cập trang này nữa**. Phần mềm sẽ:

- Tự động kiểm tra bản mới mỗi ngày khi bạn mở app
- Hiển thị thông báo khi có version mới
- Tải về + cài đè bản cũ với 1 click "Install Update"
- Bạn cũng có thể kiểm tra thủ công: vào tab **Update** → bấm **"Check for updates"**

## Lịch sử phiên bản

Xem chi tiết changelog của từng phiên bản tại trang [Releases](https://github.com/viettien117/ExamScan_Windows_updates/releases).

## Hỗ trợ

Nếu gặp vấn đề khi cài đặt hoặc sử dụng, vui lòng [tạo issue](https://github.com/viettien117/ExamScan_Windows_updates/issues/new) hoặc liên hệ nhà phát triển.

## Bản quyền

Copyright © 2026 TienDepTrai. All rights reserved.

Phần mềm này được phát hành dưới dạng binary cho người dùng cuối sử dụng miễn phí.
Source code không được phép sao chép, sửa đổi hoặc phân phối lại mà không có sự đồng ý bằng văn bản của tác giả.
