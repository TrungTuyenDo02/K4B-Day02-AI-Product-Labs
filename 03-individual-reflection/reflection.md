
# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Đỗ Trung Tuyến
- Mã học viên: 2A202602427
- Nhóm: T113/ Lạc lõng ZONE B
- Candidate problem nhóm chọn: Gọi điện nhiều lần mới đặt được vé xe khách tuyến HN - Tỉnh

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự soi lại trải nghiệm đặt vé xe khách của chính mình, liệt kê 10 problem theo nhiều lăng kính (lặp lại, tốn thời gian, pain từ nhà xe, AI có thể tốt hơn) | Nhóm có nguồn candidate xoay quanh cả phía khách lẫn phía nhà xe, không chỉ dừng ở "đặt vé chậm" chung chung |
| Pitch Problem Card | Pitch Card gọi điện nhiều lần mới đặt được vé xe với số liệu cụ thể: 22 phút/lần, 10-12 phút riêng cho bước gọi lại | Card này được chọn làm candidate chính vì có bottleneck rõ ở đúng 1 bước |
| Challenge bài của bạn khác | Đặt câu hỏi cho chính Card của mình: nếu nhà xe cập nhật bảng ghế sai giờ thì chatbot có gây hại hơn không, và quy mô 1-5 xe có đủ khách để bõ công duy trì bảng ghế không | Buộc phải nhìn lại risk thay vì chỉ khoe điểm mạnh của giải pháp |
| Gom trùng / cluster | Nhóm các problem "thiếu SMS xác nhận" và "đọc lại thông tin mỗi lần" vào chung nhóm "đặt vé/xác nhận chỗ" | Giúp thấy rõ 3 cluster lớn thay vì 10 problem rời rạc |
| Chọn candidate problem | Ủng hộ chọn Card 1 vì workflow rõ nhất và có thể đo bằng phút, không chọn "so sánh giá nhiều nhà xe" vì vượt phạm vi 1 nhà xe | Nhóm hội tụ về đúng 1 problem có thể pilot được trong thời gian ngắn |
| Validation / research | Tự đối chiếu với trải nghiệm của người quen đi xe khách, tìm thêm VeXeRe, Zalo OA, Google Sheets làm tham chiếu | Tránh đề xuất xây nền tảng lớn ngay từ đầu, chọn giải pháp nhẹ vừa quy mô nhà xe nhỏ |
| Workflow nhóm | Vẽ current/future workflow theo từng phút cho cả 3 Card | Nhóm dùng bản vẽ này làm workflow chính thức trong artifact cuối |
| Problem Statement | Viết PS v0 và v1, sửa lại impact từ "chung chung" thành "80-100 phút/tháng cho 1 khách/1 tuyến" | Metric trở nên đo được thay vì cảm tính |
| Rule / Workflow / Agent | Lập luận vì sao chọn Workflow (Zalo OA + bảng ghế) thay vì Agent | Nhóm thống nhất không cần agent tự động hóa toàn bộ khi quy mô còn nhỏ |
| Decision | Đề xuất pilot nhỏ nhất: 1 nhà xe, 1 tuyến, đo trong 2 tuần, có điều kiện rollback nếu >50% vẫn phải gọi điện | Quyết định cuối có phạm vi rõ, không lan man |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất là bảng số liệu ở Problem Card 1 (22 phút, 10-12 phút cho bước gọi lại, 80-100 phút/tháng) - đây là những con số tôi tự ước lượng lại từ chính trải nghiệm gọi điện đặt vé của mình và người thân, không phải số AI tự bịa ra.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ AI gợi ý thêm góc nhìn ngoài trải nghiệm cá nhân | Nhắc thêm góc "pain từ phía nhà xe" (ghi tay dễ nhầm) mà tôi không tự nghĩ ra | Có vài gợi ý quá rộng, không gắn với hành vi thật nào | Chỉ giữ lại ý có thể gắn số liệu quan sát được từ chính tôi |
| Problem Card | Nhờ AI cấu trúc lại problem thành đúng format Card | Giúp tách rõ Actor / Bottleneck / Impact thay vì viết lẫn lộn | AI ban đầu viết impact hơi mơ hồ ("mất nhiều thời gian") | Tôi tự quy ra số phút cụ thể dựa trên ước lượng thật của mình |
| Workflow | Nhờ AI chia nhỏ workflow theo bước và ước lượng thời gian mỗi bước | Nhanh hơn khi cần hình dung current/future state | Thời gian AI ước lượng cho bước "gọi lại vì máy bận" ban đầu hơi thấp so với thực tế | Tôi điều chỉnh lại đúng bằng trải nghiệm gọi điện thật của bản thân |
| Research | Nhờ AI liệt kê công cụ có sẵn (VeXeRe, Zalo OA, Sheets) | Giúp tránh việc tôi tự nghĩ ra giải pháp từ đầu | AI có xu hướng gợi ý nền tảng lớn (kiểu VeXeRe) ngay cho case nhỏ | Tôi hạ quy mô xuống Zalo OA + Sheet cho vừa nhà xe 1-5 xe |
| Problem Statement | Nhờ AI phản biện field còn mơ hồ trong PS | Chỉ ra "impact" và "boundary" ban đầu tôi viết thiếu chi tiết | AI đôi khi viết boundary hơi chung chung, không đủ cụ thể cho case này | Tôi tự viết lại boundary rõ hơn: không tự xác nhận vé khi ghế chưa cập nhật |
| Rule / Workflow / Agent | Nhờ AI liệt kê ưu nhược điểm từng mức | Giúp so sánh có hệ thống thay vì chọn theo cảm tính | AI có xu hướng thiên về đề xuất Agent vì nghe "tự động hóa" hấp dẫn hơn | Tôi giữ vững lựa chọn Workflow vì quy mô nhà xe chưa cần agent |
| Decision | Nhờ AI gợi ý cấu trúc pilot nhỏ nhất + điều kiện rollback | Giúp hình dung rõ exit criteria | Điều kiện rollback AI đề xuất ban đầu hơi lỏng lẻo | Tôi thêm ngưỡng cụ thể ">50% vẫn phải gọi điện trong 2 tuần" để rollback |

> Không có phase nào bỏ qua hoàn toàn AI, nhưng mọi con số cuối cùng đều được tôi đối chiếu lại với trải nghiệm thật của bản thân trước khi chốt.

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Khi nghe top 3 problem của các bạn khác, tôi nhận ra ai chỉ ra được điểm quan trọng nhất: khách không biết trước tình trạng ghế nên phải gọi điện dò, điều đó giúp tôi tự tin hơn rằng Card của mình không phải trải nghiệm cá nhân đơn lẻ mà là pattern chung. Có một lúc nhóm bị solution-first khi ai đó đề xuất làm hẳn một app đặt vé xe và tối ưu đường đi cho xe, nghe rất thực tế nhưng lệch hoàn toàn với quy mô thật của bài toán và quá khó để giải quyết nếu không học sâu. Tôi đặt câu hỏi ngược lại là nhà xe nhỏ có đủ nhân lực duy trì hệ thống lớn như vậy không và đưa ra kết luận nhóm quay về giải pháp nhẹ hơn là Workflow qua Zalo OA. Nhóm chỉ ra cho tôi lỗ hổng về số liệu của mình đưa ra trong problem là chưa tổng quát vì nó chỉ tính cho một khách nhưng tôi lại suy rộng ra cho cả nhà xe. Tôi thấy đúng là mình chưa có số liệu để suy rộng như vậy, nên đã đổi ý và thu hẹp success metric về đúng phạm vi một khách/một tuyến đã validate được. Việc thay đổi góc nhìn này chỉ ra đúng chỗ tôi đang lấy giả định làm bằng chứng. Qua đó tôi học được là một problem có thể khả thi trên mặt ý tưởng nhưng ta cần xem xét đến yếu tố thực hiện được trước khi đi tiếp.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI