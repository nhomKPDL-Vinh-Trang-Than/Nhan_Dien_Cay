# 🌿 Nhận Diện Cây bằng Hình Ảnh (YOLO)

Đây là đồ án sử dụng mô hình YOLO để nhận diện một số loại cây từ hình ảnh.

## 🧠 Mô hình sử dụng
- YOLO (You Only Look Once)
- Huấn luyện trên Google Colab
- Gán nhãn dữ liệu thủ công với nhiều class khác nhau

---

## 📦 Tải mô hình đã huấn luyện

Bạn có thể tải mô hình YOLO đã được huấn luyện tại đây:

🔗 [Tải my_model.zip từ Google Drive]([https://drive.google.com/file/d/1qxWCjdJVeWDx_TSg-Efom4Ik192X2FBu/view?usp=drive_link])

---

## 🛠️ Hướng dẫn sử dụng mô hình (trên Google Colab)

### 1. Cài đặt `gdown` và tải mô hình:
```bash
!pip install gdown
!gdown --id 1qxWCjdJVeWDx_TSg-Efom4Ik192X2FBu
!unzip my_model.zip
