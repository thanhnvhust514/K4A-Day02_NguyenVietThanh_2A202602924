# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Việt Thành
- Mã học viên: 2A202602924
- Nhóm: Đại bàng vui vẻ zone C
- Candidate problem nhóm chọn: Tự động hóa soạn thảo dự thảo Báo cáo bài tập lớn Word 40–60 trang từ Codebase và Schema DB (tập trung giải quyết nút thắt kẻ bảng đặc tả API/DB và dự thảo thuyết minh luồng nghiệp vụ theo đúng template Word chuẩn của khoa).

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 5 bài toán thực tế từ góc nhìn sinh viên năm cuối sử dụng hệ sinh thái dịch vụ Vin (VinBus, Green SM, MyVinmec, Green Express, Vincom); hoàn thiện 3 Problem Cards chi tiết có số liệu đo đạc (bấm giờ, log ticket #GSM-849201). | Đưa vào danh sách nhóm 2 bài toán tâm huyết: **• #1: Sự cố trừ tiền Xanh SM** và **• #2: Đọc kết quả khám MyVinmec**; tạo sự đa dạng về các dịch vụ hàng ngày của sinh viên. |
| Pitch Problem Card | Pitch 2 bài toán của mình; là **người hăng hái bảo vệ bài Xanh SM (#1) nhất** vì bức xúc tài chính thật khi sinh viên bị trừ tiền kép cuối tháng mà không có xe đi. | Thuyết phục được nhóm đưa bài toán #1 vào Top 3 Shortlist và xếp thứ 2 toàn nhóm ở vòng chấm điểm ban đầu (25/35 điểm). |
| Challenge bài của bạn khác | Phản biện bài #8 (Trợ lý tra cứu HDSD xe VinFast của bạn Quang) vì dễ trượt thành "chatbot hỏi đáp chung chung"; challenge bài #11 của bạn Ước về nguy cơ văn phong AI bị sáo rỗng và phạm vi cả quyển báo cáo 40–60 trang là quá rộng. | Nhóm nhận ra rủi ro văn phong AI sáo rỗng và quyết định siết chặt quy chuẩn thuyết minh theo khung Input $\rightarrow$ Process $\rightarrow$ Output, cấm dùng từ ngữ hoa mỹ. |
| Gom trùng / cluster | Cùng nhóm phân loại 12 bài toán thành 4 cụm chủ đề; phân tích sự tương đồng giữa bài của tôi và bài phản hồi dịch vụ của bạn Quang. | Giúp nhóm nhìn ra bức tranh tổng thể các mảng bài toán trước khi bước vào vòng chấm điểm và rút gọn shortlist. |
| Chọn candidate problem | Sau khi nghe bạn Ước phân tích rủi ro **"phải dùng dữ liệu giả (mock data) vì không tiếp cận được backend thật của GSM trong lab"**, Thành đồng ý chuyển sang ủng hộ bài viết Báo cáo (#11). | Đạt được sự đồng thuận 100% của nhóm một cách văn minh, thực tế; giúp nhóm tập trung vào bài toán khả thi nhất có sẵn dữ liệu code và DB trên máy để kiểm chứng ngay. |
| Validation / research | Trực tiếp tham gia phỏng vấn xác thực: **Kể trải nghiệm làm Frontend từng bị trừ 1.0 điểm trình bày do tài liệu viết lệch với code thật**; rà soát 3 công cụ research (Swagger, Mintlify, Copilot). | Khẳng định điểm nghẽn sai lệch thông số là có thật; chỉ ra khoảng trống công nghệ cốt lõi: Mintlify và Swagger không xuất được file Word `.docx` chuẩn thể thức đại học Việt Nam. |
| Workflow nhóm | **Góp ý đưa bước chụp ảnh màn hình demo và viết chú thích hình ảnh vào quy trình** (Bước 3); phản biện cảnh báo thời gian sinh viên review 15 phút cho 20–30 trang kỹ thuật là quá vội, cần có checklist. | Hoàn thiện quy trình 6 bước có cả phần minh họa giao diện Frontend; định lượng 2 điểm nghẽn chiếm 95 phút và hoàn thiện bảng Before/After giảm từ 210' xuống 55'. |
| Problem Statement | Tham gia viết và chuẩn hóa PS v0 và v1; trực tiếp viết phần ranh giới Boundary ("Làm" vs "Không làm"). | Thiết lập hàng rào bảo vệ liêm chính học thuật: AI chỉ trích xuất tham số và dự thảo thô, không tự động nộp bài và không bịa đặt số liệu thực nghiệm. |
| Rule / Workflow / Agent | Phản biện quyết liệt chống lại xu hướng muốn xây dựng "Autonomous Agent tự động clone repo nộp bài"; lập luận bảo vệ phương án Workflow lai (Rule bóc tách + LLM draft + Human review). | Nhóm thống nhất không sa đà vào bẫy "Agent hóa" phức tạp, tập trung tối ưu Workflow tuyến tính an toàn và kiểm soát được chi phí API. |
| Decision | Đồng thuận quyết định "Go"; cùng nhóm thiết kế phạm vi bài thử nghiệm nhỏ nhất (Pilot) trên module User & Auth (5 API, 2 bảng DB). | Tạo ra kế hoạch thử nghiệm thực tế đo được 3 chỉ số cụ thể trong lab và xây dựng phương án Rollback an toàn ngắt mạch khi AI gặp sự cố. |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi thể hiện ở hai đóng góp then chốt:
1. Về quy trình: Tôi mang chính trải nghiệm làm Frontend từng bị trừ 1.0 điểm vì tài liệu Word viết lệch tham số so với code thật để bổ sung bước chụp ảnh màn hình demo kèm quy định chú thích hình/bảng vào Bước 3, giúp báo cáo không bị vỡ layout khi cập nhật code.
2. Về ranh giới giải pháp: Tôi kiên quyết bảo vệ tính liêm chính học thuật bằng cách thiết lập ranh giới Boundary chặt chẽ (buộc AI chỉ draft luồng kỹ thuật theo khung Input-Process-Output, cấm viết văn sáo rỗng và cấm tự bịa số liệu thực nghiệm), đồng thời phản biện quyết liệt để kéo nhóm ra khỏi cái bẫy "Agent hóa" viển vông, giữ vững giải pháp Hybrid Workflow an toàn có con người kiểm duyệt ở chặng cuối.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Gợi ý các điểm nghẽn thực tế từ góc nhìn sinh viên dùng dịch vụ Vin (VinBus, GSM, Vinmec). | Mở rộng góc nhìn về sự cố trừ tiền ví điện tử Xanh SM và nỗi lo âu y tế khi đọc chỉ số MyVinmec. | Đề xuất các ý tưởng hời hợt như "AI mặc cả giá cuốc xe Xanh SM", "AI gợi ý thực đơn canteen". | Loại bỏ ngay các ý tưởng viễn vông, chỉ giữ lại các vấn đề có quy trình lặp lại và bấm giờ đo đạc được bằng số phút thật. |
| Problem Card | Nhờ AI đóng vai trò phản biện để soi xét độ chặt chẽ của Problem Card bài Xanh SM (#1). | Chỉ ra sự thiếu sót trong việc xác định Actor phụ (chuyên viên đối soát CSKH của ví điện tử). | Gợi ý metric cảm tính, chung chung kiểu "nâng cao trải nghiệm người dùng thêm 30%". | Tự viết lại metric đo lường định lượng kỹ thuật: "Rút ngắn thời gian hoàn tiền từ 3–7 ngày xuống dưới 15 phút". |
| Workflow | Nhờ AI chuyển đổi mô tả các bước thành text sơ đồ luồng Before / After. | Tạo khung sơ đồ tuần tự nhanh, trực quan hóa các chặng chuyển giao (handoff). | Tự ý gộp bước kẻ bảng API và viết thuyết minh làm một; ước lượng thời gian AI làm hết chỉ mất 2 phút (phi thực tế). | Tách rời 2 nút thắt riêng biệt (kẻ bảng 45' + viết văn 50') và bổ sung bước Human Review bắt buộc 15 phút. |
| Research | Tìm kiếm các công cụ và pattern chuyển đổi mã nguồn thành tài liệu kỹ thuật trên thế giới. | Nhanh chóng tổng hợp thông tin về Swagger Codegen, Mintlify AI và GitHub Copilot Docs. | Khẳng định Mintlify giải quyết trọn vẹn bài toán mà không nhận ra Mintlify chỉ xuất web docs SaaS, không hỗ trợ Word `.docx`. | Nhận định rõ khoảng trống công nghệ xuất bản Word học thuật tại Việt Nam, định hình giải pháp Hybrid Workflow. |
| Problem Statement | Nhờ AI tìm kiếm các câu từ mơ hồ trong bản nháp Problem Statement v0. | Phát hiện ra cụm từ "chất lượng văn phong thuyết minh của AI" còn định tính, khó nghiệm thu. | Gợi ý mở rộng ranh giới để AI viết luôn cả phần Kết luận và Đánh giá thực nghiệm của đồ án. | Bác bỏ gợi ý của AI; bổ sung tiêu chí nghiệm thu Input-Process-Output và siết chặt Boundary cấm AI bịa số liệu thực nghiệm. |
| Rule / Workflow / Agent | Yêu cầu AI đóng vai trò Grader phản biện xem bài toán có nhất thiết phải làm Agent không. | Cung cấp góc nhìn đối chiếu giữa Rule thuần túy và Workflow có điều phối. | Có xu hướng thiên vị Agent, gợi ý kịch bản "Autonomous Agent tự clone repo, tự test, tự nộp bài LMS cho ngầu". | Nhận định ngay đây là rủi ro cascading error và vi phạm liêm chính học thuật, giữ vững quyết định chọn Workflow. |
| Decision | Nhờ AI gợi ý kịch bản ngắt mạch (Rollback Plan) khi triển khai thực tế. | Gợi ý hay về ngưỡng tỷ lệ lỗi ảo giác (hallucination) 30% để kích hoạt dừng tầng AI. | Gợi ý phạm vi pilot quá rộng (chạy trên toàn bộ project môn học lớn, không thể làm kịp trong buổi lab 4 tiếng). | Cắt gọt phạm vi thử nghiệm về đúng 1 module nhỏ nhất: Module Quản lý người dùng & Xác thực (5 API, 2 bảng DB). |

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
Buổi thảo luận nhóm giúp tôi nhận ra một bài toán AI tốt phải bắt nguồn từ quy trình thực tế có thể đo đếm bằng phút, chứ không phải bài toán nghe thời thượng. Ban đầu, tôi hăng hái bảo vệ bài xử lý trừ tiền Xanh SM vì nỗi đau tài chính thực tế của sinh viên. Tuy nhiên, khi bạn Ước chỉ ra rào cản không thể truy cập backend thật của GSM trong buổi lab và phải dùng dữ liệu giả, tôi đã đồng thuận chuyển sang bài Báo cáo bài tập lớn. Dữ liệu bài tập lớn có sẵn 100% trên máy giúp nhóm kiểm chứng ngay tại lớp. Đóng góp cụ thể của tôi là mang trải nghiệm làm Frontend từng bị trừ điểm do lệch code để bổ sung bước chụp ảnh demo và chú thích vào quy trình. Khi nhóm manh nha ý tưởng làm Autonomous Agent tự nộp bài lên LMS cho ngầu, tôi đã phản biện nguy cơ lỗi ảo giác và vi phạm liêm chính học thuật để giữ nhóm ở mức Hybrid Workflow. Điều khó nhất với tôi là xác định Boundary: giới hạn AI chỉ draft phần kỹ thuật, không để AI can thiệp vào kết quả thực nghiệm. Nếu làm lại, tôi sẽ challenge nhóm thu hẹp phạm vi ngay từ đầu vào Chương Đặc tả Kỹ thuật thay vì ôm cả quyển 40–60 trang.
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
