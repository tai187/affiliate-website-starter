# SPEC.md — Content & Format System cho futuretoolsbase.com (bản nháp v2, chưa duyệt)

> Viết theo Bước 3 của skill `bto-teardown`: đặc tả sạch (clean-room) rút ra từ
> việc phân rã 5 trang affiliate/review AI tool (llm-stats.com Video Arena,
> Theoretically Media, Vidmetoo.com, AIToolRanked.com, theskillshift.com).
> Đây là đặc tả **hành vi mong muốn**, viết lại bằng lời của tôi — không sao
> chép code, giao diện, hay câu chữ của bất kỳ trang nào trong 5 trang trên.
> **Chưa build gì, chưa tạo ticket, chưa đụng vào website.** File này là để
> duyệt, không phải để thi hành ngay.
>
> Quan hệ với `spec.md` gốc: đây vẫn là đặc tả cho phần "quy trình sản xuất
> nội dung/review" — một lớp con nằm dưới mục "viết nội dung cho 4 nhóm ưu
> tiên" đã có trong `spec.md`. **Không thay thế `spec.md`, không đổi hướng đi
> hiện tại của futuretoolsbase.com.** Chỉ khi được duyệt riêng, nội dung này
> mới nên hợp nhất vào `spec.md` hoặc trở thành phụ lục.
>
> **v2 — bản sửa sau khi Nhung review bản v1**, thu hẹp phạm vi rubric chấm
> điểm, đơn giản hóa nhật ký sửa bài, viết lại "Done means" theo hệ thống
> nội dung thật thay vì chỉ theo bài kiểm spec bằng agent. Xem mục cuối cùng
> "Các thay đổi trong bản sửa này" để biết chính xác đã đổi gì.

## 0. Vấn đề (Problem)

Từ market research + teardown: mọi trang cạnh tranh đều thiếu ít nhất 1 trong
3 trụ cột — (a) bằng chứng test thật nhất quán cho mọi bài, (b) rubric chấm
điểm công khai, (c) đúng phủ nhóm AI avatar/UGC/ad-creator. Không trang nào
mạnh cả 3 cùng lúc. Nếu futuretoolsbase.com viết nội dung theo đúng kiểu
template phổ biến (liệt kê + pros/cons + bảng giá không rubric), sẽ chỉ là
bản sao thêm 1 cái vào một thị trường đã bão hòa (agent research: "clones of
clones", tự thú bởi chính người vận hành directory khác).

## 1. Người dùng (User)

Độc giả futuretoolsbase.com: người mới-đến-trung cấp làm affiliate/content
marketing quốc tế, ưu tiên Mỹ, đang chọn 1 tool trong 4 nhóm AI Tools ưu tiên
(video generator, avatar, UGC/ad creator, text-to-video) để dùng thật, không
phải người đọc cho vui.

## 2. Solution hypothesis

Một **hệ thống xuất bản có cổng kiểm (publishing gate)** — không phải một bài
viết đơn lẻ hay hơn, mà một quy trình bắt buộc mọi bài phải đi qua trước khi
đăng, để không lặp lại đúng lỗi "chính sách nói một đằng, bài viết làm một
nẻo" đã thấy ở AIToolRanked.com.

### 2.1 Ưu tiên MVP quan trọng nhất

Theo yêu cầu review, đây là danh sách ưu tiên phải giữ nguyên trong bản sửa
này — mỗi mục map tới đúng 1 tính năng bên dưới:

1. Danh tính tác giả rõ ràng — Tính năng 8
2. Công bố affiliate rõ ràng — Tính năng 1
3. Nguồn giá đã xác minh — Tính năng 2
4. Ngày kiểm tra lần cuối — Tính năng 2 và Tính năng 7
5. Gắn nhãn trung thực về mức độ bằng chứng — Tính năng 3
6. Bằng chứng test thật khi có thể làm được — Tính năng 3
7. Phương pháp đánh giá nhất quán — Tính năng 4 và mẫu review chuẩn (Done means)
8. Nói rõ "phù hợp với ai / không phù hợp với ai" — Tính năng 9
9. Editorial policy khớp đúng với thực tế đang làm — Tính năng 6

---

## Tính năng 1 — Khối Affiliate Disclosure

- **Người dùng nhận được gì:** một câu công bố ngắn, rõ ràng, đặt ngay đầu
  bài, trước mọi nội dung thuyết phục.
- **Kích hoạt bằng gì:** bài viết có ít nhất 1 link affiliate.
- **Vào / ra:** Vào — biên tập viên đánh dấu bài có affiliate link hay không.
  Ra — khối disclosure render tự động ngay dưới tiêu đề.
- **Trạng thái:** (a) có affiliate link → hiển thị disclosure; (b) bài thuần
  biên tập không có affiliate link nào → không hiển thị, nhưng phải có lý do
  ghi lại tại sao bài này không gắn affiliate (hiếm, ví dụ: tool chưa có
  affiliate program — xem Tính năng 5).
- **Lỗi thì sao:** bài có affiliate link mà thiếu khối disclosure → **chặn
  publish**, không phải "nhắc rồi cho qua".
- **KHÔNG làm:** không tự động phát hiện link nào là affiliate bằng máy — ở
  giai đoạn này việc đánh dấu là thủ công, do biên tập viên tự khai khi viết.

## Tính năng 2 — Bảng giá có nguồn chính thức + "Ngày kiểm tra lần cuối"

- **Người dùng nhận được gì:** giá hiển thị trên trang, kèm nguồn (link tới
  trang giá chính thức của hãng) và ngày biên tập viên tự tay xác nhận lại.
- **Kích hoạt bằng gì:** bất kỳ bảng giá nào xuất hiện trong bài.
- **Vào / ra:** Vào — biên tập viên copy số giá + link nguồn + ngày kiểm từ
  trang chính hãng. Ra — bảng hiển thị kèm dòng "Nguồn: [link hãng] — Đã kiểm
  ngày: [ngày]".
- **Trạng thái:** (a) mới kiểm trong 30 ngày → hiển thị bình thường; (b) quá
  90 ngày chưa kiểm lại → gắn cờ cảnh báo "giá có thể đã đổi, xem trực tiếp
  tại [link hãng]" thay vì lặng lẽ để số cũ đứng đó.
- **Lỗi thì sao:** không ghi được nguồn/ngày kiểm (ví dụ hãng không có trang
  giá công khai) → không được hiển thị số cụ thể, chỉ ghi "liên hệ hãng để
  biết giá hiện tại".
- **KHÔNG làm:** không tự động cào (scrape) giá theo lịch — đây là thao tác
  thủ công định kỳ ở giai đoạn MVP, không phải hệ thống tự động như
  theskillshift.com (học bài học: hệ thống tự động của họ vẫn bị lỗi thời,
  team nhỏ mới bắt đầu không nên tự tin làm tự động ngay). Cũng không làm dự
  báo giá (price forecasting).

## Tính năng 3 — Cổng "Bằng chứng thực tế" (Hands-on Evidence Gate)

- **Người dùng nhận được gì:** với mỗi tool được review đầy đủ, ít nhất 1
  ảnh chụp màn hình hoặc 1 đoạn output tự tạo (không phải video demo của
  hãng), kèm 1 con số cụ thể (thời gian tạo, độ dài, v.v.) và 1 câu nhận xét
  không chỉ toàn khen.
- **Kích hoạt bằng gì:** bài được gắn nhãn "Đã test thật".
- **Vào / ra:** Vào — biên tập viên tự tạo output bằng chính tool. Ra — khối
  bằng chứng nhúng trong bài, không thay bằng ảnh/video của hãng.
- **Trạng thái:** (a) đã test thật → gắn nhãn "Đã test thật" + hiển thị bằng
  chứng; (b) chưa test được (ví dụ tool mới ra, chưa kịp dùng) → **bắt buộc**
  gắn nhãn "Chưa tự test — tổng hợp từ tài liệu công khai của hãng", và
  **không được cho điểm số** ở Tính năng 4 cho tool đó.
- **Lỗi thì sao:** bài gắn nhãn "Đã test thật" nhưng không có bằng chứng đính
  kèm → chặn publish. Đây là quy tắc trực tiếp học từ lỗi của Kling AI review
  trên AIToolRanked.com (tiêu đề ghi "hands-on benchmarks" nhưng nội dung tự
  thú không có dữ liệu thật).
- **KHÔNG làm:** không bắt buộc mọi bài phải test thật ngay từ ngày đầu —
  chấp nhận trạng thái (b), miễn là nói thật về nó.

## Tính năng 4 — Rubric chấm điểm thử nghiệm (CHỈ 1 rubric, phạm vi MVP đã thu hẹp)

> **Đây là thay đổi lớn nhất so với bản v1** — bản v1 đề xuất 4 rubric riêng
> cho 4 nhóm ngay từ đầu, review yêu cầu thu hẹp lại chỉ còn 1 rubric.

- **Người dùng nhận được gì:** một điểm số/xếp hạng có thể tra lại được cách
  tính, nhưng **chỉ áp dụng cho đúng 1 nhóm ưu tiên đầu tiên** — theo thứ tự
  liệt kê trong `spec.md` gốc, nhóm đó là **AI video generator**. *(Giả định
  này cần Nhung xác nhận lại — nếu muốn thử nghiệm ở nhóm khác trước, chỉ cần
  đổi tên nhóm ở đây, phần còn lại của tính năng không đổi.)*
- **Kích hoạt bằng gì:** bài review nằm trong đúng nhóm ưu tiên đầu tiên nói
  trên. 3 nhóm còn lại (AI avatar, AI UGC/ad creator, text-to-video) **chưa
  có rubric** — review ở 3 nhóm này dùng đánh giá định tính (pros/cons, "phù
  hợp với ai") theo Tính năng 3 và Tính năng 9, không cho điểm số.
- **Vào / ra:** Vào — biên tập viên điền từng tiêu chí con theo đúng 1 rubric
  thử nghiệm này. Ra — điểm tổng + breakdown từng tiêu chí, có link tới trang
  giải thích cách tính rubric.
- **Trạng thái:** (a) **giai đoạn thử nghiệm** — áp dụng cho 3–5 bài review
  thật đầu tiên trong nhóm ưu tiên đầu tiên; (b) **sau khi có đủ 3–5 bài thật
  dùng rubric này** → Nhung tự đánh giá rubric có thực sự giúp phân biệt các
  tool hay không, rồi mới quyết định có mở rộng sang 3 nhóm còn lại hay sửa
  lại rubric trước khi mở rộng. Không tự động mở rộng nếu chưa qua bước đánh
  giá này.
- **Lỗi thì sao:** nếu nhiều tool liên tiếp trong nhóm này ra cùng 1 điểm số
  (ví dụ toàn 9/10) → đây là tín hiệu rubric đang bị dùng hời hợt hoặc bản
  thân rubric có vấn đề, cần dừng lại xem lại rubric trước khi viết thêm bài
  mới dùng nó.
- **KHÔNG làm:** **không xây đủ 4 rubric cho cả 4 nhóm trong MVP.** Không cần
  cơ chế bình chọn cộng đồng/mù kiểu llm-stats.com — không khả thi khi site
  chưa có traffic. Không xây công cụ so sánh tương tác quy mô lớn (large
  interactive comparison engine).

## Tính năng 5 — Gắn nhãn "Có/Không có Affiliate Program"

- **Người dùng nhận được gì:** biết ngay tool này futuretoolsbase.com có kiếm
  hoa hồng khi họ mua hay không — minh bạch động cơ tài chính đằng sau bài.
- **Kích hoạt bằng gì:** mọi bài review/so sánh tool.
- **Vào / ra:** Vào — biên tập viên kiểm tra trang affiliate program chính
  thức của hãng (nếu có). Ra — nhãn hiển thị: "Có chương trình affiliate
  công khai" / "Chỉ mời (invite-only)" / "Không có chương trình affiliate".
- **Trạng thái:** như đã xác nhận ở market research trước — Sora, Veo, Luma
  hiện không có/không rõ chương trình affiliate; Kling chỉ mời. Các bài về
  3 tool này vẫn có thể viết (vì nhu cầu tìm kiếm cao) nhưng phải gắn nhãn rõ
  và không giả vờ có link kiếm tiền nếu không có.
- **Lỗi thì sao:** gắn nhãn "Có chương trình affiliate" mà không kiểm tra
  trực tiếp trang chính thức của hãng → coi là lỗi dữ kiện, phải sửa.
- **KHÔNG làm:** không đảm bảo tình trạng affiliate program này còn đúng mãi
  mãi — cần cơ chế kiểm lại định kỳ giống Tính năng 2.

## Tính năng 6 — Trang Editorial Policy (chỉ hứa điều thực thi được)

- **Người dùng nhận được gì:** một trang giải thích rõ cách futuretoolsbase.com
  làm review, đặt ở vị trí dễ tìm (không chỉ nằm trong menu phụ như
  AIToolRanked.com), và mọi điều khoản trong đó đều có thể kiểm chứng được ở
  các bài viết thật.
- **Kích hoạt bằng gì:** có mặt cố định trên mọi trang (nav chính, không phải
  footer ẩn).
- **Vào / ra:** Vào — mỗi điều khoản trong policy phải map 1-1 tới 1 mục
  trong checklist xuất bản (Tính năng 1-5, 7-9). Ra — trang policy công khai.
- **Trạng thái:** mỗi điều khoản trong policy có đúng 2 trạng thái được phép:
  "đang thực thi ở mọi bài" hoặc "chưa làm — không được viết trong policy".
  Không có trạng thái "sẽ làm sau" nằm trong policy đang publish. Với rubric
  (Tính năng 4), policy phải nói rõ đây là "đang thử nghiệm ở 1 nhóm", không
  được viết như thể đã áp dụng cho cả 4 nhóm.
- **Lỗi thì sao:** phát hiện 1 bài không tuân theo điều đã hứa trong policy
  → phải sửa bài HOẶC sửa policy, không được để cả hai đứng yên mâu thuẫn
  nhau (đây là lỗi trực tiếp học từ AIToolRanked.com).
- **KHÔNG làm:** không copy nguyên văn cấu trúc/câu chữ của bất kỳ trang
  editorial policy nào đã teardown — chỉ học ý tưởng cấu trúc.

## Tính năng 7 — Ngày cập nhật + ghi chú khi sửa lớn (đã đơn giản hóa)

> **Thay đổi so với v1:** bỏ ý tưởng "nhật ký chi tiết mọi lần sửa" — chỉ giữ
> lại 2 việc đơn giản: luôn có ngày cập nhật, và chỉ khi sửa lớn mới cần thêm
> 1 câu ghi chú công khai.

- **Người dùng nhận được gì:** luôn thấy dòng "Lần cập nhật gần nhất: [ngày]"
  trên mọi bài; riêng khi có thay đổi quan trọng (giá đổi, kết luận/khuyến
  nghị đổi, thông tin sai đã được sửa) thì có thêm 1 câu ghi chú ngắn, công
  khai, giải thích đã sửa gì.
- **Kích hoạt bằng gì:** mọi lần chỉnh sửa bài sau khi đã publish.
- **Vào / ra:** Vào — biên tập viên cập nhật ngày mỗi lần sửa bất kỳ (nhỏ hay
  lớn đều cập nhật ngày). Nếu là sửa lớn, thêm 1 câu ghi chú ngắn. Ra — ngày
  hiển thị luôn ở đầu bài; ghi chú sửa lớn chỉ hiện khi có, không hiện ô
  trống nếu chưa từng sửa lớn.
- **Trạng thái:** (a) sửa nhỏ (chính tả, làm rõ câu chữ, không đổi thông tin
  sự kiện) → chỉ cập nhật ngày, không cần ghi chú; (b) sửa lớn (giá thay đổi,
  kết luận đổi, sửa thông tin sai) → cập nhật ngày **và** thêm 1 câu ghi chú
  ngắn (ví dụ: "12/09/2026: sửa giá gói Pro từ $99 xuống $49 sau khi kiểm lại
  trang chính hãng").
- **Lỗi thì sao:** sửa lớn mà không có câu ghi chú đi kèm → coi là vi phạm
  Tính năng 6 (policy hứa minh bạch mà không thực thi).
- **KHÔNG làm:** không cần nhật ký chi tiết từng lần sửa nhỏ; không cần hệ
  thống version control; không cần giao diện xem lịch sử phức tạp. Đây là 1
  dòng ngày + (đôi khi) 1 câu ghi chú, không hơn.

## Tính năng 8 — Danh tính tác giả rõ ràng (mới, theo yêu cầu review)

- **Người dùng nhận được gì:** biết ai đang viết bài này — tên thật, không
  phải byline kiểu "Đội ngũ [Tên site]" chung chung.
- **Kích hoạt bằng gì:** mọi bài review/so sánh có gắn điểm số hoặc khuyến
  nghị mua/không mua.
- **Vào / ra:** Vào — tên tác giả thật gắn với bài viết. Ra — hiển thị tên
  tác giả gần đầu bài (cùng khu vực với ngày cập nhật ở Tính năng 7).
- **Trạng thái:** MVP chỉ cần tên tác giả hiển thị nhất quán; phần tiểu sử/
  uy tín chi tiết (kiểu Theoretically Media) có thể bổ sung sau, không bắt
  buộc ngay ở MVP.
- **Lỗi thì sao:** bài đăng thiếu tên tác giả → chặn publish.
- **KHÔNG làm:** không bắt buộc phải có trang tiểu sử tác giả đầy đủ ngay từ
  bài đầu tiên — chỉ cần tên thật xuất hiện nhất quán.

## Tính năng 9 — "Phù hợp với ai / Không phù hợp với ai" (mới, theo yêu cầu review)

- **Người dùng nhận được gì:** một đoạn ngắn, rõ ràng, nói thẳng tool này hợp
  với ai và KHÔNG hợp với ai — không chỉ liệt kê tính năng chung chung.
- **Kích hoạt bằng gì:** mọi bài review đầy đủ về 1 tool.
- **Vào / ra:** Vào — biên tập viên tự trả lời 2 câu hỏi khi viết: "Ai nên
  dùng tool này?" và "Ai không nên dùng tool này?". Ra — 2 đoạn ngắn tương
  ứng, đặt gần phần kết luận của bài.
- **Trạng thái:** bắt buộc có cả 2 chiều (hợp với ai VÀ không hợp với ai) —
  chỉ viết 1 chiều (toàn khen) không được coi là đạt.
- **Lỗi thì sao:** bài chỉ có "phù hợp với ai" mà thiếu "không phù hợp với
  ai" → chặn publish, vì đây là dấu hiệu bài thiên về quảng cáo hơn là đánh
  giá thật.
- **KHÔNG làm:** không cần bảng phân khúc khách hàng phức tạp — chỉ cần 2
  đoạn văn ngắn, viết tay, cụ thể.

---

## 3. Việc này KHÔNG làm (DOES NOT do — chung cho cả spec)

- Không xây cơ chế bình chọn cộng đồng (community voting) hay bình chọn mù
  (blind voting) — học từ llm-stats.com, cần traffic có sẵn mới khả thi.
- Không theo dõi giá tự động bằng scraper (automated pricing scraping) — học
  từ theskillshift.com, team nhỏ mới bắt đầu tự động hóa sẽ tạo dữ liệu lỗi
  thời mà không biết.
- Không làm dự báo giá (price forecasting).
- Không mở rộng theo dõi hàng trăm tool (testing hundreds of tools) — chỉ
  giới hạn đúng danh sách tool đã xác định trong 4 nhóm ưu tiên (`spec.md`
  gốc), khoảng 15–20 tool.
- Không xây công cụ so sánh tương tác quy mô lớn (large interactive
  comparison engine).
- Không làm tự động hóa nâng cao (advanced automation) ngoài các quy tắc thủ
  công đã nêu ở trên (đánh dấu affiliate, kiểm giá, viết ghi chú sửa lớn đều
  do người làm tay ở MVP).
- **Không xây đủ 4 rubric chấm điểm cho cả 4 nhóm trong giai đoạn MVP** — chỉ
  1 rubric thử nghiệm cho nhóm ưu tiên đầu tiên (xem Tính năng 4).
- Không tự nhận đã kiểm tra affiliate program của MỌI tool trên thị trường —
  chỉ những tool thực sự được viết bài.
- Không tạo phim ngắn/sản phẩm sáng tạo minh chứng kiểu Theoretically Media
  (đòi hỏi kỹ năng làm phim chuyên nghiệp, ngoài phạm vi MVP).
- Không tự động hóa việc phát hiện/gắn nhãn affiliate link bằng máy.
- Không thay đổi `spec.md` gốc hay phạm vi MVP (4 nhóm nội dung, 6 trang cơ
  bản) đã duyệt trước đó — đây chỉ là lớp quy trình biên tập bổ sung, và sẽ
  không được hợp nhất vào `spec.md` gốc nếu chưa được Nhung duyệt riêng.

## 4. Coi là "xong" khi nào (Done means)

MVP của lớp quy trình này được coi là "xong" khi **hệ thống nội dung thật sự
chạy được**, không chỉ khi spec đọc xuôi tai trên giấy:

- [ ] Có 1 checklist xuất bản đã được duyệt, gộp đủ Tính năng 1–9.
- [ ] Có 1 mẫu (template) review chuẩn, dùng chung cho mọi bài.
- [ ] Có ít nhất **3 bài review thật** đã đi qua checklist và được đăng.
- [ ] Mỗi bài review có nguồn giá chính thức (link) + ngày kiểm tra lần cuối.
- [ ] Bài nào có link affiliate đều có khối công bố affiliate rõ ràng.
- [ ] Bài nào ghi "đã test thật" đều có bằng chứng thật đi kèm (ảnh/output +
      con số cụ thể).
- [ ] Bài nào chưa test thật đều được gắn nhãn rõ ràng là chưa test.
- [ ] Có **1 rubric chấm điểm thử nghiệm** cho đúng 1 nhóm ưu tiên đầu tiên
      (không phải cả 4 nhóm).
- [ ] Người đọc, chỉ cần đọc 1 bài, có thể hiểu rõ:
  - tool này phù hợp với ai,
  - tool này không phù hợp với ai,
  - giá hiện tại là bao nhiêu,
  - giới hạn chính của tool là gì,
  - mức độ bằng chứng của bài (đã test thật hay chỉ tổng hợp tài liệu),
  - futuretoolsbase.com có kiếm hoa hồng từ tool này hay không.

*(Bài kiểm bằng agent mới của bản v1 — dán spec vào phiên agent mới, bảo
build thử 1 tính năng, xem agent có hỏi lại về hành vi hay không — vẫn là
một cách hữu ích để kiểm spec có đủ chi tiết chưa, nhưng không còn là tiêu
chí "xong" duy nhất. Danh sách checklist thật ở trên mới là thước đo chính.)*

## 5. Nơi có thể vỡ (Where it can break)

- Viết checklist ra nhưng không có cơ chế thật sự chặn được việc publish khi
  thiếu mục nào đó → rơi lại đúng lỗi AIToolRanked.com (chính sách và thực tế
  lệch nhau).
- Rubric thử nghiệm ở Tính năng 4 bị dùng qua loa ngay từ 3–5 bài đầu, nhiều
  tool ra cùng điểm số → mất giá trị làm rubric ngay từ đầu, và quyết định mở
  rộng sang nhóm khác sẽ dựa trên dữ liệu không đáng tin.
- Không có ai thực sự đi kiểm lại giá định kỳ (Tính năng 2) → cờ cảnh báo
  không bao giờ được set, giá cũ đứng mãi mãi giống lỗi đã thấy ở Vidmetoo.com
  và theskillshift.com.
- "Sửa lớn" và "sửa nhỏ" ở Tính năng 7 không có ranh giới rõ, biên tập viên
  tự ý xếp mọi thứ vào "sửa nhỏ" để khỏi phải viết ghi chú → quay lại đúng
  vấn đề minh bạch mà tính năng này định giải quyết.
- Cố gắng làm bằng chứng thực tế (Tính năng 3) cho tất cả 15–20 tool cùng lúc
  ngay từ đầu có thể quá tải nguồn lực một người — cần ưu tiên tool nào trước
  (gợi ý: bắt đầu từ đúng 3–5 tool sẽ dùng để thử rubric ở Tính năng 4).

---

## Các thay đổi trong bản sửa này (so với bản v1)

1. **Thu hẹp Tính năng 4 (rubric chấm điểm):** từ "4 rubric riêng cho 4
   nhóm ngay từ đầu" → còn **1 rubric thử nghiệm duy nhất**, áp dụng cho
   nhóm ưu tiên đầu tiên (giả định: AI video generator, cần Nhung xác nhận),
   thử trên 3–5 bài thật, rồi mới quyết có mở rộng hay không. Đã thêm ghi rõ
   việc này vào mục 3 (KHÔNG làm) và mục 4 (Done means).
2. **Đơn giản hóa Tính năng 7 (trước gọi là "Correction Log"):** bỏ ý tưởng
   nhật ký chi tiết mọi lần sửa; giữ lại "ngày cập nhật lần cuối" luôn hiển
   thị + 1 câu ghi chú ngắn công khai chỉ khi có sửa lớn. Không cần hệ thống
   version control hay giao diện lịch sử.
3. **Viết lại mục 4 (Done means):** từ "chỉ cần agent mới hiểu spec là đủ" →
   một checklist cụ thể dựa trên hệ thống nội dung thật đã chạy (ít nhất 3
   bài thật qua checklist, có nguồn giá + ngày kiểm, có rubric thử nghiệm 1
   nhóm, người đọc hiểu đủ 6 điều cụ thể). Bài kiểm bằng agent mới của v1 vẫn
   giữ lại nhưng chỉ là tham khảo phụ, không phải tiêu chí "xong" chính.
4. **Thêm Tính năng 8 (Danh tính tác giả rõ ràng)** và **Tính năng 9 ("Phù
   hợp với ai / Không phù hợp với ai")** — hai mục này có trong yêu cầu ưu
   tiên MVP nhưng chưa có ở bản v1, nay được viết thành 2 tính năng riêng
   theo đúng khung (kích hoạt / vào-ra / trạng thái / lỗi / không làm).
5. **Thêm mục 2.1 (Ưu tiên MVP quan trọng nhất)** — liệt kê 9 ưu tiên theo
   đúng yêu cầu review, mỗi ưu tiên map rõ tới 1 tính năng cụ thể trong spec.
6. **Bổ sung rõ vào mục 3 (KHÔNG làm)** các mục còn thiếu ở v1: dự báo giá
   (price forecasting), công cụ so sánh tương tác quy mô lớn (large
   interactive comparison engine), tự động hóa nâng cao (advanced
   automation) — theo đúng danh sách loại trừ trong yêu cầu review.
7. Không có thay đổi nào ở Tính năng 1, 2, 3, 5, 6 (nội dung giữ nguyên như
   bản v1, chỉ thêm tham chiếu chéo tới các tính năng mới ở Tính năng 6).
8. Không đụng đến `spec.md` gốc, không tạo ticket, không build hay chỉnh sửa
   website — đúng theo yêu cầu review.
