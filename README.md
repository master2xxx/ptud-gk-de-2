# Task Manager

Lê Quang Đỉnh - 22632311<br>
Ứng dụng quản lý công việc được xây dựng bằng Django, cho phép người dùng tạo, theo dõi và cập nhật các công việc.

## Tính năng

- Đăng ký và đăng nhập người dùng
- Quản lý thông tin cá nhân và avatar
- Tạo và quản lý công việc
- Theo dõi trạng thái và thời hạn công việc
- Thông báo công việc quá hạn
- Giao diện người dùng thân thiện với Tailwind CSS

## Cài đặt (Windows)

1. Clone repository:
```cmd
git clone <repository-url>
cd ptud-gk-de-2
```

2. Tạo và kích hoạt môi trường ảo:
```cmd
python -m venv venv
venv\Scripts\activate
```

3. Cài đặt các thư viện cần thiết:
```cmd
pip install -r requirements.txt
```

4. Tạo và áp dụng migrations:
```cmd
python manage.py makemigrations
python manage.py migrate
```

5. Tạo thư mục media và avatars:
```cmd
mkdir media
mkdir media\avatars
copy nul media\avatars\default.png
```

6. Tạo tài khoản admin:
```cmd
python manage.py createsuperuser
```

## Chạy ứng dụng

1. Kích hoạt môi trường ảo (nếu chưa kích hoạt):
```cmd
venv\Scripts\activate
```

2. Chạy server:
```cmd
python manage.py runserver
```

3. Truy cập ứng dụng tại: http://127.0.0.1:8000/

## Cấu trúc URL

- Trang chủ (Danh sách công việc): http://127.0.0.1:8000/
- Đăng ký: http://127.0.0.1:8000/users/register/
- Đăng nhập: http://127.0.0.1:8000/users/login/
- Trang cá nhân: http://127.0.0.1:8000/users/profile/
- Tạo công việc mới: http://127.0.0.1:8000/create/
- Cập nhật công việc: http://127.0.0.1:8000/update/<id>/
- Trang admin: http://127.0.0.1:8000/admin/





