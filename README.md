<div align="center">

# 🌸 HanaNapthe Plugin

![Banner](https://via.placeholder.com/1200x300/FF6B6B/FFFFFF?text=HanaNapthe+•+Premium+Minecraft+Plugin)

**Plugin nạp thẻ cào và chuyển khoản QR chuyên nghiệp cho Minecraft Server**

[![Minecraft](https://img.shields.io/badge/minecraft-1.20-green.svg?style=for-the-badge&logo=minecraft)](https://papermc.io/)
[![Java](https://img.shields.io/badge/java-17-orange.svg?style=for-the-badge&logo=java)](https://www.oracle.com/java/)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?style=for-the-badge)](https://github.com/luzanmc/HanaNapthe)

[✨ Tính năng](#-tính-năng)  • [📖 Hướng dẫn](#-hướng-dẫn) • [🎨 Screenshots](#-screenshots) • [💬 Hỗ trợ](#-hỗ-trợ)

---

</div>

## 📋 Giới thiệu

**HanaNapthe** là plugin Minecraft Paper 1.20 cao cấp, được thiết kế đặc biệt cho server Minecraft. Plugin cung cấp giải pháp nạp thẻ cào và chuyển khoản ngân hàng tự động, với giao diện đẹp mắt và trải nghiệm người dùng tối ưu.

### ⭐ Điểm nổi bật

<table>
<tr>
<td width="50%">

#### 🎮 **Đa nền tảng**
- Hỗ trợ Java Edition
- Hỗ trợ Bedrock Edition (Floodgate)
- Giao diện tối ưu cho từng nền tảng
- Form tự động cho Bedrock

</td>
<td width="50%">

#### 💳 **Nạp thẻ cào**
- 5 loại thẻ: Viettel, Vina, Mobi, VNM, Zing
- Tích hợp Card2k.com API
- Xử lý bất đồng bộ nhanh chóng
- Hệ số quy đổi linh hoạt

</td>
</tr>
<tr>
<td>

#### 🏦 **QR Banking**
- Tạo mã QR chuyển khoản tự động
- Hiển thị trên Map item trong game
- Hỗ trợ tất cả ngân hàng Việt Nam
- ThueAPIBank.vn integration

</td>
<td>

#### 🎨 **Giao diện đẹp**
- Adventure API + MiniMessage
- Gradient colors + animations
- Viền kính đẹp mắt
- Hiệu ứng glow tuyệt vời

</td>
</tr>
</table>

---

## 🚀 Tính năng

### 💰 Nạp thẻ cào
- ┌─────────────────────────────────────────┐
- │  ⭐ NẠP THẺ CÀO ⭐                      │
- ├─────────────────────────────────────────┤
- │                                         │
- │  [Viettel] [Vina] [Mobi] [VNM] [Zing]  │
- │                                         │
- │  💎 Chọn loại thẻ và mệnh giá          │
- │  ⚡ Xử lý tức thời, nhận điểm ngay      │
- │                                         │
- └─────────────────────────────────────────┘
**Đặc điểm:**
- ✅ Hỗ trợ 5 loại thẻ phổ biến
- ✅ Mệnh giá từ 10.000đ - 500.000đ
- ✅ Xử lý bất đồng bộ, không lag server
- ✅ GUI đẹp với viền kính và hiệu ứng glow
- ✅ Thông báo Discord tự động
- ✅ Lưu lịch sử nạp thẻ

### 🏦 Chuyển khoản QR
- ╔════════════════╗
- ║ ████  ████  ██ ║
- ║ ██  ████  ████ ║
- ║ ████████████  ║
- ║ ██  ████  ████ ║
- ╚════════════════╝
QR BANK CODE
**Đặc điểm:**
- ✅ Tạo QR code tự động
- ✅ Hiển thị trên map item
- ✅ Tùy chỉnh STK, tên, ngân hàng
- ✅ Nội dung CK có tên người chơi
- ✅ Hướng dẫn chi tiết trong game

### 🏆 Bảng xếp hạng
- ╔═══════════════════════════════════╗
- ║     🏆 TOP NẠP THẺ 🏆            ║
- ╠═══════════════════════════════════╣
- ║  🥇 Player1 - 10,000,000 VNĐ     ║
- ║  🥈 Player2 - 5,000,000 VNĐ      ║
- ║  🥉 Player3 - 2,500,000 VNĐ      ║
- ╚═══════════════════════════════════╝
**Đặc điểm:**
- ✅ Top 10 người nạp nhiều nhất
- ✅ Cập nhật real-time
- ✅ GUI đẹp với medal icons
- ✅ Hiển thị thống kê cá nhân
- ✅ Phần thưởng tự động (tuỳ chỉnh)

---

## 📦 Cài đặt

### Yêu cầu hệ thống

- | Thành phần | Phiên bản | Bắt buộc |
- |-----------|-----------|----------|
- | **Server** | Paper/Purpur 1.20+ | ✅ Có |
- | **Java** | JDK 17+ | ✅ Có |
- | **PlayerPoints** | 3.2.5+ | ⚠️ Khuyến nghị |
- | **PlaceholderAPI** | 2.11.5+ | ⚠️ Khuyến nghị |
- | **Floodgate** | 2.2.2+ | ❌ Tuỳ chọn (cho Bedrock) |

- Cấu hình
- Khi khởi động lần đầu, plugin sẽ tạo thư mục:
- plugins/HanaNapthe/
- ├── config.yml          # Cấu hình chính
- ├── discord.yml         # Webhook Discord
- ├── playerdata.json     # Dữ liệu người chơi
- └── lang/
-   ├── vi.yml          # Tiếng Việt
-   └── en.yml          # Tiếng Anh
- Chỉnh sửa config.yml:
- api:
-  card2k:
-    partner-id: "YOUR_ID_HERE"        # ID từ Card2k.com
-    partner-key: "YOUR_KEY_HERE"      # Key từ Card2k.com
-  thueapibank:
-    api-key: "YOUR_API_KEY"           # API key từ ThueAPIBank

- bank:
-  account-number: "0123456789"         # STK ngân hàng của bạn
-  account-name: "NGUYEN VAN A"         # Tên chủ tài khoản
-  bank-code: "MB"                      # Mã ngân hàng
📖 Hướng dẫn sử dụng Cho người chơi
1️⃣ Nạp thẻ cào
- /napthe  hoặc  /hananapthe
- Các bước:
- Gõ lệnh /napthe để mở GUI
- Chọn loại thẻ (Viettel, Vina, Mobi, v.v.)
- Chọn mệnh giá
- Nhập số serial
- Nhập mã thẻ
- Chờ xử lý (1-30 giây)
- Nhận điểm vào tài khoản
2️⃣ Tạo QR chuyển khoản
- /bank  hoặc  /hanabank
- Các bước:
- Gõ lệnh /bank
- Nhận map item với QR code
- Mở app ngân hàng trên điện thoại
- Quét mã QR
- Kiểm tra thông tin chuyển khoản
- Xác nhận chuyển tiền
- Đợi 1-5 phút để nhận điểm
3️⃣ Xem bảng xếp hạng
- /top  hoặc  /hanatop
4️⃣ Trợ giúp
- /help  hoặc  /hanahelp
- Cho Admin
- Reload plugin
- /hanareload
- Xem logs
👑 Permissions
- hananapthe.admin      # Quyền quản trị
- hananapthe.napthe     # Sử dụng /napthe
- hananapthe.bank       # Sử dụng /bank
- hananapthe.top        # Xem bảng xếp hạng
🎨 Screenshots
- GUI Nạp thẻ

- QR Code trên Map

- Top Leaderboard

💬 Hỗ trợ
🐛 Báo lỗi
- Nếu bạn gặp lỗi, vui lòng tạo issue tại:
👉 GitHub Issues
Template:
**Mô tả lỗi:**
[Mô tả chi tiết]

**Các bước tái hiện:**
1. ...
2. ...

**Log lỗi:**
[Paste log ở đây]
**Môi trường:**
- Server: Paper 1.20.1
- Plugin version: 1.0.0
- Java: 17
📞 Liên hệ
Dicord:https://discord.hanamc.fun/

