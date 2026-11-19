# Band Nav (NavBand)

Đưa chỉ đường của Google Maps xuống vòng tay Xiaomi Smart Band: mỗi lần sắp rẽ, vòng tay rung và hiện hướng rẽ, khoảng cách, tên đường, kèm hình mũi tên của hướng đó. Điện thoại để trong túi.

Band Nav không cài gì lên vòng tay. Nó đọc thông báo dẫn đường của Google Maps trên điện thoại rồi gửi lại thành thông báo ngắn; Mi Fitness chuyển thông báo đó xuống vòng như mọi thông báo khác.

## Cần có

- Điện thoại Android 8 trở lên, chip 64-bit (hầu hết máy từ 2018 về sau).
- Google Maps.
- Vòng tay đã ghép với Mi Fitness, và Mi Fitness đang chuyển thông báo ứng dụng xuống vòng.

Mới được chạy thật trên một máy: Xiaomi Smart Band 10 Pro, bản quốc tế. Các vòng khác nhận thông báo qua Mi Fitness về lý thuyết cũng dùng được, nhưng chưa ai thử.

## Cài đặt

1. Vào mục **Releases** của trang này, tải file `BandNav-<phiên bản>.apk` về điện thoại và cài. Điện thoại sẽ hỏi cho phép cài app ngoài CH Play; Play Protect có thể cảnh báo vì app không nằm trên CH Play.
2. Mở Band Nav. Mục **Cần làm** liệt kê từng việc còn thiếu, mỗi việc một nút:
   - cho Band Nav đọc thông báo,
   - cho Band Nav gửi thông báo,
   - cài 8 app mũi tên (mỗi hướng rẽ một app nhỏ khoảng 25 KB, đã nằm sẵn trong Band Nav; Android hỏi xác nhận từng app),
   - cho từng app mũi tên gửi thông báo.
3. Mở Mi Fitness, mục Thông báo ứng dụng, bật Band Nav và 8 app mũi tên (Rẽ trái, Rẽ phải, Chếch trái, Chếch phải, Đi thẳng, Quay đầu, Vòng xuyến, Đến nơi). Bước này Band Nav không tự kiểm tra được.
4. Khi mục Cần làm báo **Đã sẵn sàng**, bấm "Gửi thông báo thử" để xem vòng tay có nhận không.

## Dùng

Mở Google Maps, chọn điểm đến, bấm Bắt đầu. Không cần mở Band Nav.

Sau mỗi lần cập nhật Band Nav, mở app một lần trước khi dẫn đường; Android ngắt quyền đọc thông báo khi cài đè và app chỉ nối lại được khi được mở.

### Vì sao có 8 app mũi tên

Vòng tay hiện biểu tượng của app gửi thông báo, và mỗi app chỉ có một biểu tượng. Muốn vòng hiện mũi tên rẽ trái thì thông báo phải đến từ một app có biểu tượng là mũi tên rẽ trái. Không thích thì tắt công tắc "Hiện hình mũi tên trên vòng"; khi đó vòng chỉ hiện chữ và không cần 8 app này.

### Khi vòng không hiện đúng hướng

Google Maps không phải lúc nào cũng viết hướng rẽ bằng chữ. Với những bước chỉ có hình mũi tên, vào thẻ **Hướng rẽ** trong Band Nav: các hình mũi tên thu được từ Maps hiện ở đó, bấm vào hướng đúng với từng hình một lần là app nhớ.

## Quyền riêng tư

- Band Nav xin quyền đọc thông báo, nhưng chỉ xử lý thông báo dẫn đường đang chạy của Google Maps và bỏ qua mọi thông báo khác.
- App không có quyền truy cập mạng nên không gửi được dữ liệu đi đâu. Toàn bộ quyền của app: gửi thông báo, đọc thông báo (do bạn bật), và mở trình cài đặt cho app mũi tên. Lộ trình và hình mũi tên chỉ lưu trên điện thoại của bạn.
- Quyền cài ứng dụng chỉ dùng để mở trình cài đặt của Android cho 8 app mũi tên đi kèm.

## Giới hạn đã biết

- Phụ thuộc vào cách Google Maps viết thông báo; Maps đổi cách viết thì có thể phải cập nhật app.
- Không có bản đồ thu nhỏ trên vòng, chỉ có hướng rẽ và chữ.
- Một số ký hiệu mũi tên trong chữ không hiển thị được trên vòng, nên chỉ các hướng trái, phải, thẳng có ký hiệu đi kèm chữ.
- Chưa có bản cho iPhone.

## Ghi chú

Đây là dự án cá nhân, không liên quan tới Google hay Xiaomi. Google Maps và Mi Fitness là sản phẩm của các chủ sở hữu tương ứng. Dùng khi lái xe thì ưu tiên an toàn: liếc vòng tay khi đã rung, đừng thao tác điện thoại lúc đang chạy.
