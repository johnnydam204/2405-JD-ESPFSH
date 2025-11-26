# JD-ESPFSH

ESP8266/ESP32 Programmer

---

## Tính năng

- Tương thích với `esp-idf` `flash/monitor` tools
- Tự động đưa chip target vào chế độ flash sau `idf.py flash monitor`
- Có tính năng cấp nguồn 3V3 cho chip target
- Chip giao tiếp: **CH340C/CH340G**
- Cổng USB loại **TYPE-B/MINI-B** phổ biến
- Sử dụng làm tools độc lập hoặc gắn vào JIG FCT/PROG

## Thông tin phiên bản

### V1.0

- Phiên bản đầu tiên
- Sử dụng chip USB2TTL CH340C

### V1.1

- Thay đổi cổng kết nối USB từ MINI-B sang TYPE-B (cổng máy in), tăng cường tiếp xúc và độ bền
- Thêm lựa chọn chip USB-TTL từ CH340C sang CH340G
- Bổ sung thạch anh 12MHz để có thể sử dụng cùng CH340G
- Thêm đầu ra XH2.54-6P để có thể sử dụng dây cắm dạng hàng ngang
- Thêm công tắc bật tắt chế độ cấp nguồn cho target chip
- Thêm lỗ vít 3.2mm để sử dụng vít bắt PCB vào JIG nếu cần thiết
