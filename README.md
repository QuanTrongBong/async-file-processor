# Hệ thống Xử lý Tệp Bất đồng bộ (Đề tài 05)

## Kiến trúc hệ thống
Client -> File API -> RabbitMQ -> Processing Worker -> File Storage & Database

## Hướng dẫn khởi chạy hạ tầng (Tuần 1)
1. Khởi chạy RabbitMQ và PostgreSQL:
   ```bash
   docker-compose up -d