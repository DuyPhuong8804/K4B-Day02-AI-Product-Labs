# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Bùi Phương Duy
- Mã học viên: 2A202602684
- Nhóm: Recall
- Candidate problem nhóm chọn: RecallAI — người dùng save bài viết/video để đọc sau nhưng phần lớn không quay lại đọc (digital hoarding); AI tóm tắt, xếp priority và "resurface" đúng lúc nội dung đã lưu.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 problems theo 4 lăng kính (báo cáo thực tập, nấu ăn, giặt phơi, nhận hàng shipper, cuộc gọi lừa đảo, tổng hợp ghi chú ôn thi, debug ML, tìm lại chat nhóm, deadline chồng chéo) | Đóng góp 3 candidate (báo cáo thực tập, shipper, ôn thi) vào pool candidates của nhóm ở Phase 3.1 |
| Pitch Problem Card | Chuẩn bị và trình bày Problem Card #1 (viết báo cáo thực tập hàng tuần) kèm 2 câu hỏi tự challenge (daily log thiếu chi tiết, effort tổng có giảm thật không) | Nhóm ghi nhận nhưng cuối cùng hội tụ chọn candidate khác của nhóm (bài toán "lưu nội dung để đọc sau nhưng bị bỏ quên") |
| Challenge bài của bạn khác | Đặt 12 câu hỏi phản biện theo 6 nhóm (giả định gốc, tính khả thi AI, metric, cạnh tranh, pháp lý/đạo đức, mô hình kinh doanh) cho candidate của nhóm | Nhóm giữ hướng đo Saved-to-Read Rate trong khung thời gian (4 tuần, không kỳ vọng đọc tức thì), giới hạn MVP ở nội dung text/URL, thêm fallback đánh dấu "Không hữu ích", và thêm boundary loại trừ trang paywall/đăng nhập |
| Gom trùng / cluster | Đóng góp candidate #6 (tổng hợp ghi chú ôn thi) vào thảo luận cluster; candidate này được nhóm gom vào Cluster B cùng 5 candidate khác (lưu/tìm/đọc tài liệu khó tổng hợp) | Nhóm ghi nhận Cluster B là "cluster phù hợp nhất với #16" — góp phần giúp nhóm nhận ra pattern chung dẫn tới candidate cuối được chọn |
| Chọn candidate problem | Tham gia thảo luận ở 3.3/3.4: dù cả 3 candidate cá nhân (#4, #5, #6) không vào shortlist cuối (chỉ có #1, #10, #16), vẫn theo dõi và góp ý trong phần chấm điểm 7 tiêu chí cho 3 candidate shortlist | Nhóm đồng thuận chọn #16 (34/35 điểm) làm candidate chính thức của nhóm |
| Validation / research | Tìm và kiểm 3 nguồn: Pocket data 2012 (TechCrunch) về tỷ lệ bookmark không đọc lại, nghiên cứu Digital Hoarding (Nature/PMC/Frontiers) về động lực tâm lý giữ nội dung; loại 1 nguồn content-farm có số liệu "42% cải thiện" không kiểm chứng được | Hướng phân khúc user từ nghiên cứu Digital Hoarding khớp với insight validation thật của nhóm (4.1): 2/8 người lưu ít/có deadline bắt buộc bị loại khỏi actor chính, chỉ giữ nhóm lưu nhiều nội dung không bắt buộc — giúp nhóm chỉnh success metric đo trong khung thời gian (4 tuần, không kỳ vọng đọc tức thì) |
| Workflow nhóm | Vai trò được nhóm phân công là "Workflow" (cùng Trần Thị Thu Hiền) — tham gia dựng current workflow (7 bước: tìm → lưu → để đó → tích tụ (bottleneck) → tìm lại → đánh giá (bottleneck) → quyết định) và future workflow (lưu → check trùng (Rule) → trích xuất (máy) → tóm tắt/gán tag (AI) → xếp hạng (AI) → review (boundary người) → đọc/feedback) | Nhóm có bảng workflow trước/sau đầy đủ actor, input, output, thời gian, bottleneck và before/after impact (20-35' → 5-10'/lần) — dùng làm nền viết Problem Statement và chọn mức Rule/Workflow/Agent |
| Problem Statement | Phản biện giả định "người dùng muốn đọc lại" và cách đo baseline (Q1, Q2, Q6, Q7 trong bộ câu hỏi) | Nhóm giữ baseline ước lượng 30-40% → target 55-60% sau 4 tuần (đo trong khung thời gian, không kỳ vọng đọc tức thì) và bổ sung Forgotten Rate + thời gian tìm lại nội dung làm metric phụ; PS v0 ghi rõ baseline/target sẽ được kiểm chứng lại qua pilot/user testing — đúng hướng câu hỏi tôi đặt ra về việc chưa có baseline thật |
| Rule / Workflow / Agent | Phản biện tính khả thi AI theo loại content (video/PDF/text) và logic priority/resurface (Q3-Q5) | PS v1 giới hạn Boundary chỉ xử lý URL bài viết công khai dạng text dưới 3000 từ, không xử lý video/PDF/trang paywall; future workflow (5.2) có bước fallback cho người dùng đánh dấu "Không hữu ích" để sửa sai của AI — khớp hướng câu hỏi tôi đặt về độ chính xác theo loại content và cơ chế kiểm soát |
| Decision | Đặt câu hỏi về rào cản gia nhập (đối thủ lớn/có sẵn copy được không) và rủi ro pháp lý khi xử lý nội dung có bản quyền (Q9, Q10) | Cùng hướng lý do nhóm loại 2 candidate còn lại ở 3.4 (bài "meeting notes" vì đã có Notion AI làm tốt, bài "notification" vì lo ngại truy xuất dữ liệu cá nhân) khi giữ lại #16; PS v1 Boundary thêm "không xử lý trang web bắt đăng nhập/paywall" để tránh rủi ro pháp lý |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Bộ 12 câu hỏi phản biện theo 6 nhóm (giả định, tính khả thi AI, metric, cạnh tranh, pháp lý, mô hình kinh doanh) cùng 2 nguồn nghiên cứu hành vi (Pocket, Digital Hoarding) mà nhóm dùng để chỉnh lại metric, boundary và phạm vi MVP.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi AI mở rộng từ 5 việc gốc (báo cáo thực tập, nấu ăn, giặt phơi, shipper, lừa đảo) sang 8-10 problem theo 4 lăng kính | Gợi ý thêm các problem trong học tập/đồ án (đọc paper, tổng hợp ghi chú ôn thi, debug code, tìm lại trao đổi nhóm cũ) mà tôi chưa nghĩ ra | Gợi ý ý số 6 quá chung/không phải pain thật | Bỏ ý 6, chỉ giữ ý có actor và số đo cụ thể |
| Problem Card | Nhờ AI đóng vai skeptical PM phản biện Problem Card #1 | Chỉ ra success metric chỉ đo thời gian, chưa đo chất lượng nội dung (mentor có phải hỏi lại không); "viết mạch lạc" còn mơ hồ | Không tự đề xuất metric thay tôi, chỉ chỉ ra lỗ hổng | Tự thêm tiêu chí "mentor không cần hỏi lại làm rõ trong 2 tuần liên tiếp" để đo cả chất lượng, không chỉ tốc độ |
| Workflow | Dùng AI để dựng nhanh 3 workflow ASCII (current + future) cho 3 Problem Card cá nhân (báo cáo thực tập, shipper, tổng hợp ghi chú ôn thi) ở Phase 2 | Giúp chia nhỏ bước theo cùng một format current/future nhất quán giữa 3 card, tiết kiệm thời gian so với tự vẽ tay từng bước | Ước lượng thời gian mỗi bước ban đầu do AI đề xuất không khớp với trải nghiệm thật (ví dụ gộp chung bước "viết + review" ở card báo cáo thực tập) | Tự tách lại từng bước và chỉnh số phút theo trải nghiệm thật của tôi (90'/150'/20' cho 3 card), tự xác định đúng bottleneck (bước 4 viết báo cáo, bước 3 thương lượng với shipper, bước 2 lọc chat nhóm) thay vì giữ nguyên AI đề xuất |
| Research | Dùng AI/search tìm nguồn dữ liệu hành vi (Pocket 2012, nghiên cứu Digital Hoarding) và so sánh đối thủ (Pocket, Readwise, Matter) | Tìm nhanh nhiều nguồn, gợi mở hướng nghiên cứu tâm lý "digital hoarding" mà tự tra cứu khó nghĩ ra | Có lúc đưa nguồn content-farm với số liệu "42% cải thiện" không có cơ sở kiểm chứng | Loại bỏ nguồn đó, chỉ giữ nguồn kiểm được (TechCrunch, Nature/PMC/Frontiers) |
| Problem Statement | Dùng AI để sinh và tự phản biện giả định "người dùng muốn đọc lại" và cách đo baseline/metric | Chỉ ra nhóm chưa có baseline Saved-to-Read Rate thật và rủi ro "save vì tâm lý" chứ không phải nhu cầu đọc thật | Ban đầu AI không tự nêu được cách đo baseline khi chưa có số liệu sẵn, chỉ dừng ở việc chỉ ra thiếu sót | Tự đề xuất neo theo số liệu ngành (Pocket/Instapaper) làm tạm baseline và đề xuất kiểm chứng lại qua pilot/user testing trước khi chốt target cuối |
| Rule / Workflow / Agent | Dùng AI hỏi phản biện tính khả thi AI theo loại content (video/PDF/text) và logic priority/resurface | Chỉ ra AI khó tóm tắt chính xác video/PDF phức tạp nếu không có xử lý riêng, và rủi ro cảm giác "ranking tùy tiện" nếu không giải thích được | AI ban đầu không tự đề xuất được cơ chế cụ thể để người dùng sửa sai, chỉ nêu rủi ro | Tự đề xuất giới hạn phạm vi ở nội dung text/URL trước, và cơ chế người dùng đánh dấu "Không hữu ích"/xem link gốc để tự kiểm khi nghi ngờ AI sai |
| Decision | Dùng AI hỏi về rào cản gia nhập, rủi ro bản quyền và mô hình kinh doanh | Chỉ ra rào cản gia nhập thấp (đối thủ lớn/sẵn có dễ làm tương tự) và rủi ro ToS khi tóm tắt nội dung trả phí/cần đăng nhập | Không tự đề xuất được moat cụ thể cho RecallAI, chỉ nêu rủi ro chung | Dùng chính câu hỏi này để so sánh giữa các candidate shortlist — nhận ra 2 candidate còn lại (meeting notes, notification) rủi ro cạnh tranh/data access cao hơn #16, ủng hộ giữ #16; đồng thời đề xuất thêm boundary loại trừ trang paywall/đăng nhập |

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



```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài (3.1 → 3.2 cluster → 3.3 shortlist → 3.4 score, group-report.md)
- [x] [15đ] Nhóm có workflow trước/sau (5.1/5.2, có actor/input/output/thời gian/bottleneck/fallback)
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh Rule / Workflow / Agent (6.1, kèm 5 câu hỏi chốt)
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ (Decision: Go, kèm pilot + exit/rollback)
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì — *còn thiếu mục 3 (đoạn reflection mở), cần tự viết*
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI — *tự xác nhận trước khi nộp, không tick thay bạn*
