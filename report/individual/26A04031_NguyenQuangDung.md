# Báo cáo cá nhân — 26A04031_NguyenQuangDung

## 1. Thông tin học viên

- Họ tên: Nguyễn Quang Dũng
- MSSV: 26A04031
- Email trường (không bắt buộc, repo có thể để public): quangdung.26a04031@... (ghi theo email trường nếu có)
- Tên nhóm: Nhóm học tập L3B
- Link repo nhóm: https://github.com/NguyenQuangDunghe161764/K5-L3-Day02-NguyenQuangDung-26A04031-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi bắt đầu một tuần mới, tôi muốn biết việc nào cần làm trước, để không bỏ sót deadline và không phải hỏi lại từng người. | Sinh viên, team project, người quản lý task | Mỗi tuần mất 20–30 phút để rà soát LMS, Discord, Zalo, email; lặp lại 2–3 lần/tuần; nhiều bạn cùng lớp cũng hỏi lại lịch công việc. |
| 2 | Tốn thời gian | Khi cần nộp bài lab, tôi muốn biết đúng yêu cầu, tiêu chí chấm và file nộp cần gì, để không mất điểm vì thiếu mục. | Sinh viên | Mỗi bài lab mất 25–40 phút kiểm tra lại yêu cầu; khoảng 1–2 bài/tuần; 1 lần sai format có thể mất 1 điểm hoặc nhiều hơn. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi làm dự án nhóm, tôi muốn tổng hợp nội dung từ chat, file drive và task board vào một nơi, để không phải đọc lại 4 nguồn để hiểu tiến độ. | Thành viên nhóm, PM, leader | Mỗi dự án mất 30–50 phút/tuần để đọc lại message, file và task; 3–4 người cùng gặp tình trạng này; có nhiều lần phải hỏi “em đang làm gì?” |
| 4 | Pain từ người khác | Khi bạn bè hỏi tôi “bài này cần gì?”, tôi muốn trả lời nhanh dựa trên yêu cầu gốc, để không phải tìm lại link và tiêu chí từng lần. | Sinh viên, team lead | Mỗi ngày có 2–3 câu hỏi lặp lại; mất 5–10 phút mỗi lần; dễ sai vì thông tin đang rải rác. |
| 5 | Lặp lại | Khi cần tổng hợp báo cáo tiến độ, tôi muốn có một bản tóm tắt rõ câu chuyện chính, để không mất thời gian viết lại từ đầu mỗi tuần. | Sinh viên làm project, lập trình viên, PM | Viết báo cáo 1 lần/tuần mất 45–60 phút, trong đó 20–30 phút dành cho đọc và sắp xếp dữ liệu từ chat và file. |
| 6 | Tốn thời gian | Khi kiểm tra tiến độ dự án, tôi muốn biết phần nào đã xong, chậm, và cần hỗ trợ gì, để quyết định nhắc việc đúng lúc. | Leader, team member | Mỗi lần review team mất 15–20 phút, tần suất 2 lần/tuần; nhiều khi phải nhắn lại từng người để xác nhận status. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi cần ôn thi hoặc làm bài tập, tôi muốn lấy kiến thức đã học từ nhiều nguồn thành một cấu trúc dễ học, để không đọc tràn lan mà bỏ sót trọng tâm. | Sinh viên | Mỗi buổi học hoặc kỳ thi mất 1–2 tiếng tìm nguồn, gộp ý và tóm tắt; có ít nhất 3–4 nguồn khác nhau: slide, ghi chép, tài liệu, bài cũ. |
| 8 | Pain từ người khác | Khi người khác hỏi lịch họp hoặc công việc, tôi muốn có một đầu mối rõ ràng, để không lặp lại các giải thích cùng lúc. | Team member, leader | Mỗi tuần có 3–5 câu hỏi lặp lại về lịch và trách nhiệm; mỗi lần mất 5 phút; gây lag trong nhắn tin và chờ phản hồi. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI gợi ý thêm các vấn đề về “sắp xếp lịch học” và “tìm lại thông tin cũ”. Tôi giữ lại ý “tổng hợp tiến độ nhóm” vì nó có actor rõ, quy trình tương đối rõ và dễ đo được bằng thời gian/tuần. Ý “sắp xếp lịch học” bị bỏ vì quá rộng, khó đo bottleneck cụ thể, và dễ trôi thành giải pháp quản lý lịch chung thay vì một bài toán rõ ràng. 

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp yêu cầu và tiến độ từ nhiều kênh | Actor rõ, quy trình có thật, cần đọc nhiều nguồn, bottleneck dễ thấy ở “tổng hợp từ nhiều đường chat/file” | Cần xác định rõ ranh giới: ai là người chủ động, thành quả cần là gì |
| 2 | Tìm lại thông tin và tiêu chí bài nộp từ LMS/drive | Có dấu hiệu lặp lại rõ, dễ đo thời gian và tần suất, dễ so sánh Rule/Workflow | Có thể trở thành bài toán “sắp xếp thông tin”, không phải “đối phó với thiếu tiêu chí” |
| 3 | Viết báo cáo tiến độ tuần theo dữ liệu rời rạc | Có bottleneck rõ ở bước đọc/tổng hợp, nhưng may cần dữ liệu từ nhiều người | Có thể cần AI/Rule nhiều hơn vì quá nhiều tùy biến văn bản |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm dự án nhóm, tôi muốn tổng hợp tiến độ từ chat, file và task board trong một chỗ, để biết mình còn thiếu gì và gửi update đúng lúc. |
| Actor | Sinh viên làm dự án nhóm / leader nhóm |
| Thời điểm / bối cảnh | Cuối mỗi tuần, chuẩn bị update tiến độ hoặc khi cần nắm nhanh tình hình dự án |
| Quy trình hiện tại (3–7 bước) | 1) Lấy dữ liệu từ Zalo/Discord/chat group; 2) Mở file Excel/Google Sheet; 3) Mở các ghi chú hoặc task board; 4) Đọc lại nội dung từng phần; 5) Viết summary tuần; 6) Gửi cho nhóm hoặc giảng viên |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4: đọc và tổng hợp dữ liệu từ nhiều nguồn; mất khoảng 25–35 phút mỗi lần |
| Impact (nếu không giải thì sao) | Mất thời gian, dễ sai, bỏ sót việc quan trọng, team không biết ai đang làm gì và deadline nào còn chậm |
| Success metric (baseline → target) | 40–50 phút/tuần → dưới 15 phút/tuần, giảm 60–70% thời gian tổng hợp |
| Phương án không dùng AI | Dùng một template update tuần, checklist, một sheet “source of truth”, phân công người tổng hợp | 
| Giả thuyết về AI (nếu có) | Công việc có thể làm trên workflow: gộp nguồn, tóm tắt nội dung, nhắn cảnh báo thiếu thông tin | 
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
Lấy thông tin từ chat: 10'
→ Kiểm tra file/Sheet: 10'
→ Đọc task và ghi chú: 15'
→ Tổng hợp + suy ra tình trạng: 25' ← BOTTLENECK
→ Viết update nhóm: 10'
→ Gửi cho nhóm / giảng viên: 5'
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần nộp bài lab, tôi muốn biết đúng yêu cầu, tiêu chí chấm và file cần nộp, để không mất điểm vì thiếu mục hoặc sai format. |
| Actor | Sinh viên làm bài lab |
| Thời điểm / bối cảnh | Trước khi nộp bài hoặc khi bắt đầu làm bài mới |
| Quy trình hiện tại (3–7 bước) | 1) Mở LMS và file hướng dẫn; 2) Đọc từng mục yêu cầu; 3) So sánh với file đã làm; 4) Tìm thêm tài liệu hoặc các câu hỏi cũ; 5) Kiểm tra format trước khi nộp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: đối chiếu yêu cầu với bài đã làm; mất khoảng 20–30 phút |
| Impact (nếu không giải thì sao) | Dễ quên mục, sai format, mất điểm, mất thời gian nộp lại |
| Success metric (baseline → target) | 30 phút/lần kiểm tra trước nộp → dưới 10 phút/lần |
| Phương án không dùng AI | Checklist mục bắt buộc, template kiểm tra “nộp bài” và 1 sheet lưu danh mục ý chính |
| Giả thuyết về AI (nếu có) | Có thể dùng AI để đối chiếu template với bài làm, nhưng nên cảnh báo đầu ra vì còn dễ bịa |
| Cảm nhận nhanh | Rule / Workflow |

Quy trình nháp hiện tại:

```text
Mở đề bài và yêu cầu: 5'
→ Đọc kỹ từng mục: 10'
→ So sánh với bài đang làm: 15' ← BOTTLENECK
→ Kiểm tra file nộp và format: 10'
→ Nộp bài: 2'
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi viết báo cáo tiến độ hằng tuần, tôi muốn có bản tóm tắt rõ tiến độ và rủi ro, để không mất thời gian sắp xếp lại dữ liệu từ nhiều nguồn. |
| Actor | Sinh viên làm project, team lead |
| Thời điểm / bối cảnh | Mỗi tuần hoặc trước khi gửi update cho giảng viên / nhóm |
| Quy trình hiện tại (3–7 bước) | 1) Thu thập chat, note, task; 2) Đọc từng item; 3) Chọn dữ liệu quan trọng; 4) Viết narrative; 5) Kiểm tra lại logic; 6) Gửi |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3–4: chọn nội dung đúng và viết narrative; mất khoảng 35–50 phút |
| Impact (nếu không giải thì sao) | Bị lặp lại công việc, nội dung update thiếu trọng tâm, dễ sai lệch hoặc thiếu minh chứng |
| Success metric (baseline → target) | 45–60 phút/tuần → dưới 20 phút/tuần |
| Phương án không dùng AI | Template báo cáo tuần + checklist “đã có bằng chứng chưa” |
| Giả thuyết về AI (nếu có) | AI có thể tạo nháp từ dữ liệu có sẵn, nhưng con người phải review và sửa |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
Thu thập dữ liệu: 10'
→ Đọc lại source: 15'
→ Chọn ý chính và rủi ro: 15'
→ Viết báo cáo: 25' ← BOTTLENECK
→ Review / sửa: 10'
→ Gửi: 2'
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Câu chuyện rõ, có actor cụ thể, bottleneck rõ, dữ liệu đầu vào có thật và dạng quy trình dễ mô hình hóa.
- Câu hỏi muốn nhóm phản biện: “Bottleneck thật sự là giai đoạn tổng hợp dữ liệu, hay phần người làm task đang thiếu source of truth từ đầu?”

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Candidate chưa xác định rõ ai là người trực tiếp chịu pain nhất (leader hay thành viên). | Có | Chỉnh actor thành “sinh viên làm dự án nhóm / leader” và nêu rõ bối cảnh trước khi update tuần. |
| Metric có thể quá rộng nếu không chỉ rõ “mỗi tuần” và “trong dự án nào”. | Có | Chuyển thành baseline và target rõ theo lần tổng hợp 1 tuần, sau đó mới tổng quát hóa. |
| Quy trình hiện tại chưa cho thấy source of truth nào thiếu. | Có | Thêm bước “source of truth” và nhấn mạnh bottleneck nằm ở việc gộp dữ liệu từ nhiều kênh rời rạc. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày Card #1 về tổng hợp tiến độ team và giải thích bottleneck rõ từ “tổng hợp” đến “ghi update”. | Giúp nhóm thấy rõ pain nằm ở nguồn thông tin rời rạc và một bottleneck dễ đo. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: “Nếu không cần AI, cách đơn giản nhất để giảm nửa thời gian là gì?” | Tạo động lực cho nhóm nhìn lại quy trình trước khi nghĩ giải pháp. |
| Nhận phản biện | Câu hỏi tôi nhận được: “Ai là người chính chịu pain, leader hay thành viên?” | Tôi chỉnh lại actor và bổ sung rõ bối cảnh. |
| Gom cluster / cây OST | Gom các problem liên quan đến “tìm lại thông tin” và “ghi update tuần” thành cluster chung. | Giúp nhóm nhìn thấy một outcome: giảm thời gian tìm/tổng hợp thông tin và update. |
| Chọn candidate problem | Chọn candidate “Tổng hợp tiến độ nhóm từ nhiều kênh khác nhau”, vì nó phổ biến, dễ chứng minh và vừa sức lab. | Đây là candidate nhóm ưu tiên. |
| Kiểm chứng / research | Tự suy nghĩ và đối chiếu với các case xử lý dữ liệu từ chat/file; xem xét có template, dashboard, checklist hay không. | Giảm nguy cơ chọn bài toán quá “đi làm AI” mà bỏ quên quy trình hiện tại. |
| Quy trình nhóm | Đóng góp vào việc mô tả quy trình trước/sau, với rõ boundary và nơi AI vào. | Quy trình dễ hiểu hơn, không nhầm lẫn giữa “AI làm hẳn” và “AI hỗ trợ”. |
| Problem Statement | Rà soát lại actor, bottleneck, metric và boundary để tránh viết quá rộng hoặc lẫn giải pháp. | Bài toán rõ hơn và dễ kiểm chứng hơn. |
| Mức can thiệp AI | Đề xuất Workflow, không phải Agent, vì có dữ liệu đầu vào rõ và vẫn cần con người kiểm tra. | Tạo quyết định hợp lý, không phóng đại AI. |
| Quyết định | Đề xuất “Go / Not Yet” tùy ngưỡng pilot khi bài toán đã check được liệu dữ liệu đủ và người dùng chấp nhận công việc khu vực. | Quyết định có logic và tiêu chí dừng. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Gợi ý các vấn đề tương tự ở trường học và thực tế nhóm. | Giúp mở rộng danh sách và sắp xếp theo 4 lăng kính. | AI thích đưa ra ý quá rộng như “trợ lý AI quản lý học tập”, thay vì bài toán thực tế. | Tôi bỏ các ý quá rộng và giữ lại những câu có actor, tình huống và impact rõ. |
| CP2 Problem Card | Đặt AI làm “PM hoài nghi” phản biện card. | Giúp phát hiện chỗ chưa rõ actor và metric. | AI có xu hướng đánh giá bằng cảm tính và không thấy sự khác biệt giữa “bottleneck” và “vấn đề tổng quát”. | Tôi sửa lại actor, bottleneck và success metric theo định nghĩa của lab. |
| CP4 Research | Tìm các pattern và công cụ tương tự khi giải quyết tổng hợp thông tin và update tiến độ. | Giúp rà soát “có tool nào đã làm sẵn chưa”. | AI đưa link hoặc mô tả chưa chắc chắn; có một số case không đúng nghĩa với bài toán. | Tôi chỉ giữ các case có link hợp lý và xác định rõ phần nào đã có sẵn, phần nào còn trống. |
| CP5 Quy trình | Nhờ AI chuyển quy trình thành sơ đồ và câu chữ rõ hơn. | Hữu ích để mô tả đầu vào/đầu ra và các bước. | AI gộp nhiều bước vào một bước, làm mờ bottleneck thật. | Tôi tự phân tách bước, đánh dấu bottleneck và boundary rõ hơn. |
| CP5–6 Problem Statement | AI góp ý lỗ hổng trong problem statement v0. | Hữu ích khi nhắc tôi kiểm tra metric và boundary. | AI dễ viết lại toàn bộ thay vì chỉ định câu hỏi. | Tôi không dùng AI “ viết thay”, mà chỉ hỏi lỗ hổng để tự sửa. |
| CP6 Mức can thiệp / quyết định | So sánh No AI / Rule / Workflow / Agent. | Giúp nhìn rõ workflow là mức phù hợp nhất. | AI có thể ép quá sớm vào “Agent” như giải pháp mặc định. | Tôi quyết định giữ ở Workflow vì có dữ liệu rõ, yêu cầu cần con người review và không cần tự quyết bước tiếp theo. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe top 3 problems của các bạn, tôi thấy rõ là một bài toán “đúng” không phải chỉ là cảm giác “mất thời gian”, mà là khi actor, quy trình và metric được mô tả cụ thể. Có những đề xuất rất gần với trải nghiệm của mình như “tìm lại thông tin cũ”, “đọc quá nhiều nguồn”, và “viết update tuần”. Tôi học được cách đánh giá một vấn đề theo giá trị thực tế, chứ không chỉ theo độ “nghe có vẻ quan trọng”. Một điểm đáng nhớ là nhiều problem đều có chung một pattern: thông tin rải rác, cần đọc nhiều, và người làm phải tổng hợp bằng tay. Nhờ đó, tôi thấy rõ hơn khi nào một problem đủ “đẹp” để đi tiếp: có người bị ảnh hưởng, có bottleneck cụ thể, có số liệu hoặc thời gian đo được, và có thể tách thành Rule/Workflow nếu cần AI.

**6.2. Nhóm có lúc nào bị “solution-first” (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, nhóm đã có lúc bắt đầu nghĩ ngay đến AI hoặc dashboard, thay vì nói rõ vấn đề. Ví dụ ban đầu, khi nghe “tổng hợp tiến độ team”, có người nhảy thẳng tới ý tưởng “xây app tự động tổng hợp”. Lúc đó, cả nhóm nhận ra rằng đây vẫn là solution-first, vì chúng ta chưa nói rõ actor, bottleneck, và rủi ro của quy trình hiện tại. Chúng tôi đã xử lý bằng cách quay lại Job Story, xác định lại actor, vẽ quy trình hiện tại và chỉ đánh dấu step nào là bottleneck. Khi đã có quy trình rõ, mới quay lại xem AI có nên chen vào đâu, và điều đó giúp bài toán đi đúng hướng hơn.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có. Ban đầu tôi muốn chọn problem “kiểm tra tiêu chí nộp bài” vì nó có dấu hiệu thực tế và dễ đo. Nhưng sau khi bị phản biện, tôi nhận ra bài toán này dễ trôi thành “AI kiểm tra bài nộp” quá sớm, không giữ được phần bottleneck thật, vì người dùng có thể chỉ mất vài phút và quy trình không rõ. Tôi đã đổi sang problem “tổng hợp tiến độ từ nhiều kênh” vì đó là một pain rõ hơn, có nhiều nguồn thông tin, bottleneck dễ thấy, và dễ soi ra boundary. Đây là lần tôi thay đổi lựa chọn vì phản biện giúp tôi nhìn ra rằng metric và quy trình là quan trọng hơn một lời cảm nhận “mất thời gian”.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Có. Tôi bất ngờ nhất là nhiều người không thực sự nói “mình cần một AI”, mà lại nói “mình phải đọc lại thông tin từ nhiều nơi mỗi tuần”. Đó là điều đáng chú ý vì nó cho thấy vấn đề thật là việc tìm và tóm tắt thông tin, không phải “nếu có AI sẽ giúp”. Tôi cũng ngạc nhiên vì người khác có thể nói “sao mình không tự làm từ trước?” nhưng thực tế họ đang dùng nhiều workaround: copy file, note lại, hoặc nhắn hỏi lại. Điều đó cho thấy pain có thật, nhưng nó không nằm ở một công cụ duy nhất; nó nằm ở quy trình tổng hợp dữ liệu và sự thiếu source of truth.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó nhất là không lẫn lộn problem với solution. Một lúc nào đó, tôi dễ viết “cần một AI tổng hợp cập nhật tiến độ” thay vì viết “thông tin bị rải rác giữa chat, file và sheet, khiến team mất thời gian tổng hợp”. Vì vậy, viết Problem Statement đòi hỏi tôi phải dừng ở mức mô tả lòng đau và bottleneck, không tự suy ra giải pháp. Việc còn khó nữa là success metric phải đo được: “rút ngắn thời gian” không đủ nếu không có baseline, target và cách đo. Tôi đã phải sửa nhiều lần để chuẩn hóa metric và boundary.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ dùng nhiều hơn thời gian ở giai đoạn CP3 và CP4 để kiểm tra actor thật sự. Tôi sẽ hỏi rõ hơn: “Ai chịu pain nhất, ai thường làm bottleneck, và ai là người sau đó dùng danh sách tổng hợp đó?”. Ngoài ra, tôi sẽ phản biện nhóm mạnh hơn ở điểm “AI đang đẩy sớm” và “một problem có thể là solution giấu mặt”. Tôi muốn hỏi rõ hơn: “Nếu không dùng AI, đổi cách làm nào đã giảm 50% thời gian chưa?” để buộc nhóm tập trung vào quy trình và metric thực tế, không chỉ là ý tưởng công nghệ.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Bài toán của nhóm là thông tin rời rạc khiến người làm mất thời gian tổng hợp tiến độ. Khi chúng ta vẽ quy trình hiện tại, bottleneck nằm ở bước đọc và gộp dữ liệu từ nhiều nguồn thành một update. Chúng ta đo thành công bằng thời gian trung bình mỗi tuần để hoàn thành bước này, với baseline hiện tại và target rõ ràng. Sau đó, chúng ta đặt boundary: AI không được tự động gửi thông tin, không được giả bộ có dữ liệu không có, và luôn cần người dùng kiểm tra lại. Vì bài toán có dữ liệu đầu vào rõ, nhưng cần con người quyết định và xác nhận, mức can thiệp phù hợp là Workflow, không phải Agent. Kết luận là nếu workflow giúp giảm thời gian đáng kể và không làm tăng rủi ro lớn, thì đi tiếp với pilot nhỏ; nếu metric không cải thiện hoặc người dùng không chấp nhận, quay lại quy trình và template hiện có.

---

## 7. Tài liệu tham khảo

- README — hướng dẫn lab Discovery & Problem Framing
- docs/01-worksheet.md — template và phương pháp CP1–CP7
- docs/02-deliverable-example.md — ví dụ nhóm, tham khảo cách định hình problem
- The Mom Test — Rob Fitzpatrick
- Lean UX — Jeff Gothelf
- Google PAIR — Google

