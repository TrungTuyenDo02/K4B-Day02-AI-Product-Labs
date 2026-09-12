# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Đỗ Trung Tuyến 
- Mã học viên: 2A202602427
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): intern DA
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
    + Check task của các hệ thống đang vận hành
    + Xem phản hồi khách hàng về dashboard, report
    + Học thêm kĩ năng sử dụng AI trong công việc
- Với vai trò một analyst đang nghiên cứu trải nghiệm khách hàng đặt vé xe khách. Đối tượng quan sát là khách hàng đặt vé, những người thường xuyên gọi điện cho nhà xe để đặt chuyến từ Hà Nội về tỉnh (hoặc ngược lại) vào cuối tuần, dịp lễ Tết.
---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| #  | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được                                                           | Ai chịu ảnh hưởng?       | Dấu hiệu thật (số + bằng chứng)                                                                                                           |
| -- | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | Lặp lại                                                                      | Gọi điện nhiều lần mới đặt được vé vì máy bận/không ai nghe                     | Khách hàng               | Theo lịch sử cuộc gọi (call log) 8 tuần gần nhất: 8/10 lần đặt vé phải gọi từ 2 cuộc trở lên, mỗi cuộc cách nhau khoảng 10–15 phút        |
| 2  | Tốn thời gian                                                                | Không biết trước giờ nào còn chỗ, phải gọi hỏi rồi mới chọn được giờ            | Khách hàng               | Trong 10 lần đặt gần nhất, có 3 lần giờ mà KH mong muốn đã hết chỗ, phải hỏi lại giờ khác ngay trong cùng cuộc gọi hoặc gọi thêm 1 cuộc   |
| 3  | Lặp lại                                                                      | Phải đọc lại họ tên, SĐT, điểm đón mỗi lần đặt vì nhà xe không lưu thông tin cũ | Khách hàng, nhà xe       | Trung bình mất 2–3 phút/cuộc gọi chỉ để đọc lại thông tin cá nhân, lặp lại ở toàn bộ 10/10 lần đặt gần nhất                               |
| 4  | Pain từ người khác                                                           | Nhà xe ghi tay thông tin khách vào sổ, dễ nhầm giờ hoặc trùng ghế               | Khách hàng, tài xế/lơ xe | 2/5 chuyến gần nhất chứng kiến có khách khác bị nhầm giờ đón hoặc tranh chỗ ngồi ngay trên xe do ghi tay sai                          |
| 5  | AI có thể tốt hơn                                                            | Không có tin nhắn/SMS xác nhận vé, chỉ xác nhận miệng qua điện thoại            | Khách hàng               | 100% lần đặt vé trong 2 tháng gần nhất không nhận được bất kỳ tin nhắn xác nhận nào, chỉ có lời xác nhận miệng                    |
| 6  | Tốn thời gian                                                                | Phải chủ động gọi lại xác nhận trước giờ khởi hành vì sợ nhà xe quên            | Khách hàng               | 9/10 chuyến gần nhất KH phải tự gọi lại xác nhận trước giờ đi khoảng 1 tiếng, mỗi cuộc gọi thêm 3–5 phút                                      |
| 7  | Pain từ người khác                                                           | Nhà xe báo đổi giờ/đổi điểm đón sát giờ khởi hành                               | Khách hàng               | 2/10 chuyến gần nhất bị báo đổi giờ đón hoặc điểm đón trong vòng dưới 2 tiếng trước giờ chạy do tình hình giao thông tắc nghẽn.                                        |
| 8  | AI có thể tốt hơn                                                            | Không so sánh được giá/giờ giữa các nhà xe khác nhau cùng tuyến                 | Khách hàng               | Để tìm giờ phù hợp nhất, KH phải gọi ít nhất 2 nhà xe khác nhau, mỗi cuộc 5–7 phút, tổng cộng thêm 10–14 phút/lần cần so sánh            |
| 9 | Tốn thời gian                                                                | Dịp lễ Tết, gọi điện đặt vé cực khó vì nhà xe quá tải cuộc gọi                  | Khách hàng               | Ghi nhận dịp Tết dương lịch năm ngoái: phải gọi hơn 10 cuộc trong 1 buổi sáng, mỗi cuộc cách nhau 5–10 phút do máy liên tục báo bận       |



> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Với vai trò một DA, ngoài những sự việc liên quan đến công việc thì bạn có thể có những problem gì, đưa ra những dấu hiệu và số liệu để thấy sự khác biệt của sự việc.
- Ý dùng được: Thường nói về các chủ đề như sức khỏe, cách sử dụng thời gian
- Ý bỏ vì không phải pain thật: phạm vi quan sát cá nhân, ko tổng quát được. Không có số liệu cụ thể.

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem | Lí do chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Gọi điện nhiều lần mới đặt được vé | Workflow rõ, có số liệu cuộc gọi cụ thể, lặp lại hằng tuần | Việc xe khách đặt còn chỗ phụ thuộc nhà xe, khách không tự kiểm tra được |
| 2 | Thiếu xác nhận vé bằng SMS | Pain thật, dễ giải quyết bằng workflow nhỏ | Cần nhà xe hợp tác gửi tin nhắn |
| 3 | Đổi giờ/điểm đón sát giờ | Ảnh hưởng thật, impact rõ | Nguyên nhân nằm ở vận hành nội bộ nhà xe, khó tác động từ phía khách |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

Problem Card 1 - Gọi điện nhiều lần mới đặt được vé
```text
Problem: Mỗi lần cần về quê, khách phải gọi 2-3 cuộc mới đặt được vé vì máy bận, mất khoảng 22 phút cho một lần đặt thành công.

Actor: Khách hàng đi tuyến cố định Hà Nội - Nam Định, đặt vé qua điện thoại với nhà xe nhỏ, số lượng xe không lớn.

Thời điểm / bối cảnh: Chiều thứ Sáu hoặc sáng thứ Bảy, trước thời điểm muốn đặt xe tầm 1 ngày.

Current workflow:

1. Tra số điện thoại nhà xe
2. Gọi lần đầu hỏi còn chỗ
3. Máy bận, gọi lại 1-2 lần
4. Đọc lại thông tin cá nhân: tên, SĐT, điểm đón
5. Nghe xác nhận miệng
6. Gọi lại xác nhận trước giờ đi


Bottleneck: Bước 2-3 phải gọi lại nhiều lần vì không biết trước xe còn chỗ không và tổng đài nhà xe bận, chiếm 10-12 phút.

Impact: Thời gian khoảng 22 phút/lần đặt với tần suất 1 lần/tuần thì sẽ mất khoảng 80 đến 100 phút/tháng chỉ để đặt vé.

Success metric: Giảm thời gian đặt vé từ 22 phút xuống dưới 6 phút; không cần gọi lại vì máy bận.

Non-AI alternative: Niêm yết khung giờ chạy cố định + bảng Sheet ghế trống cập nhật thủ công, nhưng vẫn phải gọi điện và đọc lại thông tin mỗi lần.

AI hypothesis: Chatbot Zalo OA trả lời còn chỗ/hết chỗ dựa trên bảng ghế nhà xe cập nhật, tự gửi xác nhận. Nhà xe vẫn xử lý ngoại lệ.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1**

```text
CURRENT STATE — 22 phút

[1 Tra số: 1'] → [2 Gọi lần đầu: 2'] → [3 Gọi lại vì máy bận: 10']  <--bottleneck
→ [4 Đọc lại thông tin: 3'] → [5 Xác nhận miệng: 1'] → [6 Gọi lại xác nhận: 4']

FUTURE STATE - 6 phút

[1 Nhắn Zalo OA hỏi giờ: 1'] → [2 Bot báo còn/hết chỗ: 1'] → [3 Xác nhận + lưu thông tin: 2']
→ [4 Tự gửi SMS xác nhận: tự động] → [5 Nhà xe xử lý ngoại lệ: 2']  <-- human boundary

Fallback: bot không trả lời được câu hỏi ngoài những câu trả lời được cài đặt form sẵn, nếu có chủ đề khác thì chuyển về gọi điện trực tiếp cho tổng đài.
```

Problem Card 2 - Thiếu xác nhận vé bằng SMS
```text
Problem: Sau khi đặt vé qua điện thoại, khách chỉ nhận xác nhận miệng, không có gì để đối chiếu nếu quên giờ hoặc nhầm chuyến.

Actor: Khách hàng đặt vé qua điện thoại với nhà xe nhỏ, số lượng xe không lớn.

Thời điểm / bối cảnh: Ngay sau khi chốt vé qua điện thoại, kéo dài đến sát giờ khởi hành.

Current workflow:

1. Khách chốt vé qua điện thoại
2. Nhà xe xác nhận miệng, không ghi gì gửi lại cho khách
3. Khách tự ghi nhớ hoặc note lại giờ/điểm đón
4. Gần giờ đi, khách tự gọi lại hỏi để chắc chắn


Bottleneck: Bước 2 không có bước tạo bằng chứng xác nhận (SMS/tin nhắn), đẩy phần rủi ro sang bước 4.

Impact: 100% (10/10) lần đặt gần nhất không có xác nhận bằng văn bản; 9/10 chuyến khách phải chủ động gọi lại xác nhận thêm 3-5 phút.

Success metric: Từ 0% có xác nhận bằng văn bản lên 100%; giảm số lần khách phải chủ động gọi lại xác nhận.

Non-AI alternative: Nhà xe nhắn tay 1 tin Zalo/SMS sau mỗi cuộc gọi chốt vé, nhưng dễ quên khi đông khách.

AI hypothesis: Workflow tự động gửi tin nhắn xác nhận (giờ, điểm đón, giá vé) ngay sau khi nhà xe chốt vé trên hệ thống/bảng ghế.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2**

```text
CURRENT STATE - không có bước xác nhận

[1 Chốt vé qua điện thoại] → [2 Xác nhận miệng]  <--bottleneck
→ [3 Khách tự ghi nhớ] → [4 Gọi lại xác nhận trước giờ đi: +4']

FUTURE STATE - thêm 1 bước tự động

[1 Chốt vé qua điện thoại/Zalo] → [2 Nhà xe bấm xác nhận trên bảng ghế: 10s]
→ [3 Hệ thống tự gửi SMS/Zalo xác nhận: tự động]  <-- human boundary

Fallback: nếu tin nhắn không gửi được, nhà xe xác nhận miệng như quy trình cũ.
```
Problem Card 3 - Đổi giờ/điểm đón sát giờ khởi hành
```text
Problem: Khoảng 30% chuyến, nhà xe báo đổi giờ hoặc điểm đón trong vòng dưới 2 tiếng trước giờ chạy, khiến khách bị động.

Actor: Khách hàng đã đặt vé, chờ đến giờ khởi hành; nhà xe là bên gây ra thay đổi.

Thời điểm / bối cảnh: Trong vòng 1-2 tiếng trước giờ xe chạy, thường do nhà xe gộp chuyến.

Current workflow:

1. Nhà xe quyết định gộp/đổi chuyến nội bộ
2. Nhân viên gọi điện báo từng khách
3. Khách nhận cuộc gọi bất ngờ, phải đổi kế hoạch gấp
4. Khách xác nhận lại điểm đón/giờ mới qua điện thoại


Bottleneck: Bước 1-2 quyết định gộp chuyến không có cảnh báo sớm, thông báo bị động và sát giờ.

Impact: 3/10 chuyến gần nhất (30%) bị đổi giờ/điểm đón sát giờ; khách mất thời gian sắp xếp lại gấp, ảnh hưởng lịch trình cá nhân.

Success metric: Giảm tỉ lệ đổi giờ/điểm đón sát giờ (dưới 2 tiếng trước chạy) từ 30% xuống dưới 10%.

Non-AI alternative: Quy định nội bộ chốt việc gộp chuyến trước tối thiểu 4-6 tiếng, không đổi lịch phút chót, cần kỷ luật vận hành chứ không cần AI.

AI hypothesis: Workflow nhắc nhà xe chốt danh sách chuyến sớm hơn, tự gửi thông báo đổi lịch cho toàn bộ khách cùng lúc nếu buộc phải đổi.

Quick gut:
[x] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3**

```text
CURRENT STATE - bị động

[1 Nhà xe gộp chuyến sát giờ] → [2 Gọi báo từng khách: rải rác]  <--bottleneck
→ [3 Khách bị động đổi kế hoạch] → [4 Xác nhận lại giờ/điểm đón mới]

FUTURE STATE - chủ động hơn

[1 Chốt danh sách chuyến trước 4-6 tiếng: quy định nội bộ]  <-- human boundary
→ [2 Nếu buộc đổi, hệ thống gửi thông báo hàng loạt qua SMS/Zalo: tự động]
→ [3 Khách xác nhận đã nhận thông tin mới: tự động ghi nhận]

Fallback: khách không phản hồi tin nhắn trong 15 phút thì nhân viên gọi điện trực tiếp như cũ.
```



---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card 1 - Gọi điện nhiều lần mới đặt được vé
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow đặt vé qua điện thoại có 6 bước rõ ràng, bottleneck nằm đúng 1 bước (gọi lại 2-3 lần vì máy bận), có số đo cụ thể là 22 phút/lần đặt và 10-12 phút riêng cho bước gọi lại. Impact tính được thành 80-100 phút/tháng cho một khách đi 1 lần/tuần, và có thể giảm xuống dưới 6 phút bằng một workflow nhẹ (Zalo OA + bảng ghế), không cần hệ thống lớn.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Nếu nhà xe không cập nhật bảng ghế đúng giờ mỗi ngày thì chatbot có đang trả lời sai và gây mất niềm tin của khách hơn là không có chatbot không?
2. Với nhà xe cỡ nhỏ, liệu lượng khách hỏi qua Zalo OA có đủ nhiều để nhà xe duy trì bảng ghế, hay vẫn nhanh hơn nếu cứ nghe điện thoại?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Impact 80-100 phút/tháng chỉ tính cho 1 khách hay nhiều khác, chưa chứng minh được vấn đề này đủ lớn ở quy mô nhiều khách của nhà xe để đáng làm workflow riêng.
- Tôi sửa gì: Thu hẹp success metric về đúng phạm vi 1 khách/1 tuyến đã validate, không suy rộng ra toàn bộ khách của nhà xe khi chưa có số liệu thật.

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
