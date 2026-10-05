# 3. Mẫu Phiếu Ghi Nhận Phản Hồi Cá Nhân (Prototype Feedback Note)

**Họ tên người phỏng vấn:** Phan Thị Khánh Linh

**Tester / Bối cảnh:** Nguyễn Thị Bảo Trang — học viên đã học Cloud 12, chuẩn bị học Cloud 13.

**Selected Option:** Option B — AI nhắc ôn, người chọn

**Task:** Xử lý các điểm chưa hiểu trước Cloud 13.

## Tiêu điểm quan sát hành vi

### First Action (Hành động đầu tiên)

**Tester bấm vào đâu, nhìn vào đâu đầu tiên?**

Tester nhận notification từ AI về các nội dung nên ôn trước Cloud 13. Tester mở notification, đọc nội dung AI đề xuất và chú ý đến phần lý do AI đưa ra trước khi thực hiện hành động tiếp theo.

### Hesitation (Điểm do dự, dừng lại hoặc hiểu sai)

**Chỗ nào khiến tester lúng túng hoặc hiểu lầm?**

Tester có một khoảng dừng sau khi đọc recommendation để xem lý do AI đề xuất các nội dung cần ôn. Tester chưa chủ động kiểm tra toàn bộ danh sách các điểm chưa hiểu mà tiếp tục dựa trên danh sách AI đề xuất.

Khi AI chỉ hiển thị một số điểm cần ôn và bỏ sót **điểm ①**, tester chưa ngay lập tức nhận ra rằng recommendation có thể chưa đầy đủ.

**Interpreted:** Có khả năng tester đang xem danh sách AI đề xuất là phạm vi chính cần xử lý cho task. Tuy nhiên, chưa đủ bằng chứng để kết luận tester tin rằng danh sách AI chắc chắn đầy đủ.

### Evidence Checking (Minh chứng được đọc hay bỏ qua)

**Tester có kiểm tra nguồn trích dẫn / cảnh báo không?**

Tester đọc phần lý do AI đưa ra trước khi chọn **“Ôn ngay”**.

Tester không kiểm tra nguồn trích dẫn bên ngoài vì prototype không yêu cầu nguồn trích dẫn riêng. Minh chứng chính được tester kiểm tra là phần giải thích tại sao AI đề xuất những nội dung đó.

Sau khi chọn **“Ôn ngay”**, AI cố tình bỏ sót điểm ①. Khả năng kiểm tra lại recommendation được thể hiện thông qua lựa chọn **“Xem tất cả”**.

### Control & Recovery (Cách sửa sai hoặc lấy lại quyền kiểm soát)

**Tester dùng nút nào để khắc phục khi thấy kết quả chưa ưng ý?**

Cơ chế recovery được kiểm thử thông qua nút **“Xem tất cả”**.

Nếu tester chủ động chọn **“Xem tất cả”**, tester có thể xem toàn bộ các điểm chưa hiểu thay vì chỉ xem danh sách AI đề xuất. Tester có thể phát hiện điểm ① bị AI bỏ sót và tự xử lý bổ sung.

Nếu tester không mở **“Xem tất cả”**, tester tiếp tục xử lý các nội dung AI đề xuất và điểm ① vẫn chưa được xử lý.

**Interpreted:** “Xem tất cả” có thể đóng vai trò là cơ chế giúp người học lấy lại quyền kiểm soát khi recommendation của AI không đầy đủ.

### Selected Option (Phương án được tester lựa chọn)

**Option [ B ]**

Tester lựa chọn flow trong đó AI chủ động nhắc các nội dung nên ôn trước Cloud 13, giải thích lý do đề xuất và cho phép tester quyết định có **“Ôn ngay”** hay không.

### Trade-offs (Lý do chọn và sự đánh đổi chấp nhận)

**Tester sẵn sàng hy sinh điều gì để chọn phương án này?**

Tester sử dụng recommendation của AI để nhanh chóng xác định những nội dung cần ôn thay vì tự rà soát toàn bộ nội dung Cloud 12 ngay từ đầu.

Đổi lại, tester có thể phải chấp nhận rủi ro AI bỏ sót một số nội dung.

Trade-off chính:

> **Giảm effort tìm kiếm ↔ tăng rủi ro phụ thuộc vào recommendation của AI.**

**Decided:** Giữ Option B nhưng không để AI recommendation trở thành con đường duy nhất. Cần duy trì **“Xem tất cả”** để người học có thể tự kiểm tra và bổ sung nội dung khi cần.

### Counter-evidence (Dữ kiện đi ngược lại kỳ vọng ban đầu của nhóm)

**Có phát hiện nào bất ngờ làm nhóm “vỡ mộng”?**

AI recommendation có thể giúp tester nhanh chóng bắt đầu ôn tập, nhưng prototype cho thấy AI có thể bỏ sót **điểm ①**.

Điều này đặt ra rủi ro: nếu tester chỉ làm theo AI recommendation mà không kiểm tra lại, tester có thể hoàn thành task nhưng vẫn còn một điểm chưa hiểu chưa được xử lý.

Dữ kiện này đi ngược với giả định đơn giản rằng:

> “AI đề xuất các nội dung cần ôn” đồng nghĩa với “người học đã xử lý đủ các điểm chưa hiểu”.

Do đó, AI recommendation nên được xem là **gợi ý**, không phải danh sách đảm bảo đầy đủ.

## Bóc tách 4 Tầng Tư Duy Sư Phạm (The 4 Cognitive Layers)

### 1. OBSERVED (Quan sát khách quan thuần túy)

- Tester Nguyễn Thị Bảo Trang đã học Cloud 12 và chuẩn bị học Cloud 13.
- Tester nhận notification từ AI.
- Tester mở notification.
- Tester đọc các nội dung AI đề xuất.
- Tester đọc lý do AI đưa ra.
- Tester chọn **“Ôn ngay”**.
- AI không hiển thị **điểm ①**, mặc dù điểm này thuộc các điểm tester chưa hiểu từ Cloud 12.
- Tester có/không mở **“Xem tất cả”**.
- Nếu tester mở “Xem tất cả”, tester có thể xem danh sách đầy đủ và phát hiện điểm ①.
- Nếu tester không mở “Xem tất cả”, tester tiếp tục xử lý các điểm AI đề xuất và không phát hiện điểm ①.
- Nếu phát hiện điểm ①, tester có thể quay lại và xử lý điểm này bổ sung.

### 2. INTERPRETED (Diễn giải nhận định của người làm sản phẩm)

- Tester có xu hướng sử dụng danh sách AI đề xuất làm phạm vi chính để bắt đầu ôn tập.
- Việc đọc lý do cho thấy recommendation được tester xem xét trước khi thực hiện hành động.
- Khi AI bỏ sót điểm ①, có khả năng tester không tự động kiểm tra toàn bộ phạm vi.
- “Xem tất cả” có thể giúp duy trì quyền kiểm soát của người học.
- Rủi ro chính không chỉ là AI bỏ sót mà còn là người học có thể không nhận ra AI bỏ sót.

### 3. DECIDED — NEXT CHANGE (Quyết định hành động cụ thể cho vòng sau)

- Giữ **Option B — AI nhắc ôn, người chọn**.
- Giữ notification và phần giải thích lý do AI recommendation.
- Giữ nút **“Ôn ngay”** làm action chính.
- Giữ **“Xem tất cả”** để người học có thể kiểm tra toàn bộ các điểm chưa hiểu.
- Không để recommendation của AI trở thành con đường duy nhất để người học xác định nội dung cần ôn.
- Kiểm thử thêm xem tester có tự tìm thấy và sử dụng “Xem tất cả” mà không được hướng dẫn hay không.
- Kiểm thử thêm hành vi recovery sau khi tester phát hiện AI bỏ sót một điểm.
- Kiểm thử xem tester có tiếp tục sử dụng recommendation sau khi phát hiện AI bỏ sót hay không.

Nguyên tắc cho vòng tiếp theo:

> **AI đề xuất — người học kiểm tra — người học quyết định.**

### 4. STILL UNPROVEN (Điều vẫn chưa thể chứng minh)

- Tester có thực sự tin recommendation của AI là đầy đủ hay không.
- Tester có thường xuyên kiểm tra “Xem tất cả” trong bối cảnh sử dụng thực tế hay không.
- Người học khác có hành vi giống tester Nguyễn Thị Bảo Trang hay không.
- Người học có chấp nhận việc AI đôi khi bỏ sót nếu có recovery hay không.
- Việc AI recommendation có thực sự giúp người học chuẩn bị tốt hơn cho Cloud 13 hay không.
- Mức độ ảnh hưởng của việc bỏ sót điểm ① đến kết quả học tập.
- “Xem tất cả” có đủ rõ ràng và dễ tìm để trở thành recovery mechanism hiệu quả hay không.
- Sau khi phát hiện AI bỏ sót, mức độ tin tưởng của tester vào AI thay đổi như thế nào.

## Reflection của người điều phối

**Người điều phối:** Phan Thị Khánh Linh

Trong phiên kiểm thử, người điều phối không nên dẫn tester đến điểm ① hoặc trực tiếp yêu cầu tester sử dụng **“Xem tất cả”**.

Không hỏi:

> “Bạn có thấy AI bỏ sót điểm nào không?”

Không nói:

> “Bạn thử bấm Xem tất cả.”

Không gợi ý:

> “Bạn còn một điểm chưa hiểu đấy.”

Thay vào đó, quan sát tester tự thực hiện task:

1. Tester nhìn vào đâu đầu tiên.
2. Tester có đọc lý do AI recommendation không.
3. Tester có hiểu recommendation là gợi ý hay danh sách đầy đủ không.
4. Tester có tự tìm “Xem tất cả” không.
5. Tester có phát hiện điểm ① không.
6. Nếu phát hiện, tester recovery như thế nào.
7. Tester phản ứng như thế nào sau khi nhận ra AI bỏ sót.

### Nguyên tắc ghi nhận evidence

> **Fact trước → Interpretation sau → Decision dựa trên Evidence → Điều chưa chứng minh giữ ở Still Unproven.**

Ví dụ:

**Observed:**

> Tester không mở “Xem tất cả”.

**Không kết luận ngay:**

> Tester tin AI tuyệt đối.

**Nên ghi:**

> Tester sử dụng recommendation của AI làm phạm vi xử lý chính. Việc tester có thực sự tin danh sách này đầy đủ hay không vẫn **Still Unproven**.