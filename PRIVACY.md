# Privacy Policy / Chính sách quyền riêng tư

**App / Ứng dụng:** ExamScan (`vn.examscan`)
**Developer / Nhà phát triển:** Nguyễn Việt Tiến (`viettien117`)
**Contact / Liên hệ:** viettien117@gmail.com
**Effective date / Hiệu lực từ:** 2026-05-23

---

## English Version

ExamScan is an Android app that helps teachers grade multiple-choice answer
sheets by scanning the paper with the phone camera or selecting images from
the gallery. This policy explains what data the app accesses, how it is used,
and what is shared.

### 1. Data we do NOT collect

We do **not** collect, store on our servers, or sell any of the following:

- Personal identifiers (name, email, phone number, address)
- Account credentials
- Contact list
- Precise location (GPS)
- Microphone audio
- SMS, call logs, or other phones
- Health, fitness, or financial data

ExamScan has **no user accounts** and **no login**. The app does not send
any answer sheet image or grading result to our servers — all OCR and grading
happens **on your device**.

### 2. Data the app processes locally only

| Data | Why | Where it goes |
|---|---|---|
| Camera images you capture in the app | To detect bubbles and grade the answer sheet | Stored only in the app's cache on your device; never uploaded |
| Images you pick from the gallery | Same as above | Same as above |
| Grading results (`.xlsx` export) | Saved when you tap "Export" | Saved to the folder **you** choose via the Android file picker |
| App settings (language VI/EN, free grading credits) | App preferences | Stored only in the app's private `SharedPreferences` on your device |

### 3. Data shared with third parties

ExamScan uses **two** third-party services. Each has its own privacy policy:

#### a) Google AdMob (advertising)

The app shows banner and rewarded video advertisements through the Google
Mobile Ads SDK. AdMob may collect:

- Advertising identifier (AAID) for ad personalization and frequency capping
- Approximate geographic region (country / city) inferred from IP
- Device model, OS version, screen size, language
- App package name and version
- Ad interaction events (impressions, clicks)

Google's full policy: <https://policies.google.com/privacy>
You can reset or disable your Advertising ID from Android Settings →
Privacy → Ads.

Ad content is filtered to **G-rated** (general audiences) only, with
politics, religion, sexual content, gambling, and 18+ categories blocked
at the AdMob account level.

#### b) GitHub (`raw.githubusercontent.com`)

The app downloads its in-app promotional banner images (separate from
AdMob) from a public GitHub repository:
<https://github.com/viettien117/ExamScan_Ads>

GitHub will see your IP address and standard HTTP headers when the app
fetches these files. GitHub's policy:
<https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>

### 4. Permissions the app requests

| Permission | Why |
|---|---|
| `INTERNET` | Load AdMob ads and download promotional banner images from GitHub |
| `CAMERA` (runtime) | Capture answer sheet photos in-app |
| Read media images (Android 13+) / Read external storage (older) | Pick answer sheet photos from the gallery |

The app does **not** request location, contacts, microphone, SMS, or any
other sensitive permission.

### 5. Children

ExamScan is designed for teachers and students. It does not knowingly collect
personal data from children. Ad content is restricted to G-rated to keep the
experience appropriate for minors.

### 6. Data retention

- Images and grading results: kept on **your device** until you delete them
  (the app does not auto-delete; uninstalling the app removes the cache).
- Free-credit counter and language preference: kept on your device; cleared
  when you uninstall the app or clear its data in Android Settings.

### 7. Your rights

Because the app does not collect personal data on our servers, there is
nothing for us to delete on request. You can:

- Uninstall the app to remove all locally stored data.
- Reset your Advertising ID in Android Settings to break ad personalization.
- Email viettien117@gmail.com with any privacy question.

### 8. Changes to this policy

If we make material changes (e.g., add a new third-party SDK), we will update
this page and the "Effective date" above before shipping the change.

---

## Phiên bản tiếng Việt

ExamScan là ứng dụng Android giúp giáo viên chấm bài trắc nghiệm bằng cách
quét bài làm qua camera điện thoại hoặc chọn ảnh từ thư viện. Chính sách
này giải thích app sử dụng dữ liệu gì, ở đâu, và chia sẻ cho ai.

### 1. Dữ liệu chúng tôi KHÔNG thu thập

App **không** thu thập, lưu trên máy chủ, hay bán bất kỳ thứ nào sau đây:

- Thông tin định danh cá nhân (tên, email, số điện thoại, địa chỉ)
- Tài khoản / mật khẩu
- Danh bạ
- Vị trí GPS chính xác
- Âm thanh micro
- SMS, nhật ký cuộc gọi
- Dữ liệu sức khỏe, tài chính

ExamScan **không có tài khoản người dùng** và **không có đăng nhập**. Mọi
thao tác nhận diện ô tròn và chấm điểm đều diễn ra **ngay trên máy bạn**,
không gửi ảnh bài làm về bất kỳ máy chủ nào.

### 2. Dữ liệu app xử lý cục bộ

| Dữ liệu | Mục đích | Lưu ở đâu |
|---|---|---|
| Ảnh chụp trong app | Phát hiện ô tròn và chấm bài | Chỉ trong thư mục cache của app trên máy; không upload đi đâu |
| Ảnh bạn chọn từ thư viện | Tương tự trên | Tương tự trên |
| Kết quả `.xlsx` | Khi bạn bấm "Xuất file" | Lưu vào thư mục **bạn tự chọn** qua hộp thoại Android |
| Cài đặt app (ngôn ngữ VI/EN, số lượt chấm còn) | Tuỳ chọn của bạn | Chỉ trong `SharedPreferences` riêng của app, trên máy |

### 3. Dữ liệu chia sẻ với bên thứ ba

ExamScan dùng **hai** dịch vụ bên thứ ba. Mỗi bên có chính sách riêng:

#### a) Google AdMob (quảng cáo)

App hiển thị quảng cáo banner và quảng cáo có thưởng (rewarded video) qua
SDK Google Mobile Ads. AdMob có thể thu thập:

- Mã định danh quảng cáo (AAID) — để cá nhân hoá và giới hạn tần suất
- Khu vực địa lý tương đối (quốc gia / thành phố) suy từ IP
- Kiểu máy, phiên bản hệ điều hành, kích thước màn hình, ngôn ngữ
- Tên gói + phiên bản app
- Sự kiện tương tác quảng cáo (hiển thị, click)

Chính sách Google: <https://policies.google.com/privacy>
Bạn có thể đặt lại / tắt Mã quảng cáo trong **Cài đặt Android → Quyền
riêng tư → Quảng cáo**.

Nội dung quảng cáo được lọc ở mức **G (Đối tượng chung)** — đã chặn các
mục **chính trị, tôn giáo, tình dục, cờ bạc, 18+** ở cấp tài khoản AdMob.

#### b) GitHub (`raw.githubusercontent.com`)

App tải ảnh banner quảng cáo nội bộ (riêng với AdMob) từ kho công khai
trên GitHub: <https://github.com/viettien117/ExamScan_Ads>

GitHub sẽ thấy địa chỉ IP và HTTP header tiêu chuẩn của bạn khi tải các
file này. Chính sách GitHub:
<https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>

### 4. Quyền app yêu cầu

| Quyền | Mục đích |
|---|---|
| `INTERNET` | Tải quảng cáo AdMob và ảnh banner từ GitHub |
| `CAMERA` (runtime) | Chụp ảnh bài làm trong app |
| Đọc ảnh thư viện (Android 13+) / Đọc bộ nhớ ngoài (cũ) | Chọn ảnh bài làm từ thư viện |

App **không** yêu cầu quyền vị trí, danh bạ, micro, SMS, hay bất kỳ quyền
nhạy cảm nào khác.

### 5. Trẻ em

ExamScan dành cho giáo viên và học sinh. App không cố ý thu thập dữ liệu
cá nhân từ trẻ em. Quảng cáo được giới hạn ở mức G để phù hợp với trẻ vị
thành niên.

### 6. Lưu trữ dữ liệu

- Ảnh và kết quả chấm: nằm trên **máy bạn** đến khi bạn xoá (app không
  tự xoá; gỡ app sẽ xoá hết cache).
- Số lượt chấm còn lại và ngôn ngữ: nằm trên máy; xoá khi gỡ app hoặc
  xoá data app trong Cài đặt Android.

### 7. Quyền của bạn

Vì app không thu thập dữ liệu cá nhân lên máy chủ, không có gì để chúng
tôi xoá khi bạn yêu cầu. Bạn có thể:

- Gỡ app để xoá toàn bộ dữ liệu cục bộ.
- Đặt lại Mã quảng cáo trong Cài đặt Android để cắt cá nhân hoá quảng cáo.
- Email viettien117@gmail.com nếu có câu hỏi về quyền riêng tư.

### 8. Thay đổi chính sách

Khi có thay đổi đáng kể (vd thêm SDK bên thứ ba mới), chúng tôi sẽ cập
nhật trang này và sửa "Hiệu lực từ" ở đầu trang trước khi phát hành.
