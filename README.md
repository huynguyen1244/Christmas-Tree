# 🎄 Christmas Tree - 3D Interactive Experience

Một cây thông Noel 3D tương tác với điều khiển bằng cử chỉ tay và ảnh kỷ niệm.

## 🚀 Chạy ứng dụng

```bash
npm install
npm run dev
```

Mở trình duyệt tại: `http://localhost:5173`

---

## 🖐️ Hướng dẫn cử chỉ tay

| Cử chỉ | Hình ảnh | Chức năng |
|--------|----------|-----------|
| **Nắm tay** | ✊ | Tập hợp cây thông (FORMED) |
| **Xòe tay** | ✋ | Phân tán cây thông (CHAOS) |
| **Ngón cái lên** | 👍 | Zoom camera vào gần |
| **Ngón cái xuống** | 👎 | Zoom camera ra xa |
| **Victory (2 ngón)** | ✌️ | Focus ảnh ngẫu nhiên |
| **I Love You (3 ngón)** | 🤟 | Trả ảnh về vị trí cũ |

### 📍 Di chuyển camera
- **Tay qua trái/phải** → Xoay cây theo chiều ngang
- **Tay lên/xuống** → Thay đổi góc nhìn lên/xuống

---

## 🎵 Tính năng

- ✅ Cây thông 3D với hiệu ứng particle
- ✅ Ảnh kỷ niệm treo trên cây
- ✅ Điều khiển camera bằng tay (MediaPipe AI)
- ✅ Focus/Unfocus ảnh bằng cử chỉ
- ✅ Nhạc nền Giáng sinh
- ✅ Hiệu ứng đèn nhấp nháy

---

## 📁 Cấu trúc thư mục

```
public/
├── photos/          # Ảnh kỷ niệm (1.jpg, 2.jpg, ...)
└── music/           # Nhạc nền (music.mp3)
src/
└── App.tsx          # Component chính
```

---

## 🎮 Nút điều khiển

| Nút | Chức năng |
|-----|-----------|
| 🎵 MUSIC | Bật/tắt nhạc nền |
| 🛠 DEBUG | Hiện/ẩn camera và debug info |
| Assemble/Disperse | Tập hợp/phân tán cây |

---

**Merry Christmas! 🎅🎄✨**
