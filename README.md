# Track1_Day18_2A202602360_PhanThiKhanhLinh

Day 18 — Three prototypes, one next change

| Tệp                                                          | Nội dung                                                                       |
| ------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| [three-option-design-sheet.md](three-option-design-sheet.md) | Hypothesis Problem, Option A/B/C, Comparison Contract, Human–AI Decision Table |
| [prototype-link.md](prototype-link.md)                       | Link prototype A/B/C chung của nhóm và cách dùng khi test                      |
| [prototype/index.html](prototype/index.html)                 | Mã nguồn prototype                                                             |
| [prototype-feedback-note.md](prototype-feedback-note.md)     | Feedback Note của phiên do tôi facilitate                                      |
| [group-feedback-synthesis.md](group-feedback-synthesis.md)   | Tổng hợp feedback của cả nhóm                                                  |
| [ai-support-log.md](ai-support-log.md)                       | Nhật ký sử dụng AI                                                             |

---

## 1. Thông tin cá nhân và nhóm

- **MHV:** 2A202602360
- **Họ tên:** Phan Thị Khánh Linh 
- **Tên nhóm:** NaCl
- **Case:** B — AI Notes: Personal Learning Notes

| Họ tên                | MHV         |
| --------------------- | ----------- |
| Nguyễn Thị Hồng Nhung | 2A202602557 |
| Phan Thị Khánh Linh   | 2A202602360 |
| Trần Thị Thu Trang    | 2A202602581 |
| Hồ Hoàng Phương Anh   | 2A202602460 |

## 2. Hypothesis Problem

> **Người học** khi học nội dung mới, nhiều khái niệm liên quan nhau, có ghi lại những phần chưa hiểu hoặc muốn xem lại, **nhưng ghi chép rời rạc, không có cấu trúc** nên sau đó **khó tìm lại và thường không quay lại xử lý** → đến phần học sau thì đã quên nội dung trước.

- **Nối với Day 17:** Day 17 ưu tiên điều tra Pain A (khó ghi nhận). Bốn Practice Notes cho thấy cả bốn người đều tự ghi nhận được, trong khi N2 và N4 có hậu quả rõ ở khâu sau khi ghi (khó tìm lại, quên xem lại) → nhóm chuyển trọng tâm sang Pain B, giữ nguyên case, actor, situation và JTBD.
- **Chưa biết:** nguyên nhân không quay lại (ghi lộn xộn, thiếu thời gian/động lực, hay không có gì nhắc); tần suất và công sức; tác động thật đến kết quả học.
- Chi tiết evidence: [three-option-design-sheet.md § 1](three-option-design-sheet.md#1-hypothesis-problem).

## 3. Three Solution Options

**Prototype:** https://claude.ai/artifact/LPaBWsUty1SXrkc6y3J88Y (mở trực tiếp từng option bằng `#a`, `#b`, `#c`)

|       | Option                               | Người–AI chia việc                                                                                        | Nguyên nhân đặt cược                    |
| ----- | ------------------------------------ | --------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| **A** | AI sắp xếp, người duyệt              | AI gom ghi chú rời thành danh sách điểm chưa hiểu có nguồn; người sửa và xác nhận trước khi lưu           | Ghi chép lộn xộn, không tìm lại được    |
| **B** | AI nhắc ôn, người chọn               | Trước buổi học sau, AI gợi ý điểm cần ôn kèm lý do và mức liên quan; người chọn ôn ngay / để sau / bỏ qua | Quên, không có gì nhắc quay lại         |
| **C** | Người tự đánh dấu, AI hỗ trợ khi hỏi | Người tự viết checklist; AI chỉ giải thích khi được hỏi, có trích slide; người tự đánh dấu đã hiểu        | Quay lại nhưng không biết xử lý thế nào |

Cả ba dùng chung user, situation, task, nội dung mẫu và desired outcome; chỉ khác cơ chế. Mỗi option có một tình huống AI sai cài sẵn để quan sát khả năng phát hiện và phục hồi.

## 4. Đóng góp của tôi trong nhóm

- **Option phụ trách chính:** Option B.
- **Shared context:** Tôi giúp nhóm xây dựng bối cảnh cho Option B, tập trung vào việc người học nhận được lời nhắc ôn tập trước buổi học sau, dựa trên các điểm chưa hiểu đã lưu và mức độ liên quan với nội dung mới. Mục tiêu là nhắc lại đúng thời điểm và giảm việc quên ôn.
- **Human–AI decisions:** Tôi xác định người học có quyền chọn giữa ôn ngay, ôn tối nay hoặc bỏ qua, đồng thời có thể xem lại tất cả các điểm chưa hiểu nếu cần. AI đóng vai trò gợi ý theo lý do và mức độ liên quan, nhưng không thay thế quyết định của người học. Người học vẫn có thể bỏ qua, chờ lại hoặc thêm điểm mới nếu cần.
- **Phiên test tôi facilitate:** Tôi facilitate phiên test với bạn Phan Thị Khánh Linh (2A202602360). Tester trải nghiệm cả ba option và tập trung vào cách AI nhắc ôn và lựa chọn nội dung cần xem lại.
- **Tổng hợp feedback tôi tham gia:** Tester nhận thấy Option B tiết kiệm thời gian vì AI gợi ý đúng điểm cần ôn, nhưng cũng có thể bỏ sót một số điểm chưa hiểu nếu chỉ dựa trên recommendation. Vì vậy, cần có nút “Xem tất cả điểm chưa hiểu” để người học kiểm tra lại toàn bộ danh sách.
- **Phần AI hỗ trợ và phần tôi thực hiện:** AI hỗ trợ tôi xây dựng prototype và cấu trúc phản hồi mẫu; tôi phụ trách thiết kế luồng nhắc nhở, mức độ liên quan và cách diễn giải cho người học trước khi chọn hành động.

## 5. Prototype Feedback

- **Observation từ phiên tôi facilitate:** Tester xem cả ba option theo thứ tự A, B, C và dừng lại dùng Option C đầu tiên vì thấy dễ hiểu, dễ sử dụng. Ở Option B, tester do dự và phải đọc nhiều mới biết cần ôn gì. Tester chọn Option C, chấp nhận tự ghi 3 note; khi chưa hài lòng với câu trả lời, tester đối chiếu slide buổi 12 rồi hỏi AI lần nữa. Chi tiết tại [prototype-feedback-note.md](prototype-feedback-note.md).
- **Tổng hợp feedback của nhóm:** xem [group-feedback-synthesis.md](group-feedback-synthesis.md).
  - **Pattern:** Option C được chọn trong 2/3 phiên; người thử chấp nhận tự ghi nội dung để đổi lấy trải nghiệm dễ dùng. Các phiên cũng cho thấy ma sát khi phải hiểu nhiều lựa chọn hoặc tìm nội dung cần ôn.
  - **Khác biệt:** Tester phiên Linh chọn Option B để giảm công sức tự rà soát; tuy nhiên, AI bỏ sót một điểm chưa hiểu. Các tester cũng dùng cách khác nhau để lấy lại quyền kiểm soát: đối chiếu slide, xem toàn bộ danh sách hoặc quay lại thao tác.
- **Next Change đề xuất:** Làm nút **“Xem tất cả điểm chưa hiểu”** dễ nhận ra bên cạnh recommendation của Option B, đồng thời nói rõ gợi ý của AI có thể chưa đầy đủ. Đây là đề xuất rút ra từ feedback, chưa khẳng định là quyết định cuối cùng nhóm đã thống nhất.
- **Still Unproven:** Chưa biết người học có tự kiểm tra danh sách đầy đủ, phát hiện và xử lý phần AI bỏ sót hay không; cũng chưa chứng minh lời nhắc giúp họ thực sự quay lại ôn tập hoặc cải thiện khả năng ghi nhớ/kết quả học.

## 6. AI Support Log

Chi tiết: [ai-support-log.md](ai-support-log.md)

- **Công cụ và AI đã giúp gì:** Nhóm dùng Lovable để xây dựng prototype Option A/C và Claude Artifacts cho Option B. AI hỗ trợ làm rõ đề bài, tổng hợp evidence, đề xuất các option và bảng quyết định Human–AI, tạo mã prototype, nội dung/dữ liệu mẫu và canned output, cũng như khung tài liệu.
- **AI sai hoặc chưa phù hợp:** Giao diện AI tạo ra có lúc chưa đúng kỳ vọng về luồng và cách trình bày, cần mô tả lại cụ thể hơn. Các prototype dùng canned output, không kết nối AI thật nên không thể dùng để kết luận về độ chính xác của AI thật. Ngoài điểm chưa phù hợp về giao diện, chưa có lỗi cụ thể nào khác được ghi nhận trong log.
- **Tôi tự rà soát/chỉnh sửa:** Tôi phụ trách thiết kế luồng và nội dung Option C; khi giao diện chưa phù hợp, tôi bổ sung mô tả chi tiết để AI chỉnh sửa. Tôi cũng rà soát nội dung, cách chia quyền quyết định giữa người học và AI, và đối chiếu feedback tester với nguồn slide buổi 12. Chi tiết tại [ai-support-log.md](ai-support-log.md).
