# CommandFusion IR Files Repository

Bộ sưu tập các file mã hồng ngoại (IR) cho hệ thống điều khiển CommandFusion, bao gồm các thiết bị điện tử gia dụng phổ biến tại Việt Nam.

## 📋 Mục lục

- [Giới thiệu](#giới-thiệu)
- [Cấu trúc thư mục](#cấu-trúc-thư-mục)
- [Danh sách thiết bị](#danh-sách-thiết-bị)
- [Hướng dẫn sử dụng](#hướng-dẫn-sử-dụng)
- [Định dạng file](#định-dạng-file)
- [Ghi chú](#ghi-chú)

## 🎯 Giới thiệu

Repository này chứa các file IR (.cfir) được sử dụng cho hệ thống điều khiển CommandFusion. Các file này cho phép điều khiển nhiều loại thiết bị điện tử khác nhau thông qua tín hiệu hồng ngoại (Infrared).

### Đặc điểm:
- ✅ Tương thích với CommandFusion iViewer và các sản phẩm CF
- ✅ Hỗ trợ nhiều hãng và dòng thiết bị phổ biến
- ✅ Đã được test và verify tại các dự án thực tế
- ✅ Được tổ chức theo danh mục rõ ràng

## 📁 Cấu trúc thư mục

```
File IR CommandFusion/
├── 01_AC/              # Điều hòa không khí
├── 02_TV/              # Tivi
├── 03_Projector/       # Máy chiếu
├── 04_Audio/           # Thiết bị âm thanh
├── 05_Screen/          # Màn chiếu
├── 06_Fan/             # Quạt
├── 07_Heater/          # Thiết bị sưởi
├── 08_Other/           # Thiết bị khác
├── 09_TV_Box/          # Android TV Box / Apple TV
├── 10_Projects/        # Các dự án cụ thể
└── 99_Archive/         # Lưu trữ
```

## 🔧 Danh sách thiết bị

### 01_AC - Điều hòa không khí

#### Hãng Daikin
- `AC_Daikin_16-30_low-middle-high.cfir` - Standard wall-mounted
- `AC_Daikin_OpTran_16-30_low-middle-high.cfir` - Dòng OpTran
- `AC_Daikin_TreoTuong_16-30_low-middle-high.cfir` - Treo tường
- `Daikin_Wall.cfir` - Tường chuẩn
- `Daikin_Vinhome_*.cfir` - Dự án Vinhome (có chế độ HEAT)

#### Hãng Mitsubishi
- `AC_Mitsubishi_16-30_low-middle-high.cfir` - Standard
- `AC_Mitsubishi_OpTran_*.cfir` - Dòng OpTran
- `AC_MitsubishiPK_*.cfir` - Dòng PK
- `AC_MitsubishiPN_*.cfir` - Dòng PN
- `MITSUBISHI_OPTRAN.cfir` / `MITSUBISHI_OPTRAN_BIG.cfir`

#### Hãng LG
- `AC_LG_16-30_low-middle-high.cfir` - Standard
- `AC_LG_16-30_low-middle-high_cool.cfir` - Chế độ làm lạnh
- `LG.cfir` - Phiên bản tổng hợp

#### Hãng Panasonic
- `AC_Panasonic_16-30_low-middle-high.cfir`
- `Panasonic.cfir`
- `PanasonicSky.cfir`
- `QuatTranPanasonic.cfir` - Quạt trần Panasonic

#### Hãng Samsung
- `AC_SamSung_OpTran_18-30_low-middle-high.cfir`

#### Hãng khác
- **Toshiba**: `AC_Toshiba__16-30_low-middle-high.cfir`, `Toshiba.cfir`
- **Sharp**: `AC_Sharp_TreoTuong.cfir`
- **Sanyo**: `AC_Sanyo_16-30_low-middle-high.cfir`, `Sanyo.cfir`
- **Reetech**: `AC_Reetech_TreoTuong.cfir`, `Reetech.cfir`
- **Casper**: `Casper_Wall.cfir`
- **AQUA**: `AQUA.cfir`
- **Gree**: `Gree.cfir`
- **GENERAL**: `GENERAL.cfir`, `GENERAL_HEAT.cfir`
- **TRANE**: `AC_TRANE_OpTran.cfir`
- **Heavy**: `Heavy.cfir`, `Heavy 2.cfir`

### 02_TV - Tivi

#### Samsung
- `Samsung_SmartTV.cfir` - Smart TV Samsung
- `Samsung_SmartTV_v2.cfir` - Phiên bản 2

#### LG
- `LG_SmartTV_ABaoQ6.cfir` - Smart TV LG (Dự án A Bảo Q6)
- `LG_DVD.cfir` - Đầu DVD LG

#### Panasonic
- `Panasonic_10822.cfir`
- `Panasonic_Vinhome.cfir` - Dự án Vinhome

#### Philips
- `Philips.cfir`

#### Khác
- `HubG3.cfir` - Hub điều khiển G3

### 03_Projector - Máy chiếu
- Epson
- BenQ
- Sony
- Panasonic
- Và các hãng khác...

### 04_Audio - Thiết bị âm thanh
- Amply
- Loa
- Mixer
- DAC

### 05_Screen - Màn chiếu
- Màn chiếu điện
- Màn chiếu cơ

### 06_Fan - Quạt
- Quạt trần
- Quạt đứng
- Quạt điều khiển từ xa

### 07_Heater - Thiết bị sưởi
- Máy sưởi
- Điều hòa hai chiều (chế độ HEAT)

### 08_Other - Thiết bị khác
- Các thiết bị đặc biệt
- Thiết bị tùy chỉnh

### 09_TV_Box
- Android TV Box
- Apple TV
- Google Chromecast

### 10_Projects - Dự án cụ thể
Các file IR được custom cho từng dự án:
- Vinhome
- A Bảo Q6
- Đà Kiến Trúc Q11
- Và các dự án khác...

## 📖 Hướng dẫn sử dụng

### Bước 1: Chọn file IR phù hợp
1. Xác định loại thiết bị cần điều khiển
2. Xác định hãng và model
3. Chọn file tương ứng trong thư mục

### Bước 2: Import vào CommandFusion
1. Mở phần mềm CommandFusion iViewer hoặc guiDesigner
2. Vào **System Manager** > **IR Learning**
3. Click **Import** và chọn file `.cfir`
4. Kiểm tra các lệnh đã được import

### Bước 3: Test và verify
1. Kết nối với thiết bị IR blaster
2. Test từng lệnh để đảm bảo hoạt động đúng
3. Điều chỉnh nếu cần thiết

## 📄 Định dạng file

Các file `.cfir` là file JSON chứa thông tin IR codes:

```json
{
  "RemoteInfo": {
    "DeviceFamily": "AC",
    "Manufacturer": "Daikin",
    "DeviceModel": "",
    "RemoteModel": "full",
    "RemoteID": "Daikin",
    "Description": ""
  },
  "RemoteFunctions": [
    {
      "ID": "on",
      "HeaderData": "...",
      "RepeaterData": "",
      "MinRepeats": 3,
      "FreqDivider": 123,
      "CCF": "..."
    }
  ]
}
```

### Các thông số quan trọng:
- **ID**: Tên lệnh (on, off, temp_up, temp_down, etc.)
- **HeaderData**: Dữ liệu IR dạng hex
- **MinRepeats**: Số lần lặp tối thiểu
- **FreqDivider**: Tần số chia (thường là 123 cho 38kHz)
- **CCF**: Pronto Hex format

## 🔍 Quy ước đặt tên

### Điều hòa (AC):
- `AC_[Hãng]_[Nhiệt độ]_[Tốc độ quạt].cfir`
  - Ví dụ: `AC_Daikin_16-30_low-middle-high.cfir`
  
- `[Hãng]_[Loại]_[Dự án].cfir`
  - Ví dụ: `Daikin_Wall_DaKienTrucQ11.cfir`

### Nhiệt độ:
- `16-30`: Hỗ trợ nhiệt độ từ 16°C đến 30°C
- `18-30`: Hỗ trợ nhiệt độ từ 18°C đến 30°C
- `19-30`: Hỗ trợ nhiệt độ từ 19°C đến 30°C

### Tốc độ quạt:
- `low-middle-high`: Ba mức tốc độ
- `low-high`: Hai mức tốc độ
- `FULL`: Đầy đủ các mức

### Loại máy:
- `OpTran`: Âm trần (Ceiling Cassette)
- `TreoTuong` / `Wall`: Treo tường
- `Sky`: Giấu trần nối ống gió

## 📝 Ghi chú

### Lưu ý khi sử dụng:
1. **Kiểm tra tương thích**: Không phải file nào cũng tương thích với mọi model của cùng hãng
2. **Test trước khi deploy**: Luôn test kỹ trước khi triển khai ở dự án thực tế
3. **Backup**: Lưu backup các file IR đang hoạt động tốt
4. **Tên dự án**: Các file có tên dự án (VD: Vinhome, ABaoQ6) đã được custom cho dự án cụ thể

### Các chức năng thường có:
- **Điều hòa**: On/Off, Temperature (16-30°C), Fan Speed, Mode (Cool/Heat/Dry/Fan)
- **TV**: Power, Volume, Channel, Input Source, Menu
- **Máy chiếu**: Power, Input, Zoom, Focus, Menu
- **Audio**: Power, Volume, Input, Mute

### Troubleshooting:
- Nếu lệnh không hoạt động: Thử tăng `MinRepeats`
- Nếu thiết bị phản hồi không ổn định: Kiểm tra khoảng cách và góc chiếu IR
- Nếu cần customize: Sử dụng IR Learning để học lệnh mới

## 📞 Hỗ trợ

Nếu cần file IR cho thiết bị chưa có trong danh sách hoặc gặp vấn đề, vui lòng:
1. Kiểm tra trong thư mục `99_Archive` - có thể đã được lưu trữ
2. Sử dụng tính năng IR Learning của CommandFusion để tự học
3. Tham khảo các file tương tự của cùng hãng

## 📜 Lịch sử cập nhật

- **30/12/2025**: Tổ chức lại cấu trúc thư mục theo danh mục
  - Log: `reorganize_log_20251230_111212.txt`

---

**Lưu ý**: Các file IR được tổng hợp từ nhiều nguồn và dự án thực tế. Việc sử dụng cần tuân thủ bản quyền và quy định của từng hãng thiết bị.
