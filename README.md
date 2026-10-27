# 238101_NguyenThanhNhatHao

## Hệ Thống Quản Lý Nhân Sự (HR Management System)

## Thông Tin Sinh Viên
- **Họ và tên:** Nguyễn Thanh Nhật Hảo
- **MSSV:** 238101
- **Lớp:** DH23TIN10

## Mô Tả Hệ Thống
Ứng dụng quản lý nhân sự cho phép xem danh sách, xem chi tiết, thêm mới, cập nhật thông tin, tìm kiếm và xóa hồ sơ nhân viên.

## Công Nghệ Sử Dụng
- **Frontend:** React, HTML/CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Containerization:** Docker & Docker Hub
- **Deployment:** Render

## Hướng Dẫn Chạy Ở Môi Trường Phát Triển (Local)
1. Clone dự án:
   ```bash
   git clone [https://github.com/your-username/238101_NguyenThanhNhatHao.git](https://github.com/your-username/238101_NguyenThanhNhatHao.git)
   cd 238101_NguyenThanhNhatHao

## Docker Hub

### Backend

- Docker Hub: https://hub.docker.com/r/YOUR_DOCKERHUB_USERNAME/backend
- Image: YOUR_DOCKERHUB_USERNAME/backend:latest

### Chạy Backend bằng Docker

```bash
docker pull YOUR_DOCKERHUB_USERNAME/backend:latest
docker run -d --name hr-backend -p 5000:5000 --env-file backend/.env YOUR_DOCKERHUB_USERNAME/backend:latest
```

Kiểm tra API:

- http://localhost:5000/health
- http://localhost:5000/api/employees
