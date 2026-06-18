---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** RiskGuard AI  

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** RiskGuard AI
- **Lát cắt tôi chọn để phân tích hôm nay là:** Giúp Fraud Analyst rà soát và đánh giá các cảnh báo giao dịch (alerts) có rủi ro cao.
- **Vì sao tôi chọn lát cắt này:**  
  > Vì quá trình review cảnh báo tốn nhiều thời gian nhất để thu thập evidence, khiến Analyst dễ bị quá tải trong giờ cao điểm.

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Giảm thiểu thời gian điều tra và sai sót khi rà soát các cảnh báo gian lận thủ công.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Fraud Analyst / Risk Investigator.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Mở nhiều tab/dashboard để tra soát lịch sử người dùng, IP, thiết bị, sau đó tổng hợp thủ công để đưa ra quyết định.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Các nhân viên phân tích rủi ro (Fraud Analyst) tại các tổ chức tài chính hoặc e-commerce.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Khi hệ thống rules engine bắn ra hàng loạt cảnh báo trong giờ cao điểm, buộc họ phải xử lý nhanh nhưng không được sai sót.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > Dashboard quản trị nội bộ, kết hợp SQL query thủ công và Excel để check log.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Gian lận ngày càng tinh vi, rules engine tạo ra quá nhiều False Positive khiến nhân sự bị quá tải. Đặc biệt là "Cost of doing nothing" rất lớn: Nếu Analyst không review kịp, công ty sẽ để lọt Fraud (mất tiền oan) hoặc block nhầm khách hàng xịn (bị phàn nàn và mất user).

### Tóm tắt market context trong 3-4 dòng

> Các Fraud Analyst đang bị quá tải bởi lượng lớn cảnh báo gian lận trong giờ cao điểm. Việc rà soát thủ công qua nhiều hệ thống tốn kém thời gian và dễ dẫn đến sai lầm. Cần một giải pháp tổng hợp và phân loại rủi ro nhanh chóng để họ ra quyết định chính xác hơn.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Fraud Analyst (Nhân viên phân tích gian lận).
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Vì họ là người trực tiếp click mở case, đọc data, và nhấn nút Approve / Reject cuối cùng trên hệ thống.

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Đánh giá mức độ rủi ro bằng AI cho các giao dịch bị cảnh báo.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: `AI`

### Bản chốt

**Core JTBD cuối cùng:**  
> Đánh giá mức độ rủi ro của một giao dịch đáng ngờ một cách chính xác trong quá trình rà soát hằng ngày.

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Hàng đợi cảnh báo tăng đột biến, | tôi muốn nhanh chóng nhận diện được đâu là rủi ro thực sự, | tập trung xử lý các case khẩn cấp trước mà không bỏ sót. | Áp lực về mặt thời gian và thứ tự ưu tiên (Triage). |
| JS2 | Nhìn vào một tài khoản có lịch sử phức tạp, | tôi muốn có đủ ngữ cảnh (context) về các giao dịch trước đó ngay lập tức, | ra quyết định tự tin mà không cần mở 5 tab khác nhau. | Pain point về việc phân mảnh dữ liệu (Locate context). |
| JS3 | Viết báo cáo giải trình cho một case bị đóng, | tôi muốn có sẵn các luận điểm rõ ràng, | hoàn thành công việc nhanh chóng và tuân thủ quy trình. | Nhu cầu tóm tắt và ghi nhận (Conclude & Document). |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Dashboard truyền thống kết hợp Excel | Tra cứu giao dịch, tổng hợp dữ liệu để so sánh. | Đầy đủ dữ liệu thô, dễ truy vấn bằng SQL. | Rất mất thời gian (10-15p cho 1 case thủ công), dẫn đến backlog ùn ứ nghiêm trọng trong giờ cao điểm. | Cao, vì đây là workflow chuẩn của công ty. |
| Các Rules Engine tĩnh (Rule-based) | Lọc bớt các rủi ro cơ bản (ví dụ: blacklist IP). | Hoạt động nhanh, có thể auto-block. | Tạo ra quá nhiều False Positive (báo động giả). | Thấp, vì người dùng sẵn sàng có công cụ hỗ trợ tốt hơn. |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Việc tra cứu thủ công đa nền tảng và viết SQL query để gom thông tin.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Nhận biết có cảnh báo rủi ro mới. | Bảng Alert Queue (Dashboard). | Số lượng quá nhiều, khó ưu tiên. | High |
| Locate | Tìm kiếm dữ liệu liên quan (lịch sử, thiết bị, IP). | Mở nhiều tab/ứng dụng nội bộ. | Phân mảnh data, tốn thao tác tra cứu. | High |
| Prepare | Tổng hợp và phân tích logic để đánh giá rủi ro. | Nhìn bằng mắt, nhẩm tính, copy-paste. | Dễ bỏ sót dấu hiệu bất thường tinh vi. | High |
| Confirm | Đối chiếu lại các rule của công ty. | Bộ quy tắc nội bộ. | Phải nhớ hoặc dò tài liệu cứng. | Med |
| Execute | Quyết định Approve, Reject hoặc Escalate. | Nhấn nút trên hệ thống. | Áp lực ra quyết định sai. | Med |
| Monitor | N/A | N/A | N/A | Low |
| Modify | Cập nhật lại quyết định nếu có khiếu nại. | Ticket system. | Quy trình rườm rà. | Med |
| Conclude | Ghi log và báo cáo lý do. | Gõ thủ công vào textbox ghi chú. | Tốn thời gian lặp đi lặp lại. | High |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Locate (Tìm kiếm và gom dữ liệu liên quan)  
**Bước đau nhất #2:** Prepare (Tổng hợp phân tích logic để nhận định)

**Vì sao đây là nơi đáng chú ý nhất:**  
> Giai đoạn Locate và Prepare chiếm tới 80% thời gian của một Analyst cho một case. Giải quyết được khâu này sẽ trực tiếp giúp họ tăng năng suất (làm được nhiều case hơn) và giảm mệt mỏi.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| Locate | Tổng hợp toàn bộ dữ liệu lịch sử thành một profile ngữ cảnh hiển thị trên cùng một màn hình. | Trích xuất và tóm tắt dữ liệu thô nhanh hơn con người rất nhiều. | Đưa thiếu dữ liệu quan trọng hoặc ảo giác (hallucination). |
| Prepare | Cung cấp Risk Score dựa trên ML (XGBoost) kèm theo các Risk Factors tự động tóm tắt làm bằng chứng. | Nhận diện pattern rủi ro trong dữ liệu lớn tốt hơn mắt người. | Analyst quá tin vào AI dẫn đến thiên kiến tự động (Automation Bias). |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> Đóng vai trò Analyst-Assist: Tổng hợp ngữ cảnh (Locate) và đề xuất bằng chứng rủi ro (Prepare) ngay trên màn hình Case Detail.

**Vì sao không phải ở bước khác:**  
> Không thay thế bước Execute (ra quyết định cuối) vì quyết định rủi ro vẫn cần yếu tố con người và tuân thủ các quy định nghiệp vụ nghiêm ngặt.

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp Fraud Analyst thu thập và phân tích dữ liệu tốt hơn ở bước Locate và Prepare,  
> bằng cách hiển thị điểm rủi ro tổng hợp kèm theo bằng chứng AI phân tích sẵn trên một màn hình duy nhất,  
> thì họ sẽ chuyển từ việc check thủ công qua nhiều hệ thống nội bộ sang việc sử dụng Dashboard RiskGuard AI,  
> vì nó giảm thiểu thời gian tra cứu và tăng độ tự tin khi ra quyết định.

### Tín hiệu sớm nếu hypothesis này đúng

1. Thời gian xử lý trung bình mỗi case (Average Handle Time) giảm xuống đáng kể.
2. Tỉ lệ False Positive được Analyst nhận diện và xử lý chính xác cao hơn.

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| Analyst sẽ tin tưởng AI Score. | Nếu họ không tin, họ vẫn sẽ tự check thủ công lại từ đầu, làm vô nghĩa giá trị của AI. | Chưa có, đây mới là phỏng đoán. | Thử nghiệm hiển thị Explainable AI (Giải thích lý do) và phỏng vấn xem họ có tin không. |
| Việc tổng hợp trên một màn hình (Single pane of glass) đủ cho họ ra quyết định. | Có thể nghiệp vụ của họ bắt buộc phải check chéo hệ thống ngoài mà ta không có API. | Phỏng vấn ban đầu thấy họ ghét mở nhiều tab. | Theo dõi hành vi sử dụng bằng heatmap/logging để xem họ có vẫn mở tab khác không. |

### Assumption nguy hiểm nhất nếu tôi đang sai

> Analyst không tin tưởng kết quả của AI và bị ảnh hưởng bởi Automation Bias, hoặc ngược lại, hoàn toàn phớt lờ AI vì sợ sai nghiệp vụ.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| AI có thực sự giải thích được lý do (Risk factors) tốt không? | AI Leverage & Trust | Nhấn mạnh việc xuất log và explainable rule thay vì blackbox. |
| Analyst bị phạt nếu sai, họ sẽ check lại hết. | Assumption về Trust | Giao diện phải cực kỳ minh bạch nguồn data. |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Tôi giữ nguyên các ý chính nhưng sẽ note lại cực kỳ kĩ về vấn đề Explainability (Khả năng giải thích của AI). Trust là thứ quyết định sống còn của dự án này.

### Version cuối cùng tôi nộp

**Job executor:**  
> Fraud Analyst / Risk Investigator.

**Core JTBD:**  
> Đánh giá mức độ rủi ro của một giao dịch đáng ngờ một cách chính xác trong quá trình rà soát hằng ngày.

**2 bước đau nhất trong workflow:**  
> Locate (gom nhặt dữ liệu phân mảnh) và Prepare (tổng hợp phân tích).

**AI leverage point chính:**  
> Hỗ trợ tổng hợp ngữ cảnh giao dịch và xuất ra điểm số rủi ro đi kèm với bằng chứng minh bạch ngay trên một màn hình review.

**Product hypothesis:**  
> Nếu giúp Analyst rút ngắn khâu Locate & Prepare bằng AI tổng hợp + Risk Score, họ sẽ bỏ qua việc tra soát thủ công vì tốc độ và độ tự tin tăng cao.

**Assumption cần validate đầu tiên:**  
> Khả năng giải thích của AI (Explainability) có đủ sức thuyết phục Analyst tin tưởng kết quả và ra quyết định hay không.

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.

### Bonus 2: Tư duy Data-driven & Validation
**Validation thực tế (Quick Interview với Senior Fraud Analyst):**
> *"Đau nhất không phải là lúc ra quyết định, mà là đi gom đủ data để dám ra cái quyết định đó. Có những case tôi phải mở tới 5 ứng dụng khác nhau: màn hình lịch sử giao dịch, IP/thiết bị, lịch sử ticket CSKH... Mất đến 15 phút chỉ để hiểu chuyện gì đang xảy ra. Nếu các bạn gom hết thành một màn hình tóm tắt duy nhất thì tuyệt vời."*
> 
> **->** Lời trích dẫn này đã trực tiếp **validate Job Story 2 (Locate context)** và chứng minh định lượng **mức độ đau đớn thực sự của khâu Locate** trong workflow. Nó củng cố cho việc RiskGuard AI đang nhắm đúng "tử huyệt" của công việc này.
