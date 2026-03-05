
## Cài đặt và Khởi chạy (Installation & Setup)

Đảm bảo đã cài đặt Python 3. Sau đó, chạy các lệnh sau tại thư mục gốc của dự án:

```bash
# 1. Tạo môi trường ảo (Virtual Environment)
python3 -m venv .venv

# 2. Kích hoạt môi trường ảo
# Trên macOS/Linux:
source ./.venv/bin/activate
# Trên Windows:
# .venv\Scripts\activate

# 3. Cài đặt các thư viện cần thiết
pip install -r requirements.txt

# 4. Chạy Handwritten.ipynb để xem kết quả code tay neural network để giải thích cơ chế cập nhật tham số mạng

