# Soi

**Tiếng Việt** · [English](#english)

Soi xem traffic HTTP/HTTPS của iPhone và Android ngay trên máy Mac, kiểu Proxyman, chạy trên nền [mitmproxy](https://mitmproxy.org).

Repo này chỉ chứa **bản cài và bản cập nhật** của Soi cho macOS.

## Tải và cài

1. Vào [bản mới nhất](https://github.com/hai319/soi-releases/releases/latest), tải file `Soi-<phiên bản>.dmg`.
2. Mở file DMG, kéo **Soi** vào thư mục **Applications**.
3. Lần đầu mở, macOS báo không kiểm tra được app (app chưa đăng ký với Apple): vào **System Settings → Privacy & Security**, bấm **Open Anyway** cạnh dòng Soi, rồi mở lại.
4. Làm theo hướng dẫn cài điện thoại ngay trong app (**Proxy → Hướng dẫn cài điện thoại**, ⌘I), hoặc file `Đọc trước - Read me.txt` trong DMG.

Chạy được trên Mac chip Apple và Mac Intel, macOS 13 trở lên.

## Cập nhật

Từ bản 1.1, Soi tự kiểm tra bản mới mỗi ngày, hoặc vào **Soi → Kiểm tra cập nhật…**. Bấm cài là xong, không cần gỡ app. Map Local, cert và cấu hình được giữ nguyên, điện thoại không phải cài lại cert.

Đang dùng bản 1.0 thì tải DMG mới nhất và kéo đè vào Applications (chọn **Replace**) một lần, các bản sau sẽ tự cập nhật.

Mỗi bản cập nhật đều được ký số, app chỉ cài bản có chữ ký đúng.

---

## English

Soi shows the HTTP/HTTPS traffic of your iPhone and Android phones on your Mac, Proxyman-style, built on [mitmproxy](https://mitmproxy.org).

This repository only hosts the **macOS installers and updates** for Soi.

### Download and install

1. Go to the [latest release](https://github.com/hai319/soi-releases/releases/latest) and download `Soi-<version>.dmg`.
2. Open the DMG and drag **Soi** into **Applications**.
3. On first launch macOS says it can't verify the app (it isn't registered with Apple): open **System Settings → Privacy & Security**, click **Open Anyway** next to Soi, then open it again.
4. Follow the phone setup guide inside the app (**Proxy → Phone setup guide**, ⌘I), or `Đọc trước - Read me.txt` in the DMG.

Runs on Apple silicon and Intel Macs, macOS 13 or later.

### Updates

From version 1.1, Soi checks for new versions daily, or use **Soi → Check for Updates…**. Click install and you're done, no need to remove the app. Map Local rules, certificates and settings are kept, so phones don't need the certificate again.

If you're on 1.0, download the latest DMG and drag it over the old app in Applications (choose **Replace**) once; later versions update themselves.

Every update is digitally signed, and the app only installs updates with a valid signature.
