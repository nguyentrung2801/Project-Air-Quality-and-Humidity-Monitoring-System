# ESP32 Smart Air Quality Monitoring System

## Giới thiệu

Đây là dự án **hệ thống giám sát chất lượng không khí thông minh** sử dụng **ESP32** kết hợp nhiều cảm biến môi trường để đo và lưu dữ liệu theo thời gian thực.

Hệ thống có khả năng:

- Đo nhiệt độ và độ ẩm bằng **DHT22**
- Đo nhiệt độ và độ ẩm chính xác cao bằng **SHT30**
- Đo khí gas / chất lượng không khí bằng **MQ135**
- Đo bụi mịn PM1.0 / PM2.5 / PM10 bằng **PMS7003**
- Hiển thị dữ liệu trực tiếp lên màn hình **TFT ST7735**
- Ghi log dữ liệu vào **thẻ nhớ MicroSD**

---

# Tính năng chính

## Giám sát môi trường thời gian thực

Hiển thị:

- Nhiệt độ
- Độ ẩm
- Điện áp cảm biến MQ135
- PM1.0
- PM2.5
- PM10

## Lưu dữ liệu vào thẻ nhớ SD

Tự động tạo file:

```text
/data1.csv
/data2.csv
/data3.csv
