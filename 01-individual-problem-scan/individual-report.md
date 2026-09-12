# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Trang Phước Hoàng Minh
- Mã học viên: 2A202602690
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): ERP Engineer at Lug
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Chuẩn bị tài liệu công việc đã làm tuần trước để báo cáo vào thứ Hai hằng tuần
  - Báo cáo tiến độ và demo code cho nhóm trưởng
  - Đợi validate từ nhóm trưởng rồi mới làm tiếp task mới
  - Đẩy code lên GitHub, viết báo cáo tuần, rồi viết thêm một báo cáo khác cùng dữ liệu để cuối tháng tổng hợp

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Mỗi thứ Hai phải dừng làm task để chuẩn bị tài liệu rồi họp báo cáo tiến độ tuần trước | ERP Engineer, nhóm trưởng | 1 lần/tuần; ước lượng ~45 phút chuẩn bị tài liệu + ~30 phút họp. Pain nằm ở khâu chuẩn bị, không phải bản thân buổi họp. |
| 2 | Lặp lại + Tốn thời gian | Trong lúc làm task vẫn phải viết báo cáo tiến độ và demo thủ công phần code đã xong cho nhóm trưởng | ERP Engineer, nhóm trưởng | Lặp theo từng task, khoảng 2–4 lần/tuần; mỗi lần ~20–30 phút viết tiến độ + demo. Không có kênh nào tự lấy tiến độ từ GitHub. |
| 3 | Tốn thời gian | Mỗi lần ra ngoài công ty phải điền giấy ra cổng, xin HCNS ký, rồi trình bảo vệ | ERP Engineer, HCNS, bảo vệ | Mỗi lần ra cổng; điền + tìm người ký ~10–15 phút. Nếu HCNS bận, chờ thêm ~15–30 phút. Đây là pain quy trình giấy, không phải pain ngôn ngữ/ngữ cảnh. |
| 4 | Lặp lại + Tốn thời gian | Cuối tháng phải tổng hợp báo cáo công việc từ các weekly report và GitHub commits thành một file khác | ERP Engineer, nhóm trưởng / quản lý | 1 lần/tháng; ước lượng ~2.5–3.5 giờ vì phải mở nhiều weekly, đối chiếu commit, rồi viết lại. Cùng dữ liệu đã ghi trong tuần nhưng format khác. |
| 5 | Pain từ người khác | Task code đã xong nhưng bị block vì phải chờ nhóm trưởng review/approve mới được làm task mới | ERP Engineer, nhóm trưởng | Code có thể xong trong 1–2 ngày nhưng cycle time kéo ~5–7 ngày vì chờ review. Engineer ngồi chờ, nhóm trưởng cũng bị dồn review. |
| 6 | AI có thể tốt hơn | Requirement và hướng đi của task nằm rải ở nhiều file cũ/mới (docs, chat, file task), khó biết bản nào là mới nhất | ERP Engineer, nhóm trưởng | Mỗi lần nhận task mới hoặc requirement đổi: ~20–40 phút tìm + đối chiếu. Dễ code theo file cũ rồi phải làm lại. Không có chỗ ghi “đây là version hiện hành”. |
| 7 | Tốn thời gian + AI có thể tốt hơn | Quản lý không dùng GitHub nên engineer phải viết lại thông tin đã có trên commit/PR thành report chữ cho người không kỹ thuật đọc | ERP Engineer, quản lý / nhóm trưởng | Mỗi lần báo cáo tuần/tháng mất thêm ~30–45 phút “dịch” commit → ngôn ngữ quản lý. Đây là viết lại thông tin đã tồn tại, không phải phát sinh việc mới. |
| 8 | Lặp lại + Tốn thời gian | Mỗi lần sửa code phải test lại thủ công từ đầu toàn bộ flow nghiệp vụ, vì chưa có bộ test/regression ổn định | ERP Engineer | ~30–60 phút/lần test full flow; khoảng 3–5 lần/tuần khi đang implement. Lặp lại cùng các bước click/nhập liệu. |
| 9 | Tốn thời gian | Khi bàn giao task phải giải thích lại context, việc đã làm, trạng thái hiện tại và next steps | Người bàn giao (ERP Engineer), người nhận | Mỗi lần handover ~20–30 phút nói lại. Thiếu ghi chép chuẩn nên người nhận hay hỏi lại cùng câu. |
| 10 | Lặp lại + Tốn thời gian | Sau khi xong task phải cập nhật cùng một thông tin lên GitHub, Excel và phiếu task của trưởng nhóm | ERP Engineer, nhóm trưởng | ~10–15 phút extra/task × 3 nơi; 2–4 task/tuần. Quên 1 nơi thì trạng thái lệch (GitHub đã xong, phiếu vẫn “đang làm”). |

> Các số thời gian trên là ước lượng từ trải nghiệm làm ERP Engineer tại Lug (chưa bấm giờ đủ 2 tuần liên tiếp). Trước khi pitch, nên bấm giờ 1–2 lần thật cho dòng #4, #6, #7, #10.

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Đưa bảng scan 10 dòng (lăng kính / problem / actor / dấu hiệu) rồi nhờ đối chiếu với rubric Phase 1: actor có đủ cụ thể không, dấu hiệu đã có số chưa, dòng nào trùng, dòng nào không phải bài AI.
- Ý dùng được: Siết actor từ “nhân viên, quản lý” thành ERP Engineer / nhóm trưởng / HCNS; thêm số đo thời gian; tách pain “họp thứ Hai” thành pain “chuẩn bị tài liệu”; giữ #3 và #5 vì scan cần rộng, dù không phải bài AI tốt.
- Ý bỏ vì không phải pain thật: Không biến #3 (giấy ra cổng) hay #5 (chờ approve) thành “xây agent”. Không gộp hết #1, #2, #4, #7, #10 thành một dòng “báo cáo” vì tần suất và bước nghẽn khác nhau.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính (đủ 4: Lặp lại, Tốn thời gian, AI có thể tốt hơn, Pain từ người khác)
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | #4 Cuối tháng tổng hợp báo cáo từ weekly report + GitHub commits | Actor rõ (ERP Engineer → nhóm trưởng). Workflow 6 bước vẽ được. Có baseline thời gian (~3 giờ/tháng) và lý do gốc (#7: quản lý không đọc GitHub). So sánh được Rule (template + 1 nguồn) vs Workflow (AI draft). | 3 giờ là ước lượng, chưa bấm giờ đủ 2 kỳ. “Báo cáo đủ tốt” đo bằng gì ngoài thời gian? Quản lý có chịu đọc dashboard/commit summary không? |
| 2 | #6 Requirement nằm rải nhiều file cũ/mới, khó biết bản mới nhất | Đúng lăng kính “AI có thể tốt hơn”: phải đọc, đối chiếu, giữ ngữ cảnh. Bottleneck cụ thể = tìm đúng version. Impact: làm sai requirement thì phải code lại. | File đang nằm ở đâu (local, chat, shared drive)? Ground truth “bản mới nhất” là ai chốt? Quyền truy cập data có đủ để AI search không? |
| 3 | #10 Cùng một task phải cập nhật GitHub + Excel + phiếu trưởng nhóm | Lặp theo từng task, đo được (~10–15 phút extra × 3 nơi). Rất hợp để so sánh No AI / Rule trước khi nhảy sang AI. Workflow ngắn, dễ pitch. | Nhóm trưởng có bắt buộc giữ phiếu giấy/Excel không? Nếu bắt buộc 3 nơi vì quy trình công ty thì Rule sync mới là lời giải, không phải AI. |

Không chọn vào top 3: #1 gần như là phiên bản tuần của #4; #2 là demo+report theo task, impact nhỏ hơn #4/#7; #3 giấy ra cổng là quy trình hành chính; #5 chờ review là tổ chức/process; #8 test full flow nghiêng về test tự động (Rule/script); #9 handover ít thường xuyên hơn #10; #7 gộp vào lập luận của Card #1 vì đó là nguyên nhân phải viết lại report.

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Tổng hợp báo cáo công việc cuối tháng

```text
Problem 1 câu:
Cuối tháng ERP Engineer mất khoảng 2.5–3.5 giờ để tổng hợp báo cáo công việc
từ weekly report và GitHub commits, vì phải viết lại cùng một dữ liệu thành
file chữ cho quản lý không dùng GitHub.

Actor:
ERP Engineer tại Lug (người viết báo cáo). Người nhận: nhóm trưởng / quản lý
không theo dõi GitHub.

Thời điểm / bối cảnh:
Cuối tháng, trước hạn nộp file tổng hợp công việc. Input là 4 weekly report
+ lịch sử commit/PR trong tháng.

Current workflow 3-7 bước:
1. Mở lần lượt các weekly report trong tháng
2. Vào GitHub lọc commit/PR/task đã làm
3. Đối chiếu weekly vs GitHub vì hai nguồn hay lệch nhau
4. Viết lại thành file tổng hợp theo format quản lý (diễn giải, không phải diff)
5. Copy cùng nội dung sang Excel / phiếu nếu trưởng nhóm yêu cầu
6. Gửi nhóm trưởng, chỉnh theo comment, nộp lại

Bottleneck:
Bước 3–4: đối chiếu nhiều nguồn rồi viết narrative. Ước lượng ~90–120 phút
trên tổng ~2.5–3.5 giờ. Không phải bước “lấy số”, mà bước “dịch” commit
thành việc quản lý đọc được.

Impact:
~3 giờ/tháng cho 1 engineer, lặp lại mỗi tháng. Dễ sót task hoặc ghi trùng.
Quản lý nhận báo cáo trễ / thiếu nên hỏi lại. Cùng dữ liệu đã nhập lúc làm
task (#2, #10) nhưng vẫn phải viết lần nữa.

Success metric:
Giảm thời gian tổng hợp từ ~3 giờ xuống dưới 45 phút/tháng; số lần nhóm trưởng
hỏi lại / yêu cầu bổ sung không tăng so với hiện tại.

Non-AI alternative:
Một nguồn sự thật: GitHub (hoặc 1 sheet) + template monthly cố định + checklist
field. Đủ nếu quản lý chịu đọc danh sách task/commit đã chuẩn hóa. Chưa đủ nếu
họ vẫn cần đoạn diễn giải “đã làm gì / ảnh hưởng gì / làm tiếp gì”.

AI hypothesis:
Sau khi gom weekly + commit log, AI draft narrative theo template. Engineer
chỉ kiểm tra thiếu/thừa và sửa câu. Không để AI tự gửi hay tự bịa task.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ~180 phút (3 giờ)

[1 Mở weekly reports: 20']
→ [2 Lấy commit/PR GitHub: 25']
→ [3 Đối chiếu 2 nguồn: 40']  <-- bottleneck (cùng #4 bước nghẽn)
→ [4 Viết narrative cho quản lý: 70']  <-- bottleneck chính
→ [5 Copy sang Excel/phiếu: 15']
→ [6 Gửi + sửa theo comment: 10']

FUTURE STATE — ~40 phút

[1 Export weekly + commit log: 5']          -- Rule/script
→ [2 AI map vào template monthly: 2']       -- Workflow
→ [3 AI draft narrative: 3']                -- Workflow
→ [4 Engineer review + sửa: 25']            <-- human boundary
→ [5 Engineer gửi: 5']

Fallback: AI sót task / bịa việc / giọng không đúng → bỏ draft, viết lại từ
template + checklist. Không gửi bản AI chưa review.

Risk mới: hallucination (ghi task không làm). Mitigation: chỉ được dùng
commit/weekly đã paste vào; cấm bịa.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Requirement rải rác, không biết bản mới nhất

```text
Problem 1 câu:
Khi nhận hoặc đang làm task, ERP Engineer mất khoảng 20–40 phút tìm requirement
vì hướng đi nằm rải ở nhiều file cũ/mới, không có chỗ nào ghi bản nào đang có hiệu lực.

Actor:
ERP Engineer (người phải hiểu đúng spec trước khi code). Nhóm trưởng là người
cập nhật yêu cầu rải rác và chịu ảnh hưởng nếu làm sai.

Thời điểm / bối cảnh:
Lúc nhận task mới, lúc requirement đổi giữa chừng, hoặc lúc quay lại task
sau vài ngày.

Current workflow 3-7 bước:
1. Nhận tên task / mô tả ngắn từ nhóm trưởng
2. Tìm trong folder, file Word/Excel cũ, chat, phiếu task
3. Mở vài version, đọc và đoán file nào mới hơn
4. Nếu không chắc thì hỏi lại nhóm trưởng
5. Bắt đầu code theo bản mình tin là đúng
6. (Hay xảy ra) giữa chừng phát hiện thêm file mới hơn → sửa lại

Bottleneck:
Bước 2–3: search + đối chiếu version. ~20–40 phút/lần, chưa kể thời gian
code lại nếu chọn nhầm file cũ.

Impact:
Chậm start task. Rủi ro làm sai hướng. Nhóm trưởng bị hỏi lại. Effort làm lại
lớn hơn effort tìm file ban đầu.

Success metric:
Thời gian tìm đúng requirement từ ~30 phút xuống dưới 5 phút/lần; số lần
phải hỏi “file nào là mới nhất?” và số lần code lại vì spec cũ giảm đi.

Non-AI alternative:
Một thư mục chuẩn + quy tắc đặt tên + file/pinned note “CURRENT SPEC” +
cấm sửa bằng cách tạo file song song. Rule này có thể giải 70% nếu team
tuân thủ. AI chỉ đáng dùng khi lịch sử file lộn xộn đã tồn tại và không
dọn ngay được.

AI hypothesis:
AI search theo task name, so sánh vài file liên quan, chỉ ra khác biệt và
trích đoạn “có vẻ là bản mới nhất” kèm nguồn. Engineer/nhóm trưởng confirm
trước khi code.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~35 phút tìm spec (chưa kể code lại)

[1 Nhận task: 2']
→ [2 Search nhiều folder/chat/file: 15']  <-- bottleneck
→ [3 Đọc/đối chiếu version: 12']         <-- bottleneck
→ [4 Hỏi lại nhóm trưởng: 5']
→ [5 Bắt đầu code theo bản đoán được]

FUTURE STATE — ~8 phút

[1 Nhận task + mã/tên: 1']
→ [2 AI search + xếp file liên quan: 1']     -- Workflow
→ [3 AI diff + chỉ nguồn “có vẻ current”: 1'] -- Workflow
→ [4 Engineer/lead confirm spec: 4']         <-- human boundary
→ [5 Bắt đầu code: 1']

Fallback: AI chọn nhầm file cũ → engineer không code theo AI, hỏi lead
và gắn nhãn CURRENT SPEC cho lần sau.

Boundary: AI không được tự chốt requirement. Chỉ đề xuất + cite nguồn.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Cập nhật cùng task ở GitHub, Excel và phiếu

```text
Problem 1 câu:
Mỗi khi xong task, ERP Engineer phải ghi cùng một thông tin lên GitHub, Excel
và phiếu task của trưởng nhóm, mất thêm khoảng 10–15 phút/task và dễ lệch trạng thái.

Actor:
ERP Engineer (người cập nhật 3 nơi). Nhóm trưởng (đọc phiếu/Excel, không đọc
GitHub).

Thời điểm / bối cảnh:
Ngay sau khi commit/push hoặc sau demo task. Lặp 2–4 lần/tuần.

Current workflow 3-7 bước:
1. Làm xong phần code của task
2. Commit/push GitHub, viết message
3. Mở Excel, sửa status / ghi chú cùng nội dung
4. Ghi vào phiếu task của trưởng nhóm
5. Báo nhóm trưởng (chat/họp) là đã xong

Bottleneck:
Bước 3–4: nhập lại thông tin đã có ở bước 2. Không phải bước khó về chuyên môn,
nhưng lặp và là nguồn lệch status.

Impact:
~10–15 phút extra/task × ~3 task/tuần ≈ 30–45 phút/tuần. Nếu quên 1 nơi,
nhóm trưởng vẫn thấy “đang làm” trong khi GitHub đã xong (hoặc ngược lại).
Đây cũng là lý do cuối tháng phải đối chiếu nhiều nguồn (Card #1).

Success metric:
Chỉ cập nhật 1 lần/task; Excel/phiếu lấy từ GitHub (hoặc form chung).
Thời gian extra từ ~12 phút xuống dưới 2 phút. Số lần status lệch 3 hệ thống
→ 0 trong 2 tuần thử.

Non-AI alternative:
Quy ước 1 nguồn sự thật (GitHub) + export/copy 1 cột sang sheet; hoặc 1 form
điền 1 lần, trưởng nhóm đọc form đó thay phiếu. Khả năng Rule/process đủ
70–80% mà không cần AI.

AI hypothesis:
Chỉ đáng dùng nếu vẫn bắt buộc 3 format chữ khác nhau: AI lấy commit message
điền Excel + phiếu. Không cần Agent. Ưu tiên thử Rule trước.

Quick gut:
[x] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~12 phút extra / task (× 3 task/tuần ≈ 36 phút)

[1 Commit/push GitHub: 3']
→ [2 Mở Excel ghi lại: 4']     <-- bottleneck (duplicate)
→ [3 Ghi phiếu trưởng nhóm: 4'] <-- bottleneck (duplicate)
→ [4 Báo đã xong: 1']

FUTURE STATE — ~3 phút / task  (ưu tiên Rule, chưa cần AI)

[1 Commit/push theo convention (task id + status): 2']  -- Rule
→ [2 Sheet/phiếu lấy từ GitHub hoặc form 1 lần: 0.5']   -- Rule
→ [3 Engineer/lead glance xác nhận status: 0.5']        <-- human boundary

Nếu công ty bắt buộc 3 format chữ khác nhau:
[1 Commit: 2']
→ [2 AI điền draft Excel + phiếu từ commit: 0.5']
→ [3 Engineer check 30 giây rồi lưu: 1']  <-- human boundary

Fallback: sync sai status → quay lại GitHub làm nguồn, sửa tay 2 nơi còn lại.
Không để AI tự đóng task.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Tổng hợp báo cáo công việc cuối tháng
(gốc từ scan #4, nguyên nhân từ #7: quản lý không dùng GitHub)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Đây là workflow tôi làm thật mỗi tháng: gom weekly + GitHub rồi viết lại cho
người không đọc commit. Baseline ước lượng ~3 giờ, bước nghẽn là đối chiếu
nguồn và viết narrative (~90–120 phút), không phải “họp thứ Hai”. Có thể so
sánh thẳng: template/1 nguồn (Rule) vs AI draft + người review (Workflow);
chưa cần Agent. Card #3 giải phần nhập trùng hằng tuần, Card #1 giải phần
viết lại thành chữ cuối tháng.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1) ~3 giờ/tháng là ước lượng; nếu bấm giờ thật chỉ còn 60 phút thì bài này
   còn đáng làm trong lab không?
2) Nếu nhóm trưởng chịu đọc 1 sheet/export GitHub, Rule đã đủ — mình đang
   giả định họ cần narrative; giả định đó đã kiểm chứng chưa?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Actor “quản lý” còn rộng; metric mới đo thời gian, chưa đo chất lượng báo cáo; #1/#2/#4/#7/#10 dễ bị xem là cùng 1 problem; baseline chưa phải số bấm giờ; nhảy sang AI khi chưa thử template.
- Tôi sửa gì: Thu hẹp người nhận = nhóm trưởng không dùng GitHub; tách Card #3 (nhập trùng 3 nơi, ưu tiên Rule) khỏi Card #1 (viết narrative cuối tháng, Workflow); ghi rõ số là ước lượng; thêm non-AI alternative và fallback; không chọn Agent.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
