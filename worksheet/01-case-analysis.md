---
artifact: 01 — Case Analysis
bai-tap: Lab 1 — Phân tích "tử huyệt" chiến lược
format: Cá nhân trước → share trong bàn → chốt verdict cuối
time: 20 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 1
---

# Lab 1 — Case Analysis / Phân tích "tử huyệt" chiến lược

**Case đã chọn:** Stack Overflow  
**Người làm:** Vũ Nhật Anh  
**Bàn / nhóm bàn:** (Nhóm của tôi)  
**Ngày:** 18/06/2026

> Đây là **file duy nhất** của Lab 1.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải kể lại "AI đã giết một công ty". Mục tiêu là chỉ ra, bằng bằng chứng thật:

1. **vì sao case đó bị tổn thương trước AI**
2. **điều gì đã thay đổi vĩnh viễn**
3. **và nếu rút một cảnh báo cho dự án của nhóm mình thì đó là gì**

Quy tắc xuyên suốt: **không có bằng chứng = không có nhận định.**

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 4 phần trong chính file này:

1. **3-5 bằng chứng chốt**
2. **4 nhận định bắt buộc**
3. **ghi chú sau khi share trong bàn**
4. **verdict cuối của cá nhân**

Nếu thiếu một trong bốn phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (20 phút)

```text
2'  Chọn case
8'  Làm cá nhân: gom bằng chứng + viết 4 nhận định
7'  Share trong bàn: 90 giây / người + hỏi vặn lại
3'  Tự sửa verdict cá nhân sau thảo luận
```

---

## Bước 0 — Chọn case thật nhanh

Mặc định: **bạn tự chọn case của mình**.

### Một case phù hợp cần có 4 điều

- [x] Có một **AI shock** hoặc mốc đổi cục diện đủ rõ
- [x] Có thể tìm được ít nhất **3-5 bằng chứng công khai**
- [x] Có tác động đủ nhìn thấy được ở user / doanh thu / pricing / traffic / cổ phiếu / usage / vị thế cạnh tranh
- [x] Có thể trả lời câu hỏi: **"Điều gì đã thay đổi vĩnh viễn?"**

### Điền nhanh trước khi làm

- **Case / sản phẩm / công ty:** Stack Overflow
- **AI / platform / sản phẩm mới tạo áp lực:** ChatGPT và GitHub Copilot
- **Vì sao tôi chọn case này?**  
  > Bởi vì đây là case điển hình của việc "hiệu ứng mạng" (network effects) mạnh bị phá vỡ nhanh chóng bởi generative AI. Lập trình viên thay vì hỏi và đợi cộng đồng trả lời thì nay đã chuyển sang hỏi AI để có ngay kết quả.

### Nếu bí case, chọn 1 trong 6 case gợi ý này

| Case | Vì sao đáng phân tích | Một tín hiệu đáng chú ý |
|---|---|---|
| Chegg | entry point học tập đổi rất nhanh | 7,8M → 3,2M thuê bao |
| Stack Overflow | hiệu ứng mạng bị đảo chiều | câu hỏi mới giảm mạnh sau ChatGPT |
| Jasper | lớp vỏ dễ bị generic AI ép | định giá và tăng trưởng chậm lại sau ChatGPT |
| Tome | AI phổ thông "đủ tốt" làm phân khúc cũ yếu đi | nhiều đợt cắt giảm và pivot |
| Inflection / Pi | chatbot tiêu dùng bị ông lớn lấn át | đội ngũ chuyển sang Microsoft |
| Figma / Claude Design | rủi ro "đất thuê" khi platform bước xuống app layer | cổ phiếu Figma phản ứng tiêu cực khi Claude Design ra mắt |

> Nếu có case riêng rõ hơn, dùng case riêng.

---

## Bước 1 — Gom 3-5 bằng chứng chốt

Không cần chép lại mọi số. Chỉ giữ những bằng chứng đủ mạnh để đỡ toàn bộ lập luận của bạn.

### Tìm bằng chứng theo 4 cụm

1. **Case trước AI**
   Sản phẩm là gì, user là ai, họ trả tiền cho cái gì, case từng thắng nhờ gì.

2. **AI shock**
   Mốc Big Tech AI / platform AI / sản phẩm mới xuất hiện và đổi luật chơi.

3. **Tác động quan sát được**
   User, doanh thu, ARR, pricing, traffic, usage, cổ phiếu, sa thải, pivot.

4. **Cục diện mới của thị trường**
   Ai phản ứng tốt hơn, ai thay thế tốt hơn, entry point mới nằm ở đâu, phân khúc còn sống không.

### Ưu tiên nguồn thế nào?

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 | Nguồn gốc | báo cáo tài chính, investor relations, pricing page, blog chính thức |
| 2 | Báo uy tín | Reuters, CNBC, Bloomberg, FT, TechCrunch |
| 3 | Dữ liệu công khai / tổng hợp | MacroTrends, Similarweb, Stack Overflow Survey, Sacra |

### Bảng bằng chứng chốt

| # | Bằng chứng / số liệu chốt | Vì sao số này quan trọng? | Nguồn |
|---|---|---|---|
| E1 | Traffic của Stack Overflow giảm khoảng 14% chỉ trong tháng đầu tiên và tiếp tục suy giảm đều đặn sau khi ChatGPT ra mắt. | Cho thấy user trực tiếp chuyển hành vi tìm kiếm câu trả lời ngay khi AI xuất hiện. | [Meta SO](https://meta.stackoverflow.com/questions/425651/thoughts-on-the-paper-are-large-language-models-a-threat-to-digital-public-good) |
| E2 | Lượng câu hỏi mới đăng lên Stack Overflow giảm tới 15-20% trong 6 tháng đầu sau AI shock. | Minh chứng hiệu ứng mạng (Network Effect) đang sụp đổ khi lượng data/câu hỏi mới giảm. | [Meta SO](https://meta.stackoverflow.com/questions/425651/thoughts-on-the-paper-are-large-language-models-a-threat-to-digital-public-good) |
| E3 | Stack Overflow buộc phải cắt giảm 28% nhân sự vào tháng 10 năm 2023. | Dấu hiệu rõ ràng về tác động tiêu cực lên vận hành khi mô hình kinh doanh bị ảnh hưởng. | [TechCrunch](https://techcrunch.com/2023/10/17/stack-overflow-cuts-28-of-its-staff/) |
| E4 | GitHub Copilot đạt trên 1.3 triệu người dùng trả phí và thống trị thị trường. | Entry point đã thay đổi: user không còn cần mở web browser, code được sinh ngay tại IDE. | [Copilot Stats](https://www.getpanto.ai/blog/github-copilot-statistics) |

### 3 phát hiện ban đầu

Trước khi viết nhận định, ghi nhanh 3 dòng:

1. **Case này từng thắng nhờ...**  
   > Hiệu ứng mạng khổng lồ: nội dung tốt thu hút user, user nhiều tạo thêm nội dung và SEO tốt. "Switching cost" từng rất cao dựa trên điểm uy tín (reputation points) - thứ dev dùng làm CV. Tuy nhiên, khi AI ra đời, dev sẵn sàng vứt bỏ "điểm ảo" này để đổi lấy tốc độ và code chạy được ngay lập tức.
2. **AI shock làm thay đổi...**  
   > Trải nghiệm tìm câu trả lời: từ việc phải đọc hiểu, chọn lọc giữa các comment sang việc AI tổng hợp và đưa ra ngay code snippet hoàn chỉnh.
3. **Dấu hiệu mạnh nhất cho thấy luật chơi mới là...**  
   > Sự suy giảm lượng câu hỏi mới, đồng nghĩa với việc data flywheel bị gãy, người dùng không cần lên web hỏi nữa vì AI trả lời đủ tốt và ngay lập tức.

---

## Bước 2 — Viết 4 nhận định bắt buộc

### Nhận định 1 — Trước AI, case này thắng nhờ giả định gì?

Gợi ý:

- Người dùng thuê sản phẩm này để làm gì?
- Giá trị lõi trước AI là gì?
- Họ thắng nhờ workflow, switching cost, brand, distribution, data hay một giả định hành vi nào?
- Job-to-be-done (công việc người dùng "thuê" sản phẩm làm hộ) là gì?

**Trả lời của tôi:**  
> Trước AI, Stack Overflow thắng nhờ giả định rằng "nơi duy nhất và tốt nhất để tìm giải pháp cho lỗi code là một cộng đồng lập trình viên khổng lồ". Job-to-be-done cốt lõi là "Tìm được đoạn code sửa lỗi nhanh nhất có thể để tiếp tục công việc". Giá trị cốt lõi là Data & Community Network Effect.

**Bằng chứng đỡ nhận định này:** E1, E2

---

### Nhận định 2 — Kỳ vọng người dùng và luật chơi cạnh tranh đã đổi ở đâu?

#### Nhắc nhanh 7 Dịch chuyển Kỳ vọng

1. Làm xong giúp tôi
2. May đo cho tôi
3. Tự lo việc lặt vặt
4. Trả theo kết quả
5. Phản hồi ngay
6. Giao diện tự thay đổi
7. Thấu hiểu ngữ cảnh

#### Nhắc nhanh 5 Competitive Dynamics

- switching costs giảm
- data advantages tăng
- platform risk
- build-copy cycles tăng tốc
- GTM + distribution quan trọng hơn

**Shift kỳ vọng quan trọng nhất:** Phản hồi ngay và Làm xong giúp tôi (đưa luôn đoạn code đúng với context thay vì phải tự ghép).  
**Competitive dynamic quan trọng nhất:** Platform risk & Distribution (AI platform và IDE chiếm lấy entry point của dev).

**Trả lời của tôi:**  
> Kỳ vọng đổi sang "May đo cho tôi": dev muốn nhận đoạn code giải quyết lỗi trong đúng ngữ cảnh của file đang viết, thay vì đọc các câu trả lời chung chung. Về luật chơi cạnh tranh, "entry point" đã bị dịch chuyển từ trình duyệt web (Google search) về thẳng IDE (thông qua Copilot/Cursor), dẫn đến rủi ro platform khổng lồ cho Stack Overflow.

**Bằng chứng đỡ nhận định này:** E1, E4

---

### Nhận định 3 — Giả định nào không còn đúng nữa? Điều gì đã thay đổi vĩnh viễn?

Gợi ý:

- Switching cost cũ có từng giữ user ở lại không? Vì sao giờ không còn đủ?
- Entry point cũ của sản phẩm có còn tồn tại không, hay người dùng đã chuyển sang một điểm bắt đầu mới?
- Workflow cũ có còn được chấp nhận không, hay chuẩn mới là "làm xong giúp tôi / ngay trong nơi tôi đang làm việc"?
- "Thay đổi vĩnh viễn" không phải là giá cổ phiếu giảm; nó là **chuẩn mới trong đầu người dùng** hoặc **luật chơi mới của thị trường**.
- Phân khúc này còn tồn tại không? Nếu còn, nó đang được phục vụ theo cách khác ra sao?

**Điều đã thay đổi vĩnh viễn theo tôi là:**  
> Điểm bắt đầu (Entry point) để giải quyết một lỗi code đã thay đổi vĩnh viễn. Nó không còn bắt đầu bằng việc mở trình duyệt web để Google nữa, mà bắt đầu bằng một câu prompt hoặc comment ngay trong IDE. Chuẩn mới là "Code sinh ra theo ngữ cảnh dự án" thay vì "Tìm kiếm kiến thức rồi tự điều chỉnh".

**Bằng chứng đỡ nhận định này:** E1, E4

---

### Nhận định 4 — Case này còn cứu được không? Nếu có, phải đổi bằng cách nào?

Gợi ý:

- Nếu cứu được: họ phải đổi ở moat nào, workflow nào, distribution nào?
- Nếu không cứu được: vì sao đã quá muộn?
- So với một đối thủ phản ứng tốt hơn, họ chậm ở đâu?

**Verdict ban đầu của tôi:** Có nhưng phải đổi rất mạnh

**Trả lời của tôi:**  
> Vẫn có thể cứu nhưng phải đổi cực mạnh từ mô hình "điểm đến web (B2C)" sang "nhà cung cấp dữ liệu độc quyền (B2B)". Stack Overflow đã ra chương trình API để bán data chất lượng cao cho các AI khổng lồ. Thay vì phục vụ end-user tìm kiếm qua web, khách hàng chính của họ bây giờ là các hệ thống đào tạo LLM.

**Bằng chứng đỡ nhận định này:** E3, E4

---

## Tóm tắt cá nhân trước khi share trong bàn

Viết đúng 3 câu:

1. `Case này yếu đi vì...`
2. `Điều thay đổi vĩnh viễn là...`
3. `Verdict của tôi là...`

**Bản tóm tắt 3 câu của tôi:**  
1. Case này yếu đi vì hiệu ứng mạng bị đứt gãy, và điểm bắt đầu (entry point) chuyển từ trình duyệt web thẳng vào bên trong IDE.  
2. Điều thay đổi vĩnh viễn là kỳ vọng người dùng chuyển sang "nhận code theo đúng context tức thì" thay vì phải tự "tìm kiếm và tổng hợp".  
3. Verdict của tôi là Stack Overflow phải chấp nhận mất một phần traffic trực tiếp và đổi hướng thành nhà cung cấp Data Training cho AI.

---

## Bước 3 — Share trong bàn (7')

### Mỗi người chỉ nói 4 thứ trong 90 giây

1. **Case bạn chọn là gì**
2. **Bằng chứng mạnh nhất bạn có là gì**
3. **Điều gì đã thay đổi vĩnh viễn**
4. **Verdict của bạn**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Bằng chứng mạnh nhất cho nhận định đó là gì?"**
2. **"Điều gì ở đây là triệu chứng, còn điều gì là thay đổi vĩnh viễn?"**
3. **"Nếu switching cost từng cao, vì sao người dùng vẫn rời đi?"**
4. **"Platform mới hoặc đối thủ mới đã chiếm entry point ở đâu?"**

### Ghi nhanh khi nghe các bạn cùng bàn

| Người | Case | Bằng chứng mạnh nhất họ nêu | Điều họ cho là "thay đổi vĩnh viễn" | Verdict của họ |
|---|---|---|---|---|
| Huy | Chegg | Mất 50% thuê bao | Thói quen hỏi bài tập chuyển sang AI miễn phí | Đổi thành AI tutor thay vì kho đáp án |
| Hà | Jasper | Sa thải và định giá giảm | Giá trị của wrapper AI là 0 khi AI gốc tiến hoá | Pivot sang thị trường enterprise |

### Sau khi cả bàn share xong, chốt 3 ý chung

**1. Bàn tôi thấy case nào có bằng chứng mạnh nhất? Vì sao?**  
> Case Stack Overflow có bằng chứng mạnh nhất vì traffic web là con số minh bạch và lượng user rất đại chúng, dễ thấy trực quan.

**2. Có pattern nào lặp lại giữa nhiều case không?**  
Ví dụ: switching costs giảm, platform bước xuống app layer, user chuyển sang "làm xong giúp tôi", moat cũ quá mỏng…  
> Pattern chung: Chuyển dịch kỳ vọng về "Làm xong giúp tôi" (đáp án trực tiếp) thay vì tìm tòi, và các lớp bọc (wrapper) rất dễ bị đè bẹp.

**3. Một cảnh báo cho chính dự án của nhóm tôi là gì?**  
> Dự án RiskGuard AI không được buộc Analyst phải rời khỏi màn hình làm việc chính của họ (entry point). AI phải nhúng sâu vào chính luồng review cảnh báo hiện tại của họ.

---

## Bước 4 — Chốt lại verdict cá nhân sau thảo luận (3')

### Sau khi nghe bàn phản biện, verdict của tôi:

- [ ] Giữ nguyên
- [x] Đổi nhẹ
- [ ] Đổi mạnh

### Vì sao tôi giữ / đổi verdict?

> Tôi đổi nhẹ để nhấn mạnh hơn vào sự dịch chuyển Entry Point. Bán data B2B chỉ là giải pháp tài chính, nếu muốn giữ sự hiện diện, họ buộc phải có extension nhúng thẳng vào IDE.

### Verdict cuối cùng của tôi (phiên bản nộp)

**Case này tổn thương trước AI vì:**  
> Họ mất quyền kiểm soát điểm bắt đầu (entry point) khi workflow tìm kiếm giải pháp chuyển dịch từ web browser sang ngay bên trong IDE.

**Điều thay đổi vĩnh viễn là:**  
> Trải nghiệm tiêu chuẩn của coding giờ đây mặc định bao gồm một trợ lý AI "may đo theo context", không phải một cơ sở dữ liệu web tĩnh.

**Nếu phải rút 1 bài học cho dự án của nhóm mình, tôi rút ra:**  
> Đừng tạo ra ma sát bằng cách bắt người dùng mở ứng dụng thứ hai. AI phải tìm đến tận "nơi người dùng làm việc" (ví dụ cung cấp risk score thẳng trên Dashboard duyệt).

---

## Checklist trước khi nộp

- [x] Tôi đã chọn ít nhất 3 bằng chứng chốt có nguồn.
- [x] Mỗi nhận định đều chỉ vào ít nhất 1 bằng chứng.
- [x] Tôi đã ghi lại phần share trong bàn.
- [x] Tôi đã viết verdict cuối sau thảo luận.

---

## Nếu còn thời gian / làm về nhà

- Bổ sung thêm một case "đối thủ phản ứng tốt hơn" để so.
- Kiểm lại xem case này yếu vì expectation shift, competitive dynamics, hay cả hai cùng lúc.

### Bonus 1: Tư duy Action-oriented
**Nếu tôi là PM của Stack Overflow trong 6 tháng đầu sau AI shock, tôi sẽ làm gì đầu tiên?**
> Thay vì cố gắng kéo user trở lại nền tảng web, tôi sẽ phát triển ngay lập tức một IDE extension (như một trợ lý ảo thu nhỏ dựa trên dữ liệu chuẩn của SO) để giành lại entry point của lập trình viên. Đồng thời, tôi sẽ khóa cổng API công khai để chống crawl data miễn phí, chuyển sang bán dữ liệu độc quyền (Enterprise API) cho các công ty huấn luyện LLM để tạo luồng doanh thu mới.
