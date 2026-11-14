<div align="center">

# 🎨 LuCI Theme Preview V3.0
**Hệ thống giả lập phần cứng OpenWrt, chụp ảnh Retina 2x & Sandbox tương tác trực tiếp**

[![OpenWrt 24.10](https://img.shields.io/badge/OpenWrt-24.10_Snapshot-00B5E2?style=for-the-badge&logo=openwrt&logoColor=white)](https://openwrt.org/)
[![Router Spoof](https://img.shields.io/badge/Router-Xiaomi_CR6608_(MT7621)-FF6900?style=for-the-badge&logo=xiaomi&logoColor=white)](#)
[![Retina 2x](https://img.shields.io/badge/Quality-Retina_2x_WebP-6750A4?style=for-the-badge)](#)
[![Live Portal](https://img.shields.io/badge/Live_Portal-GitHub_Pages-2EA44F?style=for-the-badge&logo=githubpages&logoColor=white)](https://vudubai-2026.github.io/luci-theme-preview/)

</div>

---

### 🚀 Tính năng nổi bật (V3.0)
- **Mô phỏng phần cứng thực tế:** Giả lập **Xiaomi Mi Router CR6608** (SoC MediaTek MT7621, RAM 256MB, Wi-Fi 6 2.4G/5G, 3 LAN + 1 WAN, DHCP leases, Firewall NAT, SQM Cake QoS, UPnP & DDNS).
- **Smart Auto-Detect:** Tự động nhận diện & đóng gói mọi cấu trúc repo theme (`htdocs/`, `www/`, `files/` và tự động giải nén file `.ipk`).
- **Interactive Sandbox V3.0:** Trải nghiệm bấm chuyển trang, mở tab, chuyển đổi **Desktop / Mobile** và **Light / Dark mode** trực tiếp trên trình duyệt mà không cần router thật.
- **Tự động dọn dẹp:** Tự động xóa các lần chạy Actions bị lỗi và giới hạn lưu tối đa **2 bản preview lỗi gần nhất**.

### 🛠️ Cách chạy kiểm thử theme mới
1. Chuyển sang tab **[Actions](../../actions)** $\rightarrow$ chọn **LuCI Theme Preview V3.0**.
2. Bấm **Run workflow**, dán link GitHub của theme cần test (ví dụ: `jerrykuku/luci-theme-argon` hoặc `peditx/luci-theme-peditx`).
3. Chờ hoàn tất, kết quả sẽ tự động deploy lên **[Trang Tổng Hợp](https://vudubai-2026.github.io/luci-theme-preview/)** và cập nhật vào bảng bên dưới.

---

### 📊 Bảng xếp hạng & Kết quả kiểm thử (0 đạt · 2 lỗi lưu gần nhất)

| Giao diện | Repository | Trạng thái & UI/UX | Hiệu năng | Trải nghiệm & Cập nhật |
| :---: | :--- | :--- | :--- | :--- |
| <a href="https://vudubai-2026.github.io/luci-theme-preview/jerrykuku-luci-theme-argon/"><img src="https://vudubai-2026.github.io/luci-theme-preview/jerrykuku-luci-theme-argon/shots/argon-login-desktop-light-t.webp" width="180" alt="jerrykuku/luci-theme-argon"/></a> | **[jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)** | 🔴 **Lỗi** (2 lỗi)<br>⚠️ 55 cảnh báo | 📦 `606 KB`<br>⚡ `93 ms` | [🖼️ Xem Album](https://vudubai-2026.github.io/luci-theme-preview/jerrykuku-luci-theme-argon/) • [🕹️ Sandbox](https://vudubai-2026.github.io/luci-theme-preview/jerrykuku-luci-theme-argon/#sandbox)<br><sub>🕒 14/11/2026</sub> |
| ⚠️ *No Preview* | **[vudubai-2026/luci-theme-preview](https://github.com/vudubai-2026/luci-theme-preview)**<br><code>@cdb821615fae71105ea75f687ea025107a72d644</code> | 🔴 **Lỗi** (0 lỗi)<br>⚠️ 0 cảnh báo | - | [🖼️ Xem Album](https://vudubai-2026.github.io/luci-theme-preview/vudubai-2026-luci-theme-preview/) • [🕹️ Sandbox](https://vudubai-2026.github.io/luci-theme-preview/vudubai-2026-luci-theme-preview/#sandbox)<br><sub>🕒 14/11/2026</sub> |

<div align="center">
<sub>Được vận hành tự động bởi GitHub Actions & Playwright Retina Engine</sub>
</div>
