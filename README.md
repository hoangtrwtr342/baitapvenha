Phần I: Phân tích lỗi trong lời giải
Lời giải của sinh viên mắc phải 3 lỗi sai chính do sự nhầm lẫn cơ bản giữa hai đơn vị Bit (b) và Byte (B) trong truyền thông mạng:
Nguyên nhân: Sinh viên đã đồng nhất chữ "b" (bit) và chữ "B" (Byte). Trong hệ thống đo lường dữ liệu, $1\text{ Byte} = 8\text{ Bits}$. Do đó, tốc độ mạng tính bằng Megabit trên giây ($\text{Mbps}$) phải chia cho 8 mới ra tốc độ tải thực tế tính bằng Megabyte trên giây ($\text{MB/s}$). Tốc độ thực tế của gói 100 Mbps 

2. Nhận định 2: "Nhà mạng chỉ cung cấp 12.5% tốc độ cam kết" $\rightarrow$ SAI
Nguyên nhân: Nhận định này được suy ra từ sai lầm ở nhận định 1. Vì sinh viên tưởng $100\text{ Mbps} = 100\text{ MB/s}$, nên khi thấy trình duyệt hiển thị $12.5\text{ MB/s}$, sinh viên nghĩ nhà mạng gian lận. Thực tế, con số $12.5\text{ MB/s}$ hoàn toàn khớp chính xác với gói cước $100\text{ Mbps}$ mà nhà mạng cung cấp.

3. Nhận định 3: "Nếu mạng giảm xuống 40 Mbps, tải tệp 1 GB sẽ mất khoảng 25 giây" $\rightarrow$ SAI
Nguyên nhân: Sinh viên tiếp tục nhầm lẫn khi lấy $40\text{ Mbps}$ nhân với $25\text{ giây}$ ($40 \times 25 = 1000$) mà quên mất việc quy đổi đơn vị dung lượng tệp ($1\text{ GB} = 1024\text{ MB}$) và tốc độ mạng ($\text{Mbps}$ sang $\text{MB/s}$).

Phần II: Hoàn thiện bài giải và Kết luận
1. Lời giải đúng
Bước 1: Quy đổi tốc độ gói mạng sang đơn vị tải thực tế ($\text{MB/s}$)Tốc độ thực tế của gói $100\text{ Mbps}$ là: $100 \div 8 = 12.5\text{ MB/s}$ (Trình duyệt hiển thị đúng $12.5\text{ MB/s}$).Bước 2: Tính thời gian tải khi mạng giảm xuống $40\text{ Mbps}$Tốc độ tải thực tế khi mạng còn $40\text{ Mbps}$ là: $40 \div 8 = 5\text{ MB/s}$.Quy đổi dung lượng tệp: $1\text{ GB} = 1024\text{ MB}$.Thời gian tải tệp $1\text{ GB}$ là:$$1024\text{ MB} \div 5\text{ MB/s} = 204.8\text{ giây}$$


2. Kết luận cuối cùng
 Nam KHÔNG NÊN khiếu nại nhà mạng.
Nhà mạng đã cung cấp đúng và đủ tốc độ cam kết ($100\text{ Mbps}$). Sự chênh lệch giữa con số $100$ và $12.5$ chỉ là sự quy đổi đơn vị đo lường cơ bản trong công nghệ thông tin ($\text{Megabit}$ và $\text{Megabyte}$), không phải lỗi từ phía nhà mạng.

HỌ VÀ TÊN : BÙI MINH HOÀNG
LỚP : HCM_CNTT1
BÀI TẬP SESSON 2
BÀI : Chẩn đoán tốc độ Internet cáp quang
