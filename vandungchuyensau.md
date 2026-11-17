# CHỦ ĐỀ: TỰ ĐỘNG HÓA QUY TRÌNH XỬ LÝ ĐƠN HÀNG
## BƯỚC 1: THIẾT KẾ GIẢI PHÁP (I/O)
1. Input:
- Mã đơn hàng, tên khách hàng.
- Tên sản phẩm, số lượng, đơn giá.
- Phí vận chuyển, trạng thái thanh toán.
2. Output:
- Thông tin đơn hàng.
- Tổng tiền cần thanh toán.
- Trạng thái đơn hàng.
- Cảnh báo lỗi và hướng xử lý.
## BƯỚC 2: VIẾT PROMPT VÀ CHẠY THỬ
1. Prompt hoàn chỉnh:
### VAI TRÒ
Bạn là nhân viên xử lý đơn hàng.

### NHIỆM VỤ
Kiểm tra thông tin, tính tổng tiền và xác định trạng thái đơn hàng.

### QUY TRÌNH
1. Kiểm tra dữ liệu đầu vào.
2. Tính tiền hàng = Số lượng × Đơn giá.
3. Tính tổng tiền = Tiền hàng + Phí vận chuyển.
4. Xác định trạng thái đơn hàng.

### XỬ LÝ LỖI
- Nếu thiếu dữ liệu: yêu cầu bổ sung.
- Nếu dữ liệu sai: thông báo lỗi.
- Nếu gặp lỗi ở một bước: dừng xử lý và nêu nguyên nhân.

### KỸ THUẬT
- Chain-of-Thought: Phân tích logic trước khi trả lời.
- Prompt Chaining: Chia thành các bước kiểm tra, tính toán và xuất kết quả.
- Xử lý đứt gãy: Dừng khi phát hiện lỗi.

### ĐẦU RA
Mã đơn hàng:
Khách hàng:
Tổng thanh toán:
Trạng thái:
Cảnh báo:
Hướng xử lý:


2. Dữ liệu chạy thử:
Mã đơn: DH001
Khách hàng: Nguyễn Văn An
Sản phẩm: Chuột không dây
Số lượng: 2
Đơn giá: 150.000 VNĐ
Phí vận chuyển: 30.000 VNĐ
Thanh toán: Chưa thanh toán


3. Kết quả AI:
Mã đơn: DH001
Khách hàng: Nguyễn Văn An
Tổng thanh toán: 330.000 VNĐ
Trạng thái: Chưa thanh toán
Cảnh báo: Không có.
Hướng xử lý: Chờ khách hàng thanh toán.
