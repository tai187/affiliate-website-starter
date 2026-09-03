# BUILD TO OWN — CLAUDE PROJECT CONTEXT
## Dành cho Claude Code / AI Agent đồng hành cùng Nhung

> Mục đích của file này: cung cấp cho Claude bối cảnh khóa học Build to Own, bài Tuần 0 đã hoàn thành, vấn đề đã được Nhung chốt, nguyên tắc làm việc và trạng thái dự án hiện tại.
>
> Claude phải đọc file này trước khi đề xuất plan, spec, ticket hoặc bắt đầu build.

---

# 1. VAI TRÒ

## Nhung
- Là người quyết định cuối cùng.
- Là người duyệt problem, spec, architecture, ticket và output.
- Không cần trở thành lập trình viên.
- Phải hiểu AI đang làm gì, vì sao làm và kết quả nào được coi là xong.

## Claude
- Là AI Agent / đội thực thi.
- Không tự ý đổi vấn đề.
- Không tự ý mở rộng scope.
- Không bắt đầu build khi spec/ticket chưa được Nhung duyệt.
- Giải thích bằng tiếng Việt đơn giản.
- Khi cần Nhung bấm, đăng nhập, xác thực hoặc quyết định thì phải dừng và hướng dẫn từng bước.

---

# 2. THỨ TỰ ƯU TIÊN NGUỒN SỰ THẬT

Khi có mâu thuẫn, dùng thứ tự sau:

1. Đề bài chính thức trên Campus.
2. Transcript / tài liệu do giáo viên cung cấp.
3. Bài Tuần 0 đã được Nhung hoàn thành và duyệt.
4. Các quyết định mới Nhung xác nhận trong quá trình làm.
5. Đề xuất của Claude.

Claude không được biến đề xuất của mình thành “yêu cầu của khóa học”.

Nếu một nội dung không có trong nguồn khóa học, phải ghi rõ:
> “Đây là đề xuất của AI, không phải yêu cầu của giáo viên.”

---

# 3. KIẾN THỨC CỐT LÕI TỪ KHÓA BUILD TO OWN

## 3.1. Đi từ vấn đề thật trước
Khóa học nhấn mạnh:
- Bắt đầu từ vấn đề/nỗi đau thật của chính mình.
- Sau đó mới xác định build cái gì.
- Tiếp theo mới nghĩ về kiến trúc, công cụ và hệ thống.
- Code là bước sau cùng, không phải bước đầu.

Áp dụng cho dự án này:
> Không bắt đầu bằng “hãy code một website”.
> Phải đi theo: Problem → Spec → Architecture → Ticket → Build.

## 3.2. Buổi 1 và Buổi 2
- Buổi 1 trả lời: “Build cái gì?”
- Buổi 2 trả lời: “Làm ở đâu và làm với ai?”
- Buổi 2 tập trung vào workspace, repo, spec, architecture, Linear/ticket và API/MCP.

## 3.3. Học một thì làm hai
Thời gian thực hành nên ít nhất khoảng gấp đôi thời gian học.

## 3.4. Nhung là CEO, AI là đội thực thi
- Nhung không nhất thiết phải đọc code.
- Nhưng Nhung phải đọc và duyệt plan/spec.
- Spec và plan phải phản ánh đúng điều Nhung thật sự muốn.
- Nếu chưa hiểu hoặc chưa đồng ý, Claude phải dừng.
- Không được “bấm đồng ý cho nhanh”.

## 3.5. Dùng transcript làm context
Quy trình Buổi 2:
1. Ghi lại cuộc nói chuyện để có transcript đầy đủ.
2. Đưa transcript làm context, không gõ lại yêu cầu bằng tay.
3. Viết spec một trang.
4. Người dùng tự đọc và duyệt spec.
5. Đẩy spec lên Linear.
6. Chia spec thành ticket, gắn vai trò và ưu tiên.
7. Duyệt ticket rồi mới bắt đầu build.

## 3.6. API và MCP
Hiểu đơn giản theo bài học:
- AI cần ngữ cảnh/dữ liệu.
- API/MCP giúp AI truy cập dữ liệu từ công cụ thật.
- Nếu chỉ thao tác một lần, có thể làm tay.
- Nếu công việc lặp lại thường xuyên, nên xem công cụ có API/MCP để kết nối.
- Không kết nối nhiều công cụ cùng lúc khi chưa cần; bắt đầu bằng 1 công cụ thật đang dùng.

---

# 4. BÀI TUẦN 0 ĐÃ HOÀN THÀNH — BỐI CẢNH CÁ NHÂN

## 4.1. Hướng Affiliate hiện tại
Nhung đang bắt đầu làm Affiliate cho thị trường quốc tế.

Hướng ưu tiên:
- Website
- Nội dung
- SEO
- Lượt truy cập miễn phí

Nhung không muốn chỉ lấy một URL tạm để hoàn thành form Affiliate.

Nhung muốn:
- Có website riêng.
- Có domain riêng.
- Sử dụng lâu dài.
- Tự chủ hơn trong việc xây, sửa và phát triển website bằng AI.

Các công cụ Nhung đã dùng:
- ChatGPT
- Claude
- Claude Code
- WordPress
- Google
- Affiliate Skills

Khó khăn:
- Tiếng Anh còn hạn chế.
- Kỹ thuật còn hạn chế.
- Nhiều AI/skill nhưng quy trình còn rời rạc.

---

# 5. 10 CHỖ ĐAU ĐÃ XÁC ĐỊNH Ở TUẦN 0

1. Khi đăng ký một số Affiliate Program quốc tế, Nhung gặp yêu cầu URL website nhưng chưa có website riêng.
2. Nhung không muốn dùng URL của người khác hoặc một trang tạm chỉ để qua form đăng ký.
3. Muốn có website Affiliate riêng trên domain của mình nhưng chưa có quy trình rõ ràng để dùng AI tự xây từ đầu đến cuối.
4. Có nhiều AI và Affiliate Skills nhưng chưa biết phối hợp chúng thành một quy trình thống nhất.
5. Có nhiều website builder ngoài thị trường nhưng chưa biết cách kết hợp phần build website với nội dung, SEO và nhu cầu Affiliate của chính mình.
6. Làm thị trường quốc tế nhưng tiếng Anh còn hạn chế, mất nhiều thời gian đọc Terms/chính sách và kiểm tra nội dung.
7. Dùng AI research/viết nhưng chưa chắc thông tin nào đúng và phần nào cần xác minh thêm.
8. Chưa chắc nội dung AI có thật sự hữu ích hay chỉ là nội dung tổng hợp.
9. Chưa có bước kiểm tra cố định cho SEO, Affiliate Disclosure, Privacy và yêu cầu của từng chương trình trước khi xuất bản.
10. Đang học và dùng nhiều công cụ nên dễ lan man, cuối ngày chưa rõ đầu ra cụ thể.

---

# 6. 3 CHỖ ĐAU LỚN NHẤT

## Pain 1 — Chưa có website Affiliate riêng và chưa biết tự build bằng AI
Hiện trạng:
- Khi gặp yêu cầu URL ở form Affiliate, có thể điền tạm một URL.
- Nhưng cách đó chỉ giải quyết form trước mắt.
- Nhung vẫn chưa có website thật thuộc sở hữu của mình.
- Khi tự làm website, Nhung phải hỏi AI từng phần và ghép nhiều hướng dẫn.

Điều mong muốn:
> Đi từ chưa có website → có website trên domain của mình → có cấu trúc/nội dung cơ bản → kiểm tra → đưa lên Internet → tiếp tục phát triển.

## Pain 2 — Có nhiều AI và Affiliate Skills nhưng công việc vẫn rời rạc
Nhung chưa có một đường đi cố định:
> Hôm nay làm gì → dùng tool/skill nào → đầu ra gì → tiêu chuẩn hoàn thành → bước tiếp theo.

## Pain 3 — Không biết kết quả AI đã đủ đúng/an toàn để sử dụng chưa
Nhung thường:
> AI trả lời → hỏi AI khác → Google/nguồn chính thức → so sánh → tự quyết định.

Mong muốn có trạng thái:
- ĐÃ XÁC MINH
- CẦN KIỂM TRA THÊM
- KHÔNG NÊN SỬ DỤNG

---

# 7. VẤN ĐỀ ƯU TIÊN ĐÃ CHỐT

## Cách hiểu đúng
URL là điểm khiến Nhung phát hiện vấn đề.

Vấn đề sâu hơn không phải:
> “Tôi không biết điền URL gì.”

Vấn đề là:
> “Khi bắt đầu đăng ký Affiliate quốc tế, tôi gặp yêu cầu URL website nhưng chưa có website riêng. Tôi không muốn dùng URL tạm của người khác. Tôi muốn có website trên domain của chính mình để dùng lâu dài cho Affiliate.”

## Mô tả 3–5 câu đã chốt về mặt ý nghĩa
Khi bắt đầu đăng ký các chương trình Affiliate quốc tế, Nhung gặp trường hợp phải cung cấp URL website nhưng lúc đó chưa có website riêng. Trong quá trình học Affiliate, Nhung từng được hướng dẫn có thể điền tạm một URL để tiếp tục đăng ký, nhưng cách này chỉ xử lý tình huống trước mắt chứ chưa giải quyết nhu cầu lâu dài. Nhung muốn có một website trên domain của chính mình, do mình sở hữu, để sử dụng cho việc đăng ký chương trình, làm nội dung, SEO và phát triển Affiliate về sau. Hiện tại Nhung chưa có một quy trình rõ ràng giúp mình dùng AI để đi từ chưa có website đến website chạy thật trên Internet. Trước mắt Nhung muốn giải quyết vấn đề này cho chính mình trước.

---

# 8. ĐIỀU KHÔNG ĐƯỢC HIỂU SAI

Claude KHÔNG được diễn giải dự án thành:

> “Build một AI Website Builder mới để cạnh tranh Wix, WordPress, Hostinger, 10Web...”

Đây KHÔNG phải mục tiêu.

Mục tiêu đúng:
> Tận dụng các tool lớn đã có + AI Agent để xây một Affiliate Website Starter / quy trình riêng phục vụ công việc của Nhung.

Các tool có thể chỉ là “linh kiện”:
- Claude Code
- GitHub
- Vercel hoặc nền tảng deploy phù hợp
- Cloudflare/domain
- WordPress nếu dùng
- Affiliate Skills
- Linear
- API/MCP của một công cụ thật

---

# 9. GIẢ THUYẾT GIẢI PHÁP HIỆN TẠI

Tên làm việc:
> Affiliate Website Starter

Phiên bản đầu tiên dành cho:
> Nhung

Mục tiêu:
> Giúp Nhung từ chưa có website riêng → có website Affiliate chạy thật trên domain của mình → có thể tiếp tục tự chỉnh sửa bằng AI.

Đầu vào dự kiến:
- Ngách
- Thị trường mục tiêu
- Nhóm khách hàng
- Loại sản phẩm Affiliate
- Domain
- Mục tiêu website

Luồng dự kiến:
1. Nhập thông tin.
2. AI đề xuất cấu trúc.
3. Nhung duyệt.
4. AI build.
5. AI kiểm tra.
6. Nhung duyệt.
7. Deploy.
8. Gắn domain.
9. Website chạy thật.
10. Tiếp tục chỉnh sửa/phát triển.

---

# 10. SCOPE — CỐ TÌNH KHÔNG LÀM TRONG MVP ĐẦU

Phiên bản đầu KHÔNG:
1. Cạnh tranh với website builder tổng quát.
2. Tự động viết hàng trăm bài.
3. Làm SEO nâng cao đầy đủ.
4. Bảo đảm được mọi Affiliate Program duyệt.
5. Bảo đảm 100% tuân thủ mọi luật/chính sách quốc tế.
6. Tự động hóa toàn bộ Affiliate business.
7. Phục vụ mọi loại người dùng/ngách ngay từ đầu.

Nếu Claude đề xuất thêm các phần trên, phải đưa vào “Later / Phase 2”, không nhét vào MVP.

---

# 11. MỤC TIÊU HỌC TẬP CỦA NHUNG

Nhung không đặt mục tiêu trở thành lập trình viên.

Mục tiêu là học được quy trình:

> Mô tả yêu cầu → giao cho AI → đọc/duyệt plan → AI thực thi → kiểm tra → feedback → sửa → deploy → tiếp tục quản lý.

Sau khi giải quyết tốt cho chính mình:
- Dùng thật.
- Kiểm chứng thật.
- Ghi lại lỗi và bài học.
- Sau đó mới đánh giá có nên chuẩn hóa/mở rộng cho người khác không.

---

# 12. YÊU CẦU BUỔI 2 HIỆN TẠI

Buổi 2 chưa yêu cầu hoàn thành toàn bộ website.

Mục tiêu Buổi 2:
- Workspace Agent đọc được
- Repo GitHub rõ ràng
- Spec một trang
- Architecture nhìn được
- Linear + ticket
- 1 API/MCP kết nối thật
- Security an toàn

## Phần A — Bảo mật
- Cài 1Password.
- Bật CLI.
- Key lưu trong 1Password/vault theo dự án.
- `.env` nằm trong `.gitignore`.
- `.env.example` chỉ có tên biến.
- Không dán key vào chat.
- Không in key ra màn hình.
- Quét secret trước khi push.
- Key lộ thì rotate.

## Phần B — Repo
- Repo Private.
- Tên theo vấn đề thật.
- Tạo/push bằng Agent.
- Có README.
- Không secret trong commit.

## Phần C — spec.md đủ 7 mục
1. Vấn đề — một câu, có chủ thể và tần suất.
2. Người dùng — ai dùng, hiện đang làm gì thay thế.
3. Nó làm gì — 3–5 gạch đầu dòng, mỗi dòng một động từ.
4. KHÔNG làm — ít nhất 3 việc.
5. Dữ liệu — input/output/lưu ở đâu.
6. Xong là gì — kết quả kiểm tra được + deadline cụ thể.
7. Dễ hỏng ở đâu.

Mục 4 và 6 là quan trọng nhất.

Nhung phải tự đọc/sửa ít nhất 1 lượt.

## Phần D — Architecture
- Tạo HTML diagram.
- Có luồng chính.
- Có nhánh lỗi.
- Có điều kiện đi tiếp.
- Có luồng dữ liệu/xử lý.
- Nhung phải tự tìm ít nhất 1 lỗi/thiếu.
- Feedback.
- Agent vẽ lại.

## Phần E — Linear
- Có workspace.
- Spec đưa lên Linear.
- Ít nhất 5 ticket thật.
- Có role/người thực hiện.
- Có priority.
- Board tối thiểu 3 cột.

## Phần F — API/MCP
- Chọn đúng 1 công cụ Nhung đang thật sự dùng.
- Kiểm tra API hoặc MCP.
- Kết nối an toàn.
- Đặt 1 câu hỏi thật.
- Lấy dữ liệu thật.
- Không để lộ dữ liệu nhạy cảm.

---

# 13. QUY TẮC BẢO MẬT BẮT BUỘC

Claude tuyệt đối không:
- Yêu cầu Nhung dán API key/token/password vào chat.
- In secret ra terminal.
- Commit `.env`.
- Đưa giá trị thật vào `.env.example`.
- Push secret lên GitHub.
- Để dữ liệu nhạy cảm trong ảnh nộp bài.

Trước mỗi push phải kiểm tra:
- `.env` đã ignore chưa.
- `.env.example` chỉ có tên biến chưa.
- File tracked có secret không.
- Không in giá trị secret khi báo cáo.

Nếu nghi ngờ key từng lộ:
> DỪNG và yêu cầu rotate key.

---

# 14. CÁCH CLAUDE PHẢI BÁO CÁO SAU MỖI BƯỚC

Sau mỗi bước/ticket, trả theo mẫu:

## Đã làm gì
- ...

## File thay đổi
- ...

## Nhung cần kiểm tra
- ...

## Rủi ro / điều chưa chắc
- ...

## Có thể sang bước tiếp theo chưa?
- CÓ / CHƯA
- Lý do

Nếu cần quyết định của Nhung:
> DỪNG và hỏi đúng 1 quyết định cần thiết.

---

# 15. LỆNH KHỞI ĐỘNG CHO CLAUDE

Sau khi đọc file này, Claude phải:

1. Tóm tắt vấn đề của Nhung trong tối đa 5 câu.
2. Nói rõ đâu là:
   - vấn đề,
   - mục tiêu,
   - giả thuyết giải pháp,
   - phần KHÔNG làm.
3. Kiểm tra workspace hiện tại.
4. Không build website ngay.
5. Bắt đầu theo đúng bài Buổi 2 từ Phần A — Bảo mật.
6. Đề xuất plan Phần A.
7. DỪNG để Nhung duyệt.

Không thay đổi file hay chạy lệnh nhạy cảm trước khi Nhung duyệt plan.
