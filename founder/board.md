# Hội đồng quản trị – Đèn ngủ thú cưng XG_Studio

**Kết quả biểu quyết: 3 FUND IF (đồng ý có điều kiện), 0 PASS. Điểm trung bình 4,7/10.**

| Thành viên | Điểm | Phiếu |
| --- | --- | --- |
| Offers lens (lời chào hàng) | 5/10 | FUND IF |
| Monopoly lens (lợi thế độc quyền) | 4/10 | FUND IF |
| Product lens (sản phẩm) | 5/10 | FUND IF |

Chi tiết từng người: `founder/board/offers.md`, `monopoly.md`, `product.md`.

## Rủi ro mà nhiều thành viên cùng nêu (xếp trước)

1. **Bước 1 (bán file) đang thử sai thứ, cho sai người.** Cả ba thành viên đều nêu. Giá trị cảm xúc nằm ở phần cá nhân hoá (tên, ngày về nhà, mặt trăng đêm đó), nhưng file thiết kế bán ra lại là bản chung. Người mua file là thợ có máy laser chứ không phải chủ thú cưng. Cults3D và MakerWorld chủ yếu là sân của in 3D, trong khi đây là sản phẩm cắt laser. Nếu file bán ế, bạn sẽ không biết là do ý tưởng hay do cách thử. Monopoly lens thêm một điểm: bán file là trao luôn thiết kế cho các xưởng laser khác làm hàng cạnh tranh.
2. **Chưa có mẫu thật.** Cả ba đều nêu. Chưa biết 8 lớp gỗ 3 mm có chứa vừa máy đồng hồ, LED, cảm biến và pin không, ánh sáng có đều không, pin dùng được bao lâu. Với một món quà kỷ niệm, hàng nhận được khác ảnh là thảm hoạ cảm xúc, không chỉ là một đơn trả hàng.
3. **Giá 250.000 VND chưa có giá vốn.** Cả ba đều nêu. Linh kiện điện tử, 8 lớp gỗ, acrylic, công cá nhân hoá từng đơn và đóng gói có thể ăn hết lợi nhuận. Offers lens còn cho rằng một món quà kỷ niệm có tên riêng không cần bán rẻ nhất.
4. **Chưa rõ người mua: mừng thú cưng về nhà hay tưởng niệm thú cưng đã mất?** Offers và Product lens cùng nêu. Đây là hai khoảnh khắc mua khác nhau, cần thông điệp, giá và kênh bán khác nhau. Còn một câu hỏi nữa: bán ở Việt Nam hay quốc tế?
5. **Chưa có kênh bán và chi phí có khách.** Monopoly và Offers lens cùng nêu: 100 khách đầu tiên đến từ đâu, mỗi người tốn bao nhiêu.

## Chỗ các thành viên khác nhau

- **Product lens** cho rằng sản phẩm đang **làm quá nhiều thứ** (đèn, đồng hồ, tranh kỷ niệm, móc chìa khoá, cảm biến, thanh theo dõi cho ăn, trang QR) và muốn cắt bớt.
- **Offers lens** lại thấy chính những thứ đó là một **"stack" có giá trị**. Lens này chỉ muốn bỏ những phần đắt để làm mà người mua ít cần.
- **Monopoly lens** coi **trang kỷ niệm qua QR** là mầm duy nhất của một lợi thế lâu dài. Product lens lại coi nó là thêm một mối nối dễ hỏng (ai duy trì trang, duy trì bao lâu).

Hướng xử lý: để `/founder-consumer` và `/founder-cfo` phân xử. Chức năng nào người mua không trả tiền thêm và tốn chi phí thì bỏ.

## Danh sách điều kiện (các skill sau sẽ kiểm tra)

- [ ] **Chọn một khoảnh khắc và một người mua:** mừng về nhà hoặc tưởng niệm, Việt Nam hoặc quốc tế. → `/founder-consumer`
- [ ] **Nói được sản phẩm trong một câu.** Giữ một chức năng chính, các chức năng khác phải chứng minh lý do ở lại. → `/founder-consumer`, `/founder-offer`
- [ ] **Xác nhận mức độ khác biệt** so với đèn/tranh gỗ nhiều lớp cá nhân hoá thú cưng đang có trên thị trường: giá bao nhiêu, khách chê gì. → `/founder-competitors`
- [ ] **Có giá vốn thật cho một chiếc** (gỗ, acrylic, đồng hồ, LED, cảm biến, pin, công, cá nhân hoá, đóng gói) trước khi chốt giá 250.000 VND. → `/founder-ops` lấy báo giá, rồi `/founder-cfo` tính
- [ ] **Không phát tán file cắt laser của bản cá nhân hoá.** Thử thị trường bằng ảnh render, trang 3D, danh sách chờ hoặc đặt trước có cọc với giá thật. Nếu vẫn bán file, chỉ bán một mẫu chung. → `/founder-launch`
- [ ] **Làm ít nhất một mẫu vật lý** (thuê xưởng cắt laser), tự dùng vài tuần, chụp ảnh và video thật. → `/founder-ops`, `/founder-launch`
- [ ] **Vẽ hành trình đơn hàng** từ quảng cáo đến lúc treo đèn và quét QR: khách gửi thông tin gì, ai tính mặt trăng, duyệt bản xem trước thế nào, trang QR do ai duy trì và trong bao lâu. → `/founder-ops`
- [ ] **Có một cam kết rõ ràng:** khách duyệt bản cá nhân hoá trước khi cắt, nếu không giống bản duyệt thì làm lại miễn phí. → `/founder-offer`
- [ ] **Chọn một kênh bán đầu tiên** và ghi rõ mục tiêu 100 khách đầu tiên cùng chi phí tối đa cho mỗi khách. → `/founder-marketing`, `/founder-cfo`

## Phiên bản mạnh nhất của mô hình này

Hội đồng thấy mô hình mạnh nhất **khác với kế hoạch bạn đang đề xuất**. Đó không phải là bán file thiết kế. Đó là bán **đèn kỷ niệm cá nhân hoá làm theo từng con thú cưng**, trực tiếp cho chủ nuôi. Tên con vật, ngày nó về nhà và mặt trăng đúng đêm đó là thứ khách mua, và cũng là thứ xưởng khác khó chép. Sản phẩm nên được gọt lại thành một câu và một khoảnh khắc mua rõ ràng. Có lẽ đó là "chiếc đèn giữ lại đêm đầu tiên con về nhà" hoặc bản tưởng niệm, tuỳ kết quả của panel khách hàng. Các chức năng phụ chỉ giữ lại khi người mua thật sự trả tiền cho chúng. Cách thử nên là làm một mẫu thật rồi nhận đặt trước có cọc với giá thật. Thiết kế 3D và trang mô hình tương tác bạn đã có là công cụ bán hàng tốt cho bài thử này. Giá cuối cùng có thể cao hơn 250.000 VND, và hội đồng không coi đó là điều xấu.
