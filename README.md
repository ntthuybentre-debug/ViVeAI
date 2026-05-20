# ViVe AI — Hướng Dẫn Cài Đặt & Sử Dụng

> **Phần mềm tạo video AI tự động** sử dụng Google Veo 3.1

---

## 📋 Yêu Cầu Hệ Thống

| Yêu cầu | Chi tiết |
|----------|----------|
| **Hệ điều hành** | Windows 10 (21H2+) / Windows 11 |
| **Google Chrome** | Phải cài sẵn trên máy |
| **Tài khoản Gmail** | Bất kỳ tài khoản Gmail nào |

> ⚠️ **Không cần cài thêm** Node.js, Python hay bất kỳ phần mềm nào khác.

---

## 🚀 Bước 1: Cài Đặt

1. Tải file **`ViVe AI_1.0.0_x64-setup.exe`** từ [Releases](../../releases)
2. Chạy file cài đặt
3. Nhấn **Next** → **Install** → Đợi cài xong → **Finish**
4. Shortcut **ViVe AI** sẽ xuất hiện trên Desktop

---

## 🔑 Bước 2: Kích Hoạt Bản Quyền

1. Mở **ViVe AI** từ shortcut trên Desktop
2. Lần đầu mở, app sẽ hiển thị **Key máy** (Hardware ID) của bạn
3. **Copy key** này và gửi qua **Zalo** cho Admin
4. Admin sẽ kích hoạt key cho bạn trong hệ thống
5. Sau khi được kích hoạt, mở lại app để bắt đầu sử dụng

---

## 🌐 Bước 3: Đăng Nhập Gmail Trên Chrome

Khi mở app, **Chrome sẽ tự động mở** một cửa sổ riêng. Đây là Chrome chuyên dụng của ViVe AI.

1. Trên cửa sổ Chrome vừa mở, **đăng nhập vào Gmail** bất kỳ
2. Chrome sẽ tự chuyển đến trang `labs.google/fx/tools/flow`
3. **Giữ cửa sổ Chrome này mở** — không đóng nó lại

---

## 🧩 Bước 4: Cài Extension Captcha (Chỉ Làm 1 Lần)

### 4.1 — Mở trang Extensions

Trên cửa sổ Chrome của ViVe AI:
1. Gõ vào thanh địa chỉ: `chrome://extensions` rồi nhấn **Enter**

### 4.2 — Bật Developer Mode

1. Ở góc **trên bên phải** trang Extensions, tìm công tắc **"Developer mode"**
2. **Bật ON** (gạt sang phải, chuyển sang màu xanh)

### 4.3 — Load Extension

1. Sau khi bật Developer mode, nhấn nút **"Load unpacked"** (góc trên bên trái)
2. Một hộp thoại chọn thư mục sẽ hiện ra
3. Điều hướng đến thư mục cài đặt ViVe AI:

```
C:\Users\<Tên_User>\AppData\Local\ViVe AI\resources\extension
```

> 💡 **Mẹo tìm nhanh:** Click chuột phải vào shortcut **ViVe AI** trên Desktop → **Open file location** → Vào thư mục `resources` → Chọn thư mục `extension`

4. Chọn thư mục `extension` → Nhấn **Select Folder**
5. Extension sẽ xuất hiện trong danh sách — **hoàn tất!**

> ✅ Bạn chỉ cần làm bước này **1 lần duy nhất**. Lần sau mở app, extension tự động có sẵn.

---

## ✅ Bước 5: Kiểm Tra Trạng Thái — Đợi Xanh Mới Chạy!

Trên giao diện ViVe AI, quan sát **2 chỉ báo trạng thái**:

| Chỉ báo | 🔴 Đỏ = Chưa sẵn sàng | 🟢 Xanh = Sẵn sàng |
|---------|----------------------|-------------------|
| **Captcha** | Extension chưa kết nối / Chrome chưa mở | Extension hoạt động, captcha sẵn sàng |
| **Tokens** | Chưa tải được token từ server | Token đã tải, sẵn sàng sinh video |

### ⚠️ QUAN TRỌNG:
> **Chỉ bắt đầu nhập prompt và chạy khi CẢ HAI chỉ báo đều XANH.**
>
> Nếu chạy khi còn đỏ → video sẽ lỗi hoặc không sinh được.

### Nếu Captcha vẫn đỏ:
- Kiểm tra Chrome có đang mở không
- Kiểm tra đã đăng nhập Gmail chưa
- Kiểm tra Extension đã được load chưa (Bước 4)

### Nếu Tokens vẫn đỏ:
- Nhấn nút **Refresh Tokens** trên app
- Kiểm tra kết nối internet
- Liên hệ Admin nếu vẫn không xanh

---

## 🎬 Bước 6: Bắt Đầu Tạo Video

1. Đảm bảo **Captcha 🟢** và **Tokens 🟢** đều xanh
2. Nhập **prompt** mô tả video bạn muốn tạo
3. Chọn cài đặt (chất lượng, thời lượng, tỷ lệ khung hình)
4. Nhấn **Generate** và đợi kết quả

---

## ❓ Câu Hỏi Thường Gặp

**Q: Tại sao Chrome mở lên một cửa sổ riêng?**
> A: ViVe AI sử dụng Chrome riêng biệt (không ảnh hưởng Chrome cá nhân của bạn) để xử lý captcha tự động. Không đóng cửa sổ này khi đang dùng app.

**Q: Tôi có thể dùng tài khoản Gmail nào?**
> A: Bất kỳ tài khoản Gmail nào cũng được. Không cần tài khoản đặc biệt.

**Q: Extension có cần cài lại sau khi update app không?**
> A: Không. Extension được lưu trong profile Chrome riêng, tự động giữ lại qua các lần cập nhật.

**Q: App bị treo / không phản hồi?**
> A: Đóng app và mở lại. Nếu vẫn lỗi, liên hệ Admin qua Zalo.

---

## 📞 Hỗ Trợ

Liên hệ **Admin qua Zalo** để được hỗ trợ kích hoạt key, xử lý lỗi, hoặc hướng dẫn thêm.
