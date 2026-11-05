# Dlayout — phiên bản chuẩn V105

## Trạng thái hiện hành (05/11/2026, Asia/Bangkok)

- **Mới nhất đang lưu trên GitHub:** **V105** tại [Dlayout-V105.zip](Dlayout-V105.zip).
- **Bản được chủ dự án xác nhận OK:** **V105**. Xác nhận trong ChatGPT: “tương tự V105 ok https://github.com/Tidi6969/-Dlayout”. **UserReportedWorking=YES**.
- **Build theo xác nhận người dùng:** `NotSpecified` (chưa có lời xác nhận build cụ thể riêng cho V105). **BuildStatus theo CAD host:** `NotVerified`.
- **NETLOAD/RuntimeStatus theo host:** `NotVerified` nếu yêu cầu chứng cứ thử riêng theo host; không suy diễn PASS các target từ xác nhận OK chung.
- **StandardsStatus:** `NotVerified` (chưa kiểm tra source, SDK và cấu trúc bên trong ZIP V105); CRC/SHA-256 cũng chưa được kiểm tra trong lần này.
- **CAD target theo hồ sơ lịch sử V102:** AutoCAD 2022, AutoCAD 2025, Desktop, GstarCAD 2027. Chưa có thông tin V105 được thử riêng trên host nào.
- **ZIP V105 thực tế:** `Dlayout-V105.zip` tại root, **9.375.720 byte**, Git blob `5a11ee45720f9de88bbedafe96b7233f8b8698bb`.
- **Baseline mặc định lần phát triển tiếp theo:** **V105** (phải đọc và xác minh ZIP/source trước khi sửa). **Version đích mặc định khi có yêu cầu sửa code mới:** V106 theo quy tắc max+1 của STD-17. Đợt đồng bộ này không tạo V106 và không xác định nguồn kỹ thuật tạo V105.

## Liên kết hồ sơ

- [ZIP V105](Dlayout-V105.zip)
- [Nhật ký nghiệm thu V105](Change%20log/V105.txt)
- [Biên bản đánh giá V105 tại DCAD](https://github.com/Tidi6969/DCAD/blob/main/Assessments/Dlayout-V105.md)
- [Danh mục DCAD](https://github.com/Tidi6969/DCAD/blob/main/README.md)
- [Quy ước 17](https://github.com/Tidi6969/QuyUoc/blob/main/17_Autoupdate.md)

## Cây file hiện có sau cập nhật

```text
-Dlayout/
├── Dlayout-V105.zip
├── V102/
│   └── Dlayout-V102.zip
├── Change log/
│   ├── V102.txt
│   └── V105.txt
└── README.md
```

## Lịch sử và giới hạn đánh giá

- **V102:** bản snapshot nguồn gốc đã lưu 31/10/2026. [ZIP V102](V102/Dlayout-V102.zip) và [Change log V102](Change%20log/V102.txt) vẫn được giữ nguyên, trạng thái Build/Runtime của V102 theo hồ sơ cũ là `NotVerified`.
- **V105:** là bản mới nhất được người dùng xác nhận OK và mới nhất có ZIP trên `main`. Không suy ra nội dung thay đổi hoặc khả năng tương thích cụ thể từ việc ZIP có mặt.
- Chỉ đồng bộ metadata/nhật ký và danh mục trạng thái theo mục 8–9 của STD-17; không sửa source, build lại, đổi tên hoặc ghi đè bản ZIP nào.
