# Balance V2.3

Ứng dụng quản lý dòng tiền cá nhân + hợp đồng + nợ/trả góp.

## Mới trong V2.2 — Phân tích thu/chi chủ động
- Tab **Phân tích** mới.
- Biểu đồ Thu nhập chủ động / Chi tiêu chủ động theo 6 hoặc 12 tháng gần nhất.
- Chọn từng tháng trực tiếp trên biểu đồ.
- Hiển thị **chênh lệch dương / âm** của từng tháng.
- So sánh Thu và Chi với tháng trước.
- Danh sách chi tiết theo tháng giống dạng báo cáo tài chính mobile.
- Xem các giao dịch chủ động nằm trong tháng đang chọn.
- Tổng hợp cả khoảng thời gian: Tổng thu / Tổng chi / Chênh lệch.

## Các tính năng giữ nguyên
- Tiền thực tế đang có.
- Thu nhập thụ động chưa thu.
- Hợp đồng chia nhiều đợt thanh toán và % đã nhận.
- Nợ / trả góp, ghi nhận từng kỳ.
- Sửa / xóa giao dịch, hợp đồng, khoản nợ.
- Export CSV, backup / restore JSON.

## Dữ liệu
Vẫn dùng key `balance-v2-data` trong localStorage nên khi deploy đè lên đúng domain cũ, dữ liệu V2/V2.1 tiếp tục được giữ.

## Publish
Giải nén ZIP và kéo toàn bộ file lên Netlify Drop, hoặc deploy bằng GitHub Pages.


## V2.3 — Phân tích đầy đủ 4 nhóm
- Tab Phân tích tính cả Thu nhập chủ động, Thu nhập thụ động, Chi tiêu chủ động và Chi tiêu thụ động.
- Ròng tháng = (Thu chủ động + Thu thụ động đã nhận) - (Chi chủ động + Chi thụ động đã trả).
- Biểu đồ dùng hai cột tổng Thu / tổng Chi; mỗi cột được xếp chồng để thấy phần chủ động và thụ động.
- Chi tiết tháng hiển thị đủ 4 nhóm và toàn bộ giao dịch.


## V2.4 — Analytics color system
- Thu chủ động: xanh lá.
- Thu thụ động: xanh mint.
- Chi chủ động: hồng.
- Chi thụ động: cam.
- Ròng tháng dương: xanh dương.
- Ròng tháng âm: đỏ.
- Đồng bộ màu ở KPI, biểu đồ, legend, chi tiết tháng và danh sách giao dịch trong tab Phân tích.
