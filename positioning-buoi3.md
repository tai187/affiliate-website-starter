# Positioning — Buổi 3 (futuretoolsbase.com)

> Hợp nhất Bài tập 1 (market research) và Bài tập 2 (định vị sản phẩm) của Buổi 3
> vào một chỗ trong repo, thay vì nằm rời trong docx nộp riêng. Không thay thế
> `market-positioning-matrix.html` (bản đầy đủ, có bằng chứng teardown 10 site) —
> file này tóm tắt lại phần kết luận + phần ICP/USP/giá chưa có trong matrix.

## 1. Market research — tóm tắt

Ngách: AI Video Tools, 4 nhóm ưu tiên — AI Video Generator, AI Avatar /
Talking-Head, AI UGC / Ad Creator, Text-to-Video / Social Video.

- TAM ~US$450M/năm, SAM ~US$22.5M/năm (4 nhóm ưu tiên, phù hợp organic SEO),
  SOM ~US$11.25K/năm (mức một website mới có thể hướng tới nếu xây được
  traffic + conversion). Đây là ước tính định hướng, không phải forecast
  doanh thu.
- Teardown đầy đủ 10 site (giá đối chiếu trực tiếp, độ tin cậy HIGH/MEDIUM/LOW
  theo từng site) và bảng ma trận khoảng trống thị trường nằm ở
  [`market-positioning-matrix.html`](./market-positioning-matrix.html) — xem
  file đó để có bằng chứng chi tiết, không lặp lại ở đây.
- Kết luận market gap (v3, đã có bằng chứng trực tiếp): không site nào trong
  10 site đạt đồng thời độ chuyên biệt theo use case cao (Y≥4) và độ minh
  bạch/bằng chứng cao (X≥4) ở đúng định dạng "bài viết + giá xác minh + rubric
  công khai". 2/10 site bị bắt quả tang giá sai khi đối chiếu trực tiếp với
  trang giá chính hãng (theskillshift.com, Vidmetoo.com).

## 2. ICP — Khách hàng mục tiêu

Content creator, solo marketer và SMB nói tiếng Anh đang cần chọn một AI
Video Tool phù hợp nhưng không có thời gian hoặc ngân sách để tự test hàng
loạt công cụ. Use case chính: marketer/e-commerce cần UGC ads, creator cần AI
avatar, blogger/agency chuyển bài viết thành video, người làm marketing cần
video social nhanh, người cần so giá/giới hạn trước khi mua.

Truy vấn họ hay tìm: "best AI video tool for X", "Tool A vs Tool B", "Tool
pricing", "best AI UGC tool", "best AI avatar for…".

## 3. USP — Điểm khác biệt thử nghiệm

> AI tool reviews theo use case, có bằng chứng test thật khi có thể, pricing
> được kiểm từ nguồn chính thức, disclosure minh bạch và methodology nhất
> quán.

Nguyên tắc chính (map trực tiếp sang 9 tính năng trong
[`content-format-spec.md`](./content-format-spec.md)):

1. Review theo nhu cầu thật, không chỉ danh sách Top 10.
2. Giá lấy từ nguồn chính thức, ghi ngày kiểm tra.
3. Nói "đã test" thì phải có evidence; chưa test thì nói rõ chưa test.
4. Có phần "phù hợp với ai / không phù hợp với ai".
5. Không giấu nhược điểm hoặc complaint.
6. Affiliate relationship phải được disclosure rõ.
7. Editorial policy phải khớp với cách bài thật được làm.

## 4. Mô hình doanh thu / Giá dự kiến

Không bán sản phẩm trực tiếp — doanh thu đến từ affiliate commission khi
người đọc đăng ký/mua công cụ qua link giới thiệu. "Giá dự kiến" ở đây là mức
hoa hồng kỳ vọng theo từng chương trình, dùng để cân nhắc thứ tự ưu tiên viết
review (không phải tiêu chí chọn tool để review — tiêu chí đó vẫn là sản phẩm
thật sự hữu ích, có nhu cầu mua thật, chính sách affiliate rõ).

Mức hoa hồng đã xác minh trực tiếp từ trang chính thức từng chương trình
(kiểm 15/09/2026):

| Công cụ | Nhóm | Hoa hồng | Điều kiện / cookie | Nguồn |
|---|---|---|---|---|
| HeyGen | AI Avatar | 35% | 3 tháng đầu, cookie 30 ngày, tối thiểu $30 để rút, trả qua PayPal | heygen.com/en-in/affiliate-program |
| Synthesia | AI Avatar | 25% | Gói Starter/Creator, cookie 60 ngày | synthesia.io/partners/affiliates |
| Creatify | AI UGC/Ad Creator | 25% | Định kỳ (recurring), +5% nếu doanh số tháng qua $5.000 | creatify.ai/affiliate |
| InVideo AI | Text-to-Video | 50% / 25% | 50% gói tháng, 25% gói năm, không giới hạn số lượng, trả sau ~42–45 ngày | invideo.io/make/affiliate-program |
| Pictory | Text-to-Video | Tới 50% | Định kỳ + thưởng $1.000 tiền mặt cho khách trả phí đầu tiên | pictory.ai/partnernow |
| Runway | AI Video Generator | $15/subscriber | Cố định (không theo %), không giới hạn, trả qua Stripe đầu mỗi tháng | runway.com/affiliate-program |

Ghi chú: Kling, Luma, Pika, Sora, Veo, D-ID, Colossyan, Elai, Arcads,
CreatorKit, Fliki, Synthesys — chưa tìm được trang chương trình affiliate
chính thức khi kiểm (chỉ có trang tổng hợp bên thứ ba, chưa đủ tin cậy theo
tiêu chuẩn "nguồn chính thức" của dự án này). Cần xác minh trực tiếp trước
khi đưa các tool này vào bài review có gắn affiliate link.

## 5. Còn thiếu / chưa làm ở Buổi 3

- Bài tập 3 (bổ trợ) — tự viết Skill/Mini App riêng và đưa lên GitHub: chưa
  làm. 3 skill đang dùng (`bto-teardown`, `bto-researchmarket`,
  `bto-secrets`) là của giảng viên Sơn Piaz (clone từ
  github.com/sonpiaz/bto-skills), không tính là tự viết. Đây là phần khuyến
  khích, không bắt buộc để đạt điểm.
