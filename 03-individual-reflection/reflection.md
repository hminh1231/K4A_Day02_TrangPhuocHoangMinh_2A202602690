# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Trang Phước Hoàng Minh
- Mã học viên: 2A202602690
- Nhóm: 5 người trên repo Nguyễn Lê Phúc Thắng (`pthang228/K4A_Day02_NguyenLePhucThang_2A202602638`) — Nguyễn Lê Phúc Thắng (trưởng nhóm), Lê Gia Bảo, Trang Phước Hoàng Minh, Bùi Trọng Trình, Vũ Minh Hiếu
- Candidate problem nhóm chọn: Cuối tháng, ERP Engineer mất khoảng 2.5–3.5 giờ để đối chiếu weekly report và GitHub commits rồi viết lại thành báo cáo cho quản lý không dùng GitHub.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự liệt kê 10 pain từ việc ERP Engineer tại Lug (họp thứ Hai, demo theo task, giấy ra cổng, monthly report, chờ duyệt, spec rải file, dịch GitHub, test tay, handover, cập nhật 3 nơi). Đưa bảng lên branch `TrangPhuocHoangMinh_02690`. | Nhóm có candidate “monthly report ERP” với actor, 6 bước và số giờ; không phải list chung chung. |
| Pitch Problem Card | Pitch Card #1: cuối tháng gom 4 weekly + commit rồi viết chữ cho nhóm trưởng không đọc GitHub. Nói bottleneck là bước đối chiếu + viết narrative (~90–120 phút / tổng ~3 giờ), không phải buổi họp. | Bài vào shortlist rồi được chọn làm candidate nhóm, dù điểm tổng (31) thấp hơn group update của Trình (33). |
| Challenge bài của bạn khác | Hỏi Thắng: FAQ homestay 1000 tin/ngày thì Rule/FAQ đã đủ chưa, và chỉ một người trong nhóm nắm domain. Hỏi Bảo: chi tiêu Momo/banking khó validate chung + dính privacy. Hỏi Trình: form + 1 bảng task đã giảm phần lớn thời gian thì AI còn cần ở bước nào. Hỏi Hiếu: weekly intern có cùng pattern Git/task/chat → narrative, nên cluster với monthly chứ đừng chọn song song. | Nhóm loại FAQ homestay và chi tiêu vì domain/data cá nhân; gom monthly + group update + weekly vào một cụm “tổng hợp rồi viết cho người khác đọc”. |
| Gom trùng / cluster | Đưa ý: #1/#2/#4/#7/#10 của mình là cùng gốc “ghi lại vì quản lý không đọc GitHub”; tách #10 (nhập trùng 3 nơi → Rule) khỏi #4 (viết narrative cuối tháng → Workflow). | Cluster A trên `group-report.md` lấy monthly làm đại diện; Card #3 của mình không bị nhồi thành bài AI. |
| Chọn candidate problem | Giữ monthly report khi bảng điểm nghiêng về group update của Trình. Lập luận: impact lớn hơn (2.5–3.5 giờ/tháng), nguồn đã rõ (4 weekly + commit/PR), mình cung cấp được data pilot đã ẩn thông tin nhạy cảm. Nhận group update là phương án dự phòng. | Nhóm chốt monthly report ERP; ghi rõ vì sao chọn dù điểm thấp hơn, và điều kiện data phải do mình ẩn/chọn. |
| Validation / research | Xác nhận với nhóm: 3 giờ là ước lượng, chưa bấm giờ 2 kỳ. Chưa interview quản lý. Không tự bịa quote. Research tool (GitHub Projects, Jira Automation, Slack AI) để Hiếu làm; mình chỉ xác nhận GitHub là nguồn kỹ thuật, không phải chỗ quản lý đọc. | `group-report.md` ghi interview/survey = 0 và baseline phải đo lại trong pilot. Không lấy số AI bịa. |
| Workflow nhóm | Mang workflow 6 bước từ individual report: mở weekly → lấy commit → đối chiếu → viết narrative → copy Excel/phiếu → gửi. Chỉ bottleneck ở bước 3–4. Nhắc future phải có human review và fallback bỏ draft. | Bản nhóm giữ before ~180 phút / after <45 phút, AI chỉ sau khi source đã map. |
| Problem Statement | Cung cấp actor (ERP Engineer → quản lý không dùng GitHub), bottleneck “dịch commit”, metric <45 phút + không tăng câu hỏi lại, boundary: AI không tự lấy data công ty, không tự gửi, không bịa task. | PS v0/v1 trên bản nhóm dùng đúng các field này; Thắng tổng hợp câu chữ, mình giữ phần domain. |
| Rule / Workflow / Agent | Giữ lập luận: Rule cho template + 1 nguồn; Workflow cho AI draft narrative; không Agent vì không cần tự lập kế hoạch/tự gửi. Card #3 (GitHub/Excel/phiếu) để chứng minh có bài nên dừng ở Rule. | Nhóm chọn Workflow pilot, Agent = không chọn. Bảng R/W/A trong group report khớp hướng này. |
| Decision | Đồng ý **Go chỉ với pilot nhỏ**: 2 monthly lịch sử đã ẩn PII, chạy song song template thủ công vs AI draft, mình review từng claim có source rồi mới gửi. Nếu draft phải viết lại >50% hoặc lộ data nhạy cảm thì rollback về template. | Quyết định cuối trên `main` là Go — pilot bán thủ công, có rollback. Mình là domain owner / người gửi duy nhất. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Workflow 6 bước monthly report, câu chốt “pain là dịch commit thành chữ chứ không phải lấy số”,
và điều kiện pilot: chỉ dùng data mình chọn/ẩn, AI không tự gửi. Các phần đó đi từ
individual-report của mình vào group-report.md trên main.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Đưa bảng 10 dòng (lăng kính/problem/actor/dấu hiệu) + công việc tuần/tháng, nhờ đối chiếu rubric Phase 1: actor đã cụ thể chưa, đã có số chưa, dòng nào trùng, dòng nào cần siết. | Siết “nhân viên, quản lý” thành ERP Engineer / nhóm trưởng / HCNS; thêm số phút; tách pain họp thứ Hai thành pain chuẩn bị tài liệu. | Muốn gộp #1 #2 #4 #7 #10 thành một dòng “báo cáo”, hoặc biến giấy ra cổng / chờ approve thành bài AI. | Giữ 10 dòng vì tần suất khác nhau. Bỏ #3 và #5 khỏi top 3. Không biến thành agent. |
| Problem Card | Nhờ điền 3 card đủ field và vẽ workflow trước/sau. | Ép mỗi card có bottleneck 1 bước, metric, non-AI alternative, fallback. | Dễ viết giống ví dụ Weekly Report của PM (Jira/Sheets/Slack) và nhảy Agent. | Giữ bối cảnh Lug + quản lý không dùng GitHub. Card #3 chọn Rule, không AI. Pitch Card #1. |
| Workflow | Nhờ viết ASCII current/future từ mô tả 6 bước. | Nhanh ra before ~180' / after ~40' và chỗ gắn Rule vs AI vs người. | Gộp bước viết narrative với bước review, làm mất chỗ nghẽn thật. | Tách đối chiếu 40' + viết 70' là bottleneck; review 25' là human boundary. Cấm AI tự gửi. |
| Research | Không dùng. | — | — | Để Hiếu tìm GitHub Projects, Jira Automation, Slack AI. Mình chỉ xác nhận: dashboard GitHub không thay narrative cho quản lý. |
| Problem Statement | Không để AI viết thay 6 field. Chỉ kiểm lại actor/workflow/metric/boundary cho đúng việc mình làm. | — | Nếu viết thay, dễ để metric “nhanh hơn” và boundary mơ hồ. | Tự chốt: <45 phút; 100% claim có source; không tăng hỏi lại; không tự lấy/sửa/gửi data công ty. |
| Rule / Workflow / Agent | Nhờ phản biện “đã nhảy Agent quá sớm chưa”. | Nhắc Rule có thể đủ phần gom nguồn/template. | Gợi ý Agent tự đọc GitHub/Excel/chat rồi tự gửi report. | Chọn Workflow. Agent loại vì permission + risk tự gửi. Card #10 giữ làm ví dụ Rule. |
| Decision | Không dùng. Nhóm tự chốt. | — | AI sẽ nghiêng Go cho “ngầu”, bỏ qua data công ty chưa xin. | Go chỉ pilot 2 report lịch sử, ẩn PII, có rollback. Baseline 3 giờ phải bấm giờ lại. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 của cả nhóm, mình thấy cùng một pattern: Thắng trả lời FAQ homestay,
Bảo gom chi tiêu nhiều ví, Trình viết group update từ chat/bảng/file, Hiếu viết
weekly từ Git/Jira/chat, còn mình viết monthly từ weekly + GitHub. Khác domain,
nhưng đều là “nguồn rải → viết cho người khác đọc”. Bài của Thắng và Bảo pain thật
nhưng nhóm không validate chung được; bài Hiếu xác nhận pattern của mình chứ không
cần chọn thêm một report nữa. Lúc chấm điểm, group update của Trình được 33, monthly
của mình 31. Mình suýt nghĩ nhóm nên lấy bài Trình vì dễ làm trong lab hơn. Sau khi
bị challenge đúng chỗ yếu — 3 giờ chưa bấm giờ, chưa hỏi quản lý có cần narrative
không — mình không đổi candidate, nhưng đổi quyết định: không Go triển khai, chỉ Go
pilot nhỏ, và nhận group update làm phương án dự phòng nếu data công ty không dùng
được. Nhóm không đòi Agent cho ngầu; mình và Trình cùng giữ Workflow, AI chỉ draft
sau khi source đã map, người gửi vẫn là mình. Dấu tay mình trong bản cuối là workflow
6 bước, câu “pain là dịch commit chứ không phải lấy số”, và boundary cấm AI tự lấy
data / tự gửi. Chỗ khó nhất của Problem Statement không phải viết actor, mà là metric
và boundary: số giờ đang là ước lượng, còn data Lug thì không được đưa nguyên vào
lab. Nếu làm lại, mình sẽ challenge mạnh hơn ở validation — group report đang ghi
0 interview — và bắt mình bấm giờ một kỳ monthly thật trước khi tin mục tiêu dưới
45 phút.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
