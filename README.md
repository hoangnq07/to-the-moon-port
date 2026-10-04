# To the Moon - Port cho ArkOS / R36S (PortMaster)

Bản port game **To the Moon** (kèm Minisode 1 & Minisode 2) dành cho các thiết bị máy chơi game cầm tay chạy **ArkOS** (như R36S, Anbernic RK3326).

## Đặc điểm bản Port
- Hỗ trợ đầy đủ: **Game gốc (Main Story)**, **Siggy - Holiday Special (Minisode 1)**, **SigCorp Minisode 2**.
- Tích hợp **Launcher lựa chọn game** mượt mà viết bằng LÖVE.
- **Việt Hóa 100%**: Đã cài đặt bộ font tiếng Việt (`Open Sans`, `Arial`, `Times`, `Tahoma`) hỗ trợ đầy đủ dấu tiếng Việt, không bị lỗi font hay ký tự lạ.
- **Tối ưu hiệu năng**:
  - Đã làm sạch metadata lỗi `iCCP` trên toàn bộ 718 file PNG, triệt tiêu cảnh báo `libpng` và hiện tượng khựng khung hình do nghẽn I/O ghi thẻ nhớ SD.
  - Tối ưu `mkxp.conf` (`frameSkip=false`, `subImageFix=false`) giúp game chạy ổn định mượt mà ở 40 FPS gốc.
  - Tự động kích hoạt Governor CPU/GPU `performance` khi chơi game.

## Cài đặt trên ArkOS (R36S)
1. Chép file `To the Moon.sh` vào thư mục `/roms/ports/` (hoặc `/roms2/ports/`).
2. Chép toàn bộ thư mục `to_the_moon/` vào `/roms/ports/to_the_moon/`.
3. Khởi động lại EmulationStation hoặc vào mục **Ports** để chọn và chơi game.

## Điều khiển (Controls)
- **D-Pad / Cần Analog trái**: Di chuyển nhân vật
- **Cần Analog phải**: Di chuyển con trỏ chuột
- **Nút A**: Tương tác / Đồng ý (`Enter` / `Input::C`)
- **Nút B**: Hủy / Menu (`Esc` / `Input::B`)
- **Nút X**: Chạy nhanh (`Shift` / `Input::A`)
- **Nút Y**: Giảm tốc độ chuột (ngắm chuột chính xác)
- **Nút R1**: Chuột trái (Tương tác / Click)
- **Nút L1**: Chuột phải (Hủy / Bỏ chọn)
- **Nút L2 / R2**: Đổi trang menu (`Q` / `W`)
- **Start**: `Enter`
- **Select + Start**: Thoát game
