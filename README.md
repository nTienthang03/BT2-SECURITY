# BT2-SECURITY
# I. MÔ TẢ CHUNG
# 🧾 BÀI TẬP: CHỮ KÝ SỐ TRONG FILE PDF

## 📘 MÔN: AN TOÀN VÀ BẢO MẬT THÔNG TIN
**Giảng viên:** Đỗ Duy Cốp  
**Lớp:** 58KTPM  
**Sinh viên thực hiện:** Nguyễn Tiến Thắng  
**Chủ đề:** Chữ ký số trong file PDF  
**Thời điểm giao:** 24/10/2025  
**Công cụ sử dụng:** Python (PyHanko + OpenSSL)

---

## I. GIỚI THIỆU CHỮ KÝ SỐ

### 1. Khái niệm
Chữ ký số là dạng chữ ký điện tử được mã hóa bằng **mật mã khóa công khai (Public Key Cryptography)**, giúp xác minh:
- **Nguồn gốc (Authentication)** – đảm bảo tài liệu do đúng người ký phát hành.  
- **Toàn vẹn (Integrity)** – đảm bảo nội dung không bị thay đổi sau khi ký.  
- **Chống chối bỏ (Non-repudiation)** – người ký không thể phủ nhận việc đã ký.

### 2. Ứng dụng
- Ký hợp đồng điện tử, chứng từ, hóa đơn, file PDF, văn bản pháp lý.  
- Dùng trong các hệ thống hành chính công, ngân hàng, thuế điện tử.  
- Đặc biệt phổ biến trong các file PDF ký bằng **PyHanko**, **Adobe Acrobat**, **Evince**,...

---

## II. CÔNG CỤ VÀ THƯ VIỆN SỬ DỤNG

### 1. Ngôn ngữ & môi trường
- Python 3.11  
- OpenSSL (dùng để tạo khóa RSA và chứng chỉ X.509)  
- Thư viện `pyHanko` – hỗ trợ ký và xác minh PDF.  

### 2. Cài đặt môi trường
```powershell
# Kích hoạt môi trường ảo
& D:/BT2_Security/.venv/Scripts/Activate.ps1

# Cài các thư viện cần thiết
pip install pyHanko pyHanko-certvalidator
pip install cryptography reportlab Pillow

Kết Quả 


<img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/0059a83f-283a-4028-94f4-522162c867b1" />

<img width="1918" height="1079" alt="image" src="https://github.com/user-attachments/assets/648e5ac4-bb73-4ef2-b9a7-e56d13fb6e0d" />

<img width="1059" height="901" alt="image" src="https://github.com/user-attachments/assets/6e31974a-1cb1-4cfc-b83d-f59efb7f5a38" />

