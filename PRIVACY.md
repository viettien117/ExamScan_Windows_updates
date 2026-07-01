# Privacy Policy / Chính sách quyền riêng tư

**App / Ứng dụng:** ExamScan (`vn.examscan`)
**Developer / Nhà phát triển:** Nguyễn Việt Tiến (`viettien117`)
**Contact / Liên hệ:** Rubi.ExamScan@gmail.com
**Effective date / Hiệu lực từ:** 2026-07-01

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

The app **does** send anonymous usage statistics, crash/performance
diagnostics, and a push-notification token to Google Firebase to operate and
improve the app and to deliver notifications — see Section 3(c). This never
includes your answer sheet images, grading results, or personal identifiers.

### 2. Data the app processes locally only

| Data | Why | Where it goes |
|---|---|---|
| Camera images you capture in the app | To detect bubbles and grade the answer sheet | Stored only in the app's cache on your device; never uploaded |
| Images you pick from the gallery | Same as above | Same as above |
| Grading results (`.xlsx` export) | Saved when you tap "Export" | Saved to the folder **you** choose via the Android file picker |
| App settings (language VI/EN, remaining grading credits) | App preferences | Stored only in the app's private `SharedPreferences` on your device |
| Reward counters (last daily-login date, last share date, today's rewarded-ad count) | To enforce once-per-day daily/share bonuses and the progressive video reward | Stored only in the app's private `SharedPreferences` on your device |

### 3. Data shared with third parties

ExamScan uses **three** third-party services. Each has its own privacy policy:

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

#### c) Google Firebase (analytics, crash reporting, remote config, push notifications)

The app uses Google Firebase SDKs to understand usage, improve stability,
deliver remote settings, and send notifications. Firebase may collect:

- **Analytics** — anonymous app-usage events (screens viewed, features used) and aggregate device info (model, OS version, language, country)
- **Crashlytics** — crash and performance diagnostics (stack traces, device state) used to fix bugs
- **Remote Config** — fetches configuration values (e.g., reward amounts) from Google's servers
- **Cloud Messaging** — a device push token used to deliver notifications about news, updates, and offers
- A pseudonymous device / installation identifier to support the above

This data is used only to operate and improve ExamScan and is **not** used
to track you across other companies' apps or websites. You can turn
notifications off anytime in your device Settings. Google / Firebase policies:
<https://firebase.google.com/support/privacy> and
<https://policies.google.com/privacy>

### 4. Permissions the app requests

| Permission | Why |
|---|---|
| `INTERNET` | Load AdMob ads, download promotional banner images from GitHub, and connect to Google Firebase |
| `CAMERA` (runtime) | Capture answer sheet photos in-app |
| Read media images (Android 13+) / Read external storage (older) | Pick answer sheet photos from the gallery |
| `POST_NOTIFICATIONS` (Android 13+, optional) | Show news, updates, and offers via push — you choose whether to allow; can be turned off anytime in Settings |

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
- Email Rubi.ExamScan@gmail.com with any privacy question.

### 8. Outbound links and sharing

When you tap a link inside the app (for example, **"Download templates"** in
the About screen, the **bug-report email** address, or the **"Read privacy
policy"** link), the app uses a standard Android Intent to open the URL in
your default browser or email app. Once you leave ExamScan, your interaction
is governed by the privacy policy of the destination site or app — not by us.

The app also includes a **"Share app"** feature. When you tap it, the
Android system share sheet opens so you can pick an app (Zalo, Messenger,
Gmail, etc.) to forward a short promotional text plus a public link to
ExamScan. The text is composed by us; the actual sending and any recipient
data are handled entirely by the app you choose. **We do not see who you
share with, nor do we collect anything from this action** — the only signal
ExamScan stores is a local "last share date" used to limit the daily
share bonus.

### 9. Changes to this policy

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

App **có** gửi số liệu thống kê sử dụng ẩn danh, dữ liệu chẩn đoán sự
cố/hiệu năng, và một mã thông báo đẩy (push token) tới Google Firebase để vận
hành, cải thiện app và gửi thông báo — xem Mục 3(c). Phần này **không bao giờ**
bao gồm ảnh bài làm, kết quả chấm, hay thông tin định danh cá nhân của bạn.

### 2. Dữ liệu app xử lý cục bộ

| Dữ liệu | Mục đích | Lưu ở đâu |
|---|---|---|
| Ảnh chụp trong app | Phát hiện ô tròn và chấm bài | Chỉ trong thư mục cache của app trên máy; không upload đi đâu |
| Ảnh bạn chọn từ thư viện | Tương tự trên | Tương tự trên |
| Kết quả `.xlsx` | Khi bạn bấm "Xuất file" | Lưu vào thư mục **bạn tự chọn** qua hộp thoại Android |
| Cài đặt app (ngôn ngữ VI/EN, số lượt chấm còn) | Tuỳ chọn của bạn | Chỉ trong `SharedPreferences` riêng của app, trên máy |
| Bộ đếm lượt thưởng (ngày nhận daily login gần nhất, ngày nhận share gần nhất, số video đã xem trong ngày) | Để giới hạn quà đăng nhập / chia sẻ mỗi ngày 1 lần và áp dụng thưởng tăng dần cho video | Chỉ trong `SharedPreferences` riêng của app, trên máy |

### 3. Dữ liệu chia sẻ với bên thứ ba

ExamScan dùng **ba** dịch vụ bên thứ ba. Mỗi bên có chính sách riêng:

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

#### c) Google Firebase (phân tích, báo lỗi, cấu hình từ xa, thông báo đẩy)

App dùng các SDK Google Firebase để hiểu cách sử dụng, cải thiện độ ổn định,
nhận cấu hình từ xa và gửi thông báo. Firebase có thể thu thập:

- **Analytics** — sự kiện sử dụng app ẩn danh (màn hình đã xem, tính năng dùng) và thông tin thiết bị tổng hợp (kiểu máy, phiên bản HĐH, ngôn ngữ, quốc gia)
- **Crashlytics** — dữ liệu chẩn đoán sự cố và hiệu năng (stack trace, trạng thái thiết bị) để sửa lỗi
- **Remote Config** — tải các giá trị cấu hình (vd số lượt thưởng) từ máy chủ Google
- **Cloud Messaging** — một mã push token của thiết bị để gửi thông báo về tin tức, cập nhật và ưu đãi
- Một mã định danh thiết bị / bản cài đặt ẩn danh để phục vụ các mục đích trên

Dữ liệu này chỉ dùng để vận hành và cải thiện ExamScan, **không** dùng để
theo dõi bạn xuyên app/website của công ty khác. Bạn có thể tắt thông báo bất
cứ lúc nào trong Cài đặt máy. Chính sách Google / Firebase:
<https://firebase.google.com/support/privacy> và
<https://policies.google.com/privacy>

### 4. Quyền app yêu cầu

| Quyền | Mục đích |
|---|---|
| `INTERNET` | Tải quảng cáo AdMob, ảnh banner từ GitHub, và kết nối Google Firebase |
| `CAMERA` (runtime) | Chụp ảnh bài làm trong app |
| Đọc ảnh thư viện (Android 13+) / Đọc bộ nhớ ngoài (cũ) | Chọn ảnh bài làm từ thư viện |
| `POST_NOTIFICATIONS` (Android 13+, tuỳ chọn) | Gửi tin tức, cập nhật, ưu đãi qua thông báo đẩy — bạn tự chọn cho phép; có thể tắt bất cứ lúc nào trong Cài đặt |

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
- Email Rubi.ExamScan@gmail.com nếu có câu hỏi về quyền riêng tư.

### 8. Liên kết ngoài và chia sẻ

Khi bạn chạm vào một link bên trong app (vd **"Tải mẫu phiếu"** trong màn
Giới thiệu, địa chỉ **email báo lỗi**, hoặc link **"Đọc đầy đủ chính sách"**),
app dùng Android Intent chuẩn để mở URL trong trình duyệt hoặc app email
mặc định của bạn. Khi đã rời ExamScan, mọi tương tác sẽ được điều chỉnh
bởi chính sách quyền riêng tư của trang đích — không phải của chúng tôi.

App cũng có chức năng **"Chia sẻ app"**. Khi bạn chạm vào, hệ thống Android
mở share sheet để bạn chọn app (Zalo, Messenger, Gmail...) gửi một đoạn
text quảng bá ngắn kèm link công khai của ExamScan. Đoạn text do chúng tôi
soạn; việc gửi và mọi dữ liệu người nhận được xử lý hoàn toàn bởi app mà
bạn chọn. **Chúng tôi không biết bạn chia sẻ với ai, cũng không thu thập
gì từ thao tác này** — tín hiệu duy nhất ExamScan lưu là "ngày share gần
nhất" (cục bộ) để giới hạn thưởng chia sẻ mỗi ngày 1 lần.

### 9. Thay đổi chính sách

Khi có thay đổi đáng kể (vd thêm SDK bên thứ ba mới), chúng tôi sẽ cập
nhật trang này và sửa "Hiệu lực từ" ở đầu trang trước khi phát hành.
