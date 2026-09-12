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
| Challenge bài của bạn khác | Đặt 12 câu hỏi phản biện theo 6 nhóm (giả định gốc, tính khả thi AI, metric, cạnh tranh, pháp lý/đạo đức, mô hình kinh doanh) cho candidate của nhóm | Nhóm bổ sung: đo Saved-to-Read Rate trong khung 30 ngày, loại nhóm "hoarder tâm lý" khỏi target, giới hạn MVP ở nội dung text/URL, thêm UI ghim/ẩn, thêm boundary về bản quyền |
| Gom trùng / cluster | *(chưa tham gia trực tiếp bước này — nhóm tự làm 3.2)* | |
| Chọn candidate problem | *(chưa có vai trò rõ ở 3.3/3.4 — cần bổ sung nếu có tham gia)* | |
| Validation / research | Tìm và kiểm 3 nguồn: Pocket data 2012 (TechCrunch) về tỷ lệ bookmark không đọc lại, nghiên cứu Digital Hoarding (Nature/PMC/Frontiers) về động lực tâm lý giữ nội dung; loại 1 nguồn content-farm có số liệu "42% cải thiện" không kiểm chứng được | Giúp nhóm chỉnh success metric đo trong khung thời gian (không kỳ vọng đọc tức thì) và tách riêng nhóm user "hoarder tâm lý" ra khỏi target ban đầu |
| Workflow nhóm | *(chưa có vai trò rõ — cần bổ sung nếu có tham gia)* | |
| Problem Statement | Phản biện giả định "người dùng muốn đọc lại" và cách đo baseline (Q1, Q2, Q6, Q7 trong bộ câu hỏi) | Nhóm thêm bước khảo sát định tính 15-20 người trước khi build, đổi target thành % cải thiện tương đối thay vì số tuyệt đối, định nghĩa rõ "Forgotten Rate" như proxy đo được |
| Rule / Workflow / Agent | Phản biện tính khả thi AI theo loại content (video/PDF/text), logic priority decay, và cold-start (Q3-Q5) | Nhóm giới hạn MVP ưu tiên nội dung text/URL trước, thêm heuristic cho user mới, thêm yêu cầu minh bạch/kiểm soát cho cơ chế ranking |
| Decision | Đặt câu hỏi về rào cản gia nhập (đối thủ lớn copy được không), rủi ro bản quyền, và mô hình kinh doanh (Q8, Q9, Q10, Q12) | Nhóm xác định rõ đây là sản phẩm ngách (không cạnh tranh trực diện Notion/Google), thêm boundary không truy cập nội dung trả phí, ghi nhận bài toán tài chính để giải quyết ở giai đoạn sau |

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
| Problem Statement | Dùng AI để sinh và tự phản biện giả định "người dùng muốn đọc lại" và cách đo baseline/metric | Chỉ ra nhóm chưa có baseline Saved-to-Read Rate và rủi ro "save vì tâm lý" chứ không phải nhu cầu đọc thật | Ban đầu không tự nêu được cách đo baseline khi chưa có số liệu sẵn | Tự đề xuất đo bằng khảo sát định tính 15-20 người + neo theo số liệu ngành đã kiểm chứng, đổi target thành % cải thiện tương đối |
| Rule / Workflow / Agent | Dùng AI hỏi phản biện tính khả thi AI theo loại content, logic priority decay/resurface, và cold-start | Vạch ra rủi ro cold-start và cảm giác "ranking tùy tiện" với người dùng mới | Ban đầu chưa nhấn đủ vào yêu cầu explainability cho người dùng | Tự bổ sung yêu cầu UI ghim/ẩn để người dùng tự sửa sai của AI, tăng kiểm soát |
| Decision | Dùng AI hỏi về rào cản gia nhập, rủi ro bản quyền và mô hình kinh doanh | Chỉ ra rào cản gia nhập thấp (đối thủ lớn dễ copy) và rủi ro ToS khi tóm tắt nội dung trả phí | Không tự đề xuất được moat cụ thể, chỉ nêu rủi ro | Tự xác định moat thực tế nằm ở dữ liệu hành vi tích lũy + định vị sản phẩm ngách, không cạnh tranh trực diện nền tảng lớn |

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

- [ ] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ ] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
