# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhóm học tập L3B
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Tổng hợp tiến độ và yêu cầu từ nhiều kênh như chat, file, task board khiến người làm mất thời gian và dễ bỏ sót việc quan trọng.
- Quyết định cuối: Not Yet

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nguyễn Quang Dũng | Khi làm dự án nhóm, tôi muốn tổng hợp tiến độ và yêu cầu từ nhiều nguồn, để biết mình còn thiếu gì và gửi update đúng lúc. | Sinh viên làm project / leader | Gộp dữ liệu từ chat, file, task board | “Ai là người trực tiếp chịu pain nhất?” (nhóm) |
| 2 | Thành viên khác | Khi cần nộp bài lab, tôi muốn biết đúng yêu cầu và tiêu chí chấm, để không mất điểm vì thiếu mục. | Sinh viên | So sánh đề bài với sản phẩm đã làm | “Nếu không cần AI, cách đơn giản nhất là gì?” |
| 3 | Thành viên khác | Khi viết báo cáo tuần, tôi muốn có bản tóm tắt rõ tiến độ, để không mất thời gian đọc lại nguồn. | Leader / PM cá nhân | Tóm tắt dữ liệu rời rạc thành narrative | “Bottleneck thật là viết văn hay là chọn dữ liệu?” |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | Tổng hợp tiến độ project, viết update tuần | Tìm lại thông tin từ nhiều nguồn và tóm tắt thành bản cập nhật ngắn |
| B | Kiểm tra đề bài / tiêu chí chấm | Cần đối chiếu nhiều hướng dẫn với bài làm |
| C | Theo dõi lịch và công việc lặp lại | Mất thời gian nhắn hỏi lại và tra cứu lại lịch trình |

### 2.3. Opportunity Solution Tree rút gọn

```text
OUTCOME: Giảm thời gian trung bình cho việc tìm, tổng hợp và update thông tin trong học tập / dự án
├── Opportunity A: Thông tin nằm rải rác trên nhiều kênh và không có nguồn “chính” |
├── Opportunity B: Người làm mất thời gian đọc lại quá nhiều nguồn để biết tiến độ / nhiệm vụ |
└── Opportunity C: Việc tạo update tuần hoặc báo cáo dễ sai vì phần “dữ liệu gốc” không được chuẩn hóa |
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- “App dashboard tổng hợp tự động”
- “Chatbot AI quản lý project”
- “AI sinh báo cáo tuần tự động”

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Tổng hợp tiến độ project | 5 | 5 | 4 | 5 | 5 | 5 | 4 | 33 |
| Kiểm tra đề bài / tiêu chí chấm | 4 | 4 | 3 | 4 | 4 | 4 | 4 | 27 |
| Viết report tuần | 4 | 4 | 4 | 4 | 4 | 4 | 3 | 27 |

**Candidate được chọn:** Tổng hợp tiến độ project từ nhiều kênh rời rạc.

**Vì sao chọn:** Có actor rõ, quy trình mô tả được, bottleneck cụ thể, impact đo được và vừa sức cho lab. Đây là bài toán có thể giải bằng Rule/Workflow mà không cần Agent.

**Vì sao loại các candidate còn lại:** Candidate “kiểm tra tiêu chí chấm” có thể quá hẹp và dễ trôi thành solution AI kiểm tra bài; candidate “viết report tuần” có overlap với candidate chính và bị ảnh hưởng mạnh bởi biến đổi văn bản.

**Xử lý bất đồng (nếu có):** Nhóm thảo luận và đồng thuận rằng candidate chính là “tổng hợp thông tin” chứ không phải “AI làm báo cáo”.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người dùng thực sự bị chậm vì phải đọc và gộp dữ liệu từ nhiều nguồn | Value | 5 | 3 | Có |
| 2 | Họ sẽ dùng một checklist hoặc template nếu có sẵn | Usability | 4 | 2 | Có |
| 3 | Dữ liệu đầu vào đủ rõ để AI hoặc workflow tổng hợp được | Feasibility | 5 | 3 | Có |
| 4 | Team chấp nhận con người review lại output trước khi gửi | Usability | 4 | 4 | Có |
| 5 | Một workflow đơn giản sẽ tốt hơn một agent | Viability | 3 | 2 | Có |

Giả định nhóm kiểm chứng trong buổi này: “pain có thật, người dùng mất thời gian tìm và gộp dữ liệu; workflow đơn giản hơn agent”.

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot:

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | Sinh viên làm project nhóm |
| Câu nói đáng nhớ nhất (nguyên văn) | “Mỗi tuần mình phải lật lại chat, file và task board, rồi mới biết ai đang làm gì.” |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Mình đã mất 30–45 phút để tổng hợp update cho leader. |
| Hiện đang xử lý bằng cách nào (workaround)? | Ghi chú tay, copy từ chat, dùng sheet riêng. |
| Mất bao lâu, bao lần? | 30–45 phút/tuần, 1–2 lần/tuần. |
| Insight / opportunity rút ra | Thông tin đang bị rải rác; cần one source of truth hoặc template chuẩn hóa. |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn ngắn / quan sát | 3 | Cả 3 người đều nói phải đọc lại nhiều nguồn và mất 20–40 phút/tuần | Có 1 người cho rằng workflow dạng template đã đủ, không cần AI |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Chuyển từ “AI tổng hợp tiến độ” sang “điều kiện cần có source of truth và workflow giảm thời gian đọc, gộp và review”.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Trello / Jira board + template update | https://www.atlassian.com/software/jira | Thu thập task và hiển thị trạng thái | Dễ dùng, rõ kiến thức team | Chưa tự chuyển chat/file thành narrative | Cần chuẩn hóa dữ liệu đầu vào |
| Notion / Google Sheet dashboard | https://www.notion.so/ | Tạo source-of-truth cho tiến độ | Trật tự, dễ cập nhật | Chưa tự tổng hợp bằng AI | Cần review của con người |
| Weekly standup template | Không cần link cố định | Tạo nhịp và checklist cho update | Giảm thông tin thừa | Không tự động đo tiến độ | Rule/simple workflow vẫn hiệu quả |

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

```text
Chat / Zalo / Email
       ↓
Mở file / task board
       ↓
Đọc lại từng source
       ↓
Tổng hợp trạng thái và rủi ro
       ↓
Viết update tuần
       ↓
Gửi cho leader / nhóm
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Thành viên / leader | Chat, file, task board | Danh sách thông tin cần xem | 10 phút | Rải rác |
| 2 | Leader | Báo cáo từ từng nguồn | Tập dữ liệu tổng hợp | 10 phút | Khó đồng nhất |
| 3 | Leader | Dữ liệu thô | Tóm tắt tiến độ | 25 phút | BOTTLENECK |
| 4 | Leader | Tóm tắt | Update chính thức | 10 phút | Dễ thiếu context |
| 5 | Người gửi | Update | Thông tin đến người nhận | 5 phút | Có thể bị lỗi / quên |

**Bottleneck chính:** Bước 3: đọc và tổng hợp dữ liệu từ nhiều nguồn thành một bản update hợp lý.

### 4.2. Quy trình tương lai

```text
Source of truth (template / sheet)
       ↓  Rule
Tạo checklist input
       ↓  AI (optional)
Tóm tắt dữ liệu thành draft update
       ↓  Con người review
Chỉnh sửa, bổ sung rủi ro và xác nhận
       ↓  Con người gửi
Gửi update cuối cùng
```

- Rule: chuẩn hóa đầu vào, lưu một sheet/template duy nhất
- AI: tạo nháp tóm tắt từ dữ liệu đã có
- Con người: review, sửa, quyết định cuối cùng
- Boundary: AI không tự gửi, không tự thêm dữ liệu thiếu nguồn
- Phương án quay về: nếu AI sai, quay về template cũ và viết update thủ công

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 5 | Giữ quy trình đơn giản |
| Tổng thời gian | 45–60 phút/tuần | 15–20 phút/tuần | Giảm nhờ template và AI hỗ trợ |
| Số bước thủ công | 5 | 3 | Giảm thao tác lặp lại |
| Bottleneck chính | Tổng hợp dữ liệu | Review + sửa nháp | Bottleneck di chuyển sang con người |
| Rủi ro mới phát sinh | Bỏ sót nội dung | Chậm / sai do AI | Xử lý bằng HITL |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên làm dự án nhóm / leader nhóm |
| **Quy trình** | Người làm cần thu thập thông tin từ chat, file, task board, tổng hợp thành một bản update tiến độ hằng tuần và gửi cho nhóm hoặc giảng viên |
| **Bottleneck** | Bước tổng hợp dữ liệu từ nhiều nguồn về cùng một câu chuyện thời gian và tiến độ, mất 25–35 phút mỗi lần |
| **Impact** | Mất thời gian, dễ bỏ sót, update thiếu minh chứng và chậm phản hồi |
| **Success Metric** (baseline → target, cách đo) | Baseline hiện tại: 40–50 phút/tuần để tổng hợp; Target: dưới 15 phút/tuần trong 4 tuần pilot; đo bằng tự ghi thời gian mỗi lần tổng hợp |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | AI không được tự động gửi update; không được suy luận dữ liệu không có trong nguồn đầu vào; mọi bản nháp cần người dùng review và sửa trước khi gửi |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- “Metric chưa đủ rõ nếu không nói rõ dữ liệu đầu vào”. Nhóm đồng ý và sửa lại thành “mỗi tuần trong 4 tuần pilot”.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: độ mơ hồ trung bình / độ phức tạp vừa phải.

Vì sao: Có nhiều đầu ra khác nhau nhưng vẫn có cấu trúc cố định của bản update; dữ liệu đầu vào rõ nhưng nhiều nguồn và cần người kiểm tra.

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** | Template chuẩn hóa + checklist + source of truth | Nếu không cần tự động hóa | Ít rủi ro nhưng không tiết kiệm nhiều | Không |
| **Rule** | Tạo template, trích xuất dữ liệu theo chuẩn, cảnh báo thiếu thông tin | Khi dữ liệu đã rõ và có sẵn cấu trúc | Rủi ro thấp | Không đủ |
| **Workflow** | Thu thập → chuẩn hóa → tóm tắt nháp → người review | Khi cần AI ở một vài bước | Rủi ro kiểm soát được | Chọn |
| **Agent** | AI tự tìm dữ liệu và quyết định step tiếp theo | Khi cần tự động hóa toàn chuỗi liên tục | Rủi ro cao, khó kiểm soát | Không |

**Mức chọn:** Workflow

**Vì sao không chọn mức đơn giản hơn:** Rule và No AI chỉ giảm nhàn và hành vi viết lại, nhưng chưa giải được phần “đọc và chọn thông tin” quan trọng nhất; workflow xử lý được phần đó mà vẫn giữ người kiểm tra ở cuối.

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | Tạo bản tóm tắt ngắn về tiến độ, rủi ro, việc cần làm |
| **Judgment** — con người cân nhắc, quyết định gì? | Chọn thông tin nào đáng tin cậy và chỉnh sửa lại giọng văn |
| **Action** — hành động cuối cùng là gì, ai làm? | Leader / sinh viên review và gửi update cuối |
| **Outcome** — đo kết quả bằng gì? | Thời gian tổng hợp, tỷ lệ bỏ sót vấn đề, chất lượng update |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Chat, file, task board; có, nhưng cần chuẩn hóa |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Review thủ công, phản hồi từ người nhận, số lần phải sửa sau khi gửi |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: người dùng muốn AI giúp tóm tắt và chuẩn bị nháp, nhưng không muốn AI tự quyết hoặc tự gửi vì còn cần xem xét rủi ro.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: báo nhầm tệ hơn vì có thể làm sai lệch tình trạng dự án; do đó cần con người review, và nếu AI thiếu dữ liệu thì không tự suy luận.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Sinh viên / leader trong dự án nhóm |
| **Quy trình** | Thu thập, đọc, tổng hợp và gửi update tiến độ từ nhiều nguồn |
| **Bottleneck** | Bước tổng hợp dữ liệu rời rạc thành bản update thật sự đáng tin cậy |
| **Impact** | Mất thời gian, dễ bỏ sót, sai lệch thông tin và chậm phản hồi |
| **Success Metric** (baseline → target, cách đo) | 40–50 phút/tuần → dưới 15 phút/tuần trong 4 tuần pilot; đo bằng thời gian thực tế để hoàn thành một bản update |
| **Boundary** | AI không tự gửi, không tự suy luận khi thiếu dữ liệu, không được bịa nguồn; người sử dụng phải review và sửa |
| **AI intervention point** | Tạo nháp update từ dữ liệu có sẵn, không tự quyết toàn bộ bản update |
| **Mức chọn** | Workflow |
| **Rủi ro & người kiểm tra** | Rủi ro: AI bịa dữ liệu hoặc chọn sai thông tin; người kiểm tra là leader / người gửi update |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Mức can thiệp | Không có | Workflow | Vì đã rõ AI chỉ làm bước nháp, không quyết định toàn bộ |
| Boundary | Chỉ nói AI không được làm gì | Mở rộng thành rõ hành vi cần người kiểm tra | Để chuẩn hóa sự kiểm soát, tránh AI bịa hay gửi nhầm |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đúng nguồn | Tất cả số liệu và ý chính đều có căn cứ từ input | AI thêm thông tin không có trong nguồn |
| 2 | Không làm mất rủi ro | Ghi rõ ít nhất 1 rủi ro, blocker hoặc thiếu sót | Bỏ qua blocker hoặc rủi ro quan trọng |
| 3 | Dễ đọc và có thể sửa | Nháp cập nhật ngắn gọn, cấu trúc rõ, người dùng hiểu ngay | Văn bản rối, nghĩa mơ hồ hoặc quá dài |
| 4 | Dễ review | Người dùng chỉ mất ít thời gian sửa | Người dùng phải viết lại gần như hoàn toàn |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | TB | Có bằng chứng rằng người dùng mất 20–45 phút/tuần; open to workflow |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp | Có template và người dùng review cuối |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | Dữ liệu có sẵn, workflow đơn giản |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Thấp | Không cần hệ thống phức tạp hay ra quyết định tự động |

### 8.2. Kết luận

**Quyết định:** Not Yet

**Lý do:** Bài toán đã có minh chứng về pain, nhưng cần kiểm chứng thêm trong 2–4 tuần với dữ liệu thực, không chỉ giả định. Workflow có vẻ phù hợp nhưng cần xác nhận metric thực tế và khả năng dùng của người dùng. Dù không phải “No-Go”, chúng ta chưa đủ dữ liệu để chọn Go.

**Nếu Go — pilot nhỏ nhất:** Một template + script chuẩn hóa dữ liệu + AI giúp tóm tắt nháp update trong 4 tuần pilot.

**Nếu Not Yet — cần kiểm chứng gì trước:** Đo thời gian thực tế, xác nhận người dùng có review và sửa, kiểm tra tính tin cậy khi dữ liệu không đầy đủ.

**Nếu No-Go — nên làm gì thay AI:** Quay về template, source of truth, checklist và trước khi gửi update phải phục hồi từ dữ liệu gốc.

**Ngưỡng dừng** (nếu sau 4 tuần mà số lần phải sửa lại > 50% bản nháp thì quay về template + dashboard thuần túy):

---

## 9. Hạn chế và hướng tiếp theo

- Chưa có dữ liệu phỏng vấn đủ lớn để khẳng định mức tiết kiệm thực tế.
- Cần rõ hơn cách định nghĩa “update đáng tin cậy” và ai là người review cuối cùng.
- Nếu có thời gian, nên làm thêm một mini survey và đối chiếu với dữ liệu thực.

## 10. Tài liệu tham khảo

- README.md
- docs/01-worksheet.md
- docs/02-deliverable-example.md
- The Mom Test — Rob Fitzpatrick
- Lean UX — Jeff Gothelf

