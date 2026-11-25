# Privacy Policy / Chính sách quyền riêng tư

**App / Ứng dụng:** ExamScan (`vn.examscan`)
**Developer / Nhà phát triển:** Nguyễn Việt Tiến (`viettien117`)
**Contact / Liên hệ:** Rubi.ExamScan@gmail.com
**Effective date / Hiệu lực từ:** 2026-11-25

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

**Payment details.** ExamScan Pro subscriptions are bought and billed entirely
by Google Play (Android) or the App Store (iOS). We never see or receive your
card number, billing address, or store account details.

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
| ExamScan Pro status (active or not, plan type, end date of the prepaid plan) | To unlock unlimited grading and remove ads | Stored only in the app's private storage on your device; re-checked with Google Play / the App Store each time the app opens |

### 3. Data shared with third parties

ExamScan uses **four** third-party services. Each has its own privacy policy:

#### a) Unity LevelPlay / ironSource (advertising)

The app shows **rewarded video advertisements only**, through the Unity
LevelPlay (ironSource) mediation SDK, and only when you tap the "watch a video
for extra credits" button yourself. There are no ads that appear on their own
while you work. The promotional banner at the bottom of the screen is **not**
part of this network — see section (b).

Unity LevelPlay and the ad networks it mediates may collect:

- Advertising identifier (AAID) for ad personalization and frequency capping
- Approximate geographic region (country / city) inferred from IP
- Device model, OS version, screen size, language
- App package name and version
- Ad interaction events (impressions, video completions, clicks)

Unity's full policy: <https://unity.com/legal/game-player-and-app-user-privacy-policy>
You can reset or disable your Advertising ID from Android Settings →
Privacy → Ads.

**Your choice (EEA / UK).** If you are in the European Economic Area or the
United Kingdom, the app asks you — before the first video — whether ads may be
personalized to your interests. If you decline, you still get ads and you still
earn exactly the same number of credits; they are simply not selected based on
you. You can change your answer at any time in **About → Personalized ads**.
Outside those regions this question is not shown.

We configure our advertising partners to exclude adult and age-inappropriate
categories at the strictest setting each partner offers, and we review the
ads that appear in the app periodically. Ad networks source their inventory
from many advertisers, so we cannot guarantee that every single ad will be
suitable. If you see an ad you consider inappropriate, please report it to
Rubi.ExamScan@gmail.com and we will block it.

#### b) GitHub (`raw.githubusercontent.com`)

The app downloads its in-app promotional banner images (these are self-hosted
and reviewed by us, entirely separate from the ad network) from a public
GitHub repository:
<https://github.com/viettien117/ExamScan_Ads>

GitHub will see your IP address and standard HTTP headers when the app
fetches these files. GitHub's policy:
<https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>

#### c) Google Firebase (analytics, crash reporting, remote config, push notifications)

The app uses Google Firebase SDKs to understand usage, improve stability,
deliver remote settings, and send notifications. Firebase may collect:

- **Analytics** — anonymous app-usage events (screens viewed, features used, including opening the ExamScan Pro screen, the plan chosen and whether a purchase completed) and aggregate device info (model, OS version, language, country)
- **Crashlytics** — crash and performance diagnostics (stack traces, device state) used to fix bugs
- **Remote Config** — fetches configuration values (e.g., reward amounts) from Google's servers
- **Cloud Messaging** — a device push token used to deliver notifications about news, updates, and offers
- A pseudonymous device / installation identifier to support the above

This data is used only to operate and improve ExamScan and is **not** used
to track you across other companies' apps or websites. You can turn
notifications off anytime in your device Settings. Google / Firebase policies:
<https://firebase.google.com/support/privacy> and
<https://policies.google.com/privacy>

#### d) Google Play Billing / Apple App Store (ExamScan Pro, optional)

ExamScan Pro (unlimited grading, no ads) is an optional subscription sold
through Google Play Billing on Android and the App Store on iOS. The store
processes the payment, handles renewal and cancellation, and tells the app
whether you have an active plan. The app keeps only that status on your device
and sends no payment information anywhere. You can manage or cancel your
subscription at any time in your Google Play or Apple account settings.
Policies: <https://policies.google.com/privacy> and
<https://www.apple.com/legal/privacy/>

### 4. Permissions the app requests

| Permission | Why |
|---|---|
| `INTERNET` | Load rewarded video ads, download promotional banner images from GitHub, and connect to Google Firebase |
| `CAMERA` (runtime) | Capture answer sheet photos in-app |
| Read media images (Android 13+) / Read external storage (older) | Pick answer sheet photos from the gallery |
| `POST_NOTIFICATIONS` (Android 13+, optional) | Show news, updates, and offers via push — you choose whether to allow; can be turned off anytime in Settings |

The Android ad SDK also declares three background permissions of its own
(`ACCESS_ADSERVICES_TOPICS`, `FOREGROUND_SERVICE`, `RECEIVE_BOOT_COMPLETED`).
They come from the SDK and its scheduling library, not from ExamScan's own
code; the app itself never starts anything at boot and runs no background
service.

The app does **not** request location, contacts, microphone, SMS, or any
other sensitive permission.

### 5. Children

ExamScan is a tool for teachers and exam markers. Students are the people whose
answer sheets get graded, not the intended users of the app. It does not
knowingly collect personal data from children.

We configure every advertising partner to exclude adult and age-inappropriate
categories at the strictest setting that partner offers, and we review the ads
shown in the app periodically. We cannot guarantee that every ad served by a
third-party network will be suitable; report anything inappropriate to
Rubi.ExamScan@gmail.com and we will block it.

### 6. Data retention

- Images and grading results: kept on **your device** until you delete them
  (the app does not auto-delete; uninstalling the app removes the cache).
- Free-credit counter and language preference: kept on your device; cleared
  when you uninstall the app or clear its data in Android Settings.
- ExamScan Pro status: kept on your device; after reinstalling, the app
  restores it from your Google Play / App Store account.

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

**Thông tin thanh toán.** Gói ExamScan Pro được mua và thanh toán hoàn toàn qua
Google Play (Android) hoặc App Store (iOS). Chúng tôi không bao giờ thấy hay nhận
số thẻ, địa chỉ thanh toán hay thông tin tài khoản cửa hàng của bạn.

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
| Trạng thái ExamScan Pro (đang dùng hay không, loại gói, ngày hết hạn gói trả trước) | Mở chấm không giới hạn và tắt quảng cáo | Chỉ trong bộ nhớ riêng của app trên máy; được đối chiếu lại với Google Play / App Store mỗi lần mở app |

### 3. Dữ liệu chia sẻ với bên thứ ba

ExamScan dùng **bốn** dịch vụ bên thứ ba. Mỗi bên có chính sách riêng:

#### a) Unity LevelPlay / ironSource (quảng cáo)

App hiển thị quảng cáo của mạng Unity LevelPlay (ironSource) ở **hai** chỗ:

- **Video có thưởng** — chỉ chạy khi chính bạn bấm nút "xem video nhận thêm
  lượt". Không bao giờ tự hiện lên.
- **Banner ở màn hình Thống kê, Giới thiệu, và danh sách kết quả sau khi chấm
  xong.** Banner này **không** xuất hiện ở màn hình chính, cũng **không** xuất
  hiện trong lúc bạn đang chụp hay đang chấm.

Banner ở cuối **màn hình chính** là quảng cáo nội bộ do chính chúng tôi tự
đăng và tự duyệt, không thuộc mạng nào — xem mục (b). Chạm vào banner nội bộ
đó được cộng lượt; chạm vào banner của mạng thì không, vì các mạng quảng cáo
cấm việc thưởng cho hành vi chạm.

Unity LevelPlay và các mạng quảng cáo mà nó trung gian có thể thu thập:

- Mã định danh quảng cáo (AAID) — để cá nhân hoá và giới hạn tần suất
- Khu vực địa lý tương đối (quốc gia / thành phố) suy từ IP
- Kiểu máy, phiên bản hệ điều hành, kích thước màn hình, ngôn ngữ
- Tên gói + phiên bản app
- Sự kiện tương tác quảng cáo (hiển thị banner, xem hết video, chạm vào)

Chính sách Unity: <https://unity.com/legal/game-player-and-app-user-privacy-policy>
Bạn có thể đặt lại / tắt Mã quảng cáo trong **Cài đặt Android → Quyền
riêng tư → Quảng cáo**.

**Quyền lựa chọn của bạn (EEA / Anh).** Nếu bạn ở Khu vực Kinh tế châu Âu hoặc
Vương quốc Anh, app sẽ hỏi bạn — trước video đầu tiên — rằng quảng cáo có được
cá nhân hoá theo mối quan tâm của bạn hay không. Từ chối thì bạn vẫn có quảng
cáo và vẫn nhận đủ số lượt y như vậy; chỉ là quảng cáo không được chọn riêng
theo bạn. Bạn đổi câu trả lời lúc nào cũng được trong **Giới thiệu → Quảng cáo
cá nhân hoá**. Ngoài các khu vực đó, câu hỏi này không hiện.

Chúng tôi cấu hình mọi đối tác quảng cáo để loại bỏ các danh mục người lớn và
không phù hợp lứa tuổi ở mức chặt nhất mà từng đối tác cho phép, và định kỳ
kiểm tra quảng cáo hiển thị trong app. Mạng quảng cáo lấy nguồn từ rất nhiều
nhà quảng cáo nên chúng tôi không thể bảo đảm mọi quảng cáo đều phù hợp. Nếu
bạn thấy quảng cáo không phù hợp, hãy báo về Rubi.ExamScan@gmail.com và chúng
tôi sẽ chặn.

#### b) GitHub (`raw.githubusercontent.com`)

App tải ảnh banner quảng cáo nội bộ (do chính chúng tôi tự đăng và tự duyệt,
hoàn toàn tách biệt với mạng quảng cáo) từ kho công khai trên GitHub:
<https://github.com/viettien117/ExamScan_Ads>

GitHub sẽ thấy địa chỉ IP và HTTP header tiêu chuẩn của bạn khi tải các
file này. Chính sách GitHub:
<https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement>

#### c) Google Firebase (phân tích, báo lỗi, cấu hình từ xa, thông báo đẩy)

App dùng các SDK Google Firebase để hiểu cách sử dụng, cải thiện độ ổn định,
nhận cấu hình từ xa và gửi thông báo. Firebase có thể thu thập:

- **Analytics** — sự kiện sử dụng app ẩn danh (màn hình đã xem, tính năng dùng, kể cả việc mở màn hình ExamScan Pro, gói được chọn và mua có thành công không) và thông tin thiết bị tổng hợp (kiểu máy, phiên bản HĐH, ngôn ngữ, quốc gia)
- **Crashlytics** — dữ liệu chẩn đoán sự cố và hiệu năng (stack trace, trạng thái thiết bị) để sửa lỗi
- **Remote Config** — tải các giá trị cấu hình (vd số lượt thưởng) từ máy chủ Google
- **Cloud Messaging** — một mã push token của thiết bị để gửi thông báo về tin tức, cập nhật và ưu đãi
- Một mã định danh thiết bị / bản cài đặt ẩn danh để phục vụ các mục đích trên

Dữ liệu này chỉ dùng để vận hành và cải thiện ExamScan, **không** dùng để
theo dõi bạn xuyên app/website của công ty khác. Bạn có thể tắt thông báo bất
cứ lúc nào trong Cài đặt máy. Chính sách Google / Firebase:
<https://firebase.google.com/support/privacy> và
<https://policies.google.com/privacy>

#### d) Google Play Billing / Apple App Store (ExamScan Pro, tuỳ chọn)

ExamScan Pro (chấm không giới hạn, không quảng cáo) là gói thuê bao tuỳ chọn,
bán qua Google Play Billing trên Android và App Store trên iOS. Cửa hàng xử lý
thanh toán, gia hạn, huỷ gói và cho app biết bạn có đang dùng gói nào không. App
chỉ giữ trạng thái đó trên máy bạn và không gửi thông tin thanh toán đi đâu. Bạn
có thể quản lý hoặc huỷ gói bất cứ lúc nào trong cài đặt tài khoản Google Play
hoặc Apple. Chính sách: <https://policies.google.com/privacy> và
<https://www.apple.com/legal/privacy/>

### 4. Quyền app yêu cầu

| Quyền | Mục đích |
|---|---|
| `INTERNET` | Tải quảng cáo video có thưởng, ảnh banner từ GitHub, và kết nối Google Firebase |
| `CAMERA` (runtime) | Chụp ảnh bài làm trong app |
| Đọc ảnh thư viện (Android 13+) / Đọc bộ nhớ ngoài (cũ) | Chọn ảnh bài làm từ thư viện |
| `POST_NOTIFICATIONS` (Android 13+, tuỳ chọn) | Gửi tin tức, cập nhật, ưu đãi qua thông báo đẩy — bạn tự chọn cho phép; có thể tắt bất cứ lúc nào trong Cài đặt |

SDK quảng cáo bên Android còn tự khai ba quyền nền của riêng nó
(`ACCESS_ADSERVICES_TOPICS`, `FOREGROUND_SERVICE`, `RECEIVE_BOOT_COMPLETED`).
Chúng đến từ SDK và thư viện hẹn giờ của nó, không phải từ code của ExamScan;
bản thân app không khởi chạy gì lúc bật máy và không chạy dịch vụ nền nào.

App **không** yêu cầu quyền vị trí, danh bạ, micro, SMS, hay bất kỳ quyền
nhạy cảm nào khác.

### 5. Trẻ em

ExamScan là công cụ dành cho giáo viên và người chấm thi. Học sinh là đối
tượng có bài được chấm, không phải người dùng của app. App không cố ý thu
thập dữ liệu cá nhân từ trẻ em.

Chúng tôi cấu hình mọi đối tác quảng cáo để loại bỏ các danh mục dành cho
người lớn và không phù hợp lứa tuổi, ở mức chặt nhất mà đối tác đó hỗ trợ,
và định kỳ kiểm tra quảng cáo hiển thị trong app. Mạng quảng cáo lấy nguồn
từ rất nhiều nhà quảng cáo nên chúng tôi không thể bảo đảm mọi quảng cáo
đều phù hợp. Nếu bạn thấy quảng cáo không phù hợp, hãy báo về
Rubi.ExamScan@gmail.com, chúng tôi sẽ chặn.

### 6. Lưu trữ dữ liệu

- Ảnh và kết quả chấm: nằm trên **máy bạn** đến khi bạn xoá (app không
  tự xoá; gỡ app sẽ xoá hết cache).
- Số lượt chấm còn lại và ngôn ngữ: nằm trên máy; xoá khi gỡ app hoặc
  xoá data app trong Cài đặt Android.
- Trạng thái ExamScan Pro: nằm trên máy; cài lại app thì app tự khôi phục từ
  tài khoản Google Play / App Store của bạn.

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
