# Spec — Affiliate Website Starter (futuretoolsbase.com)

## 1. Problem
Khi bắt đầu đăng ký các chương trình Affiliate quốc tế, Nhung gặp trường hợp phải cung cấp URL website nhưng chưa có website hoàn chỉnh, đủ nội dung và đáng tin cậy thuộc sở hữu của mình để sử dụng lâu dài. Nhung đã đăng ký domain và dựng bản nháp WordPress (futuretoolsbase.com) nhưng chưa hoàn thiện cấu trúc, nội dung, bảo mật và tốc độ để dùng chính thức cho hồ sơ Affiliate.

## 2. User
- Người dùng: Nhung (phiên bản MVP đầu tiên, chưa mở rộng cho người khác).
- Hiện đang làm gì thay thế: điền tạm một URL không thuộc sở hữu của mình để qua được form đăng ký Affiliate, không giải quyết nhu cầu website riêng lâu dài.

## 3. What it does
- Thu thập thông tin đầu vào từ Nhung (ngách AI Tools, nhóm ưu tiên ban đầu, thị trường mục tiêu, domain, ngôn ngữ, mục tiêu website).
- Research và xác nhận phạm vi ngách/nhóm sản phẩm/Affiliate Program bằng Affiliate Skills (`02-affiliate-skills/`) làm SOP kết hợp nguồn chính thức/đáng tin cậy, sau đó thiết kế cấu trúc website (category/taxonomy, URL pattern ổn định) để hỗ trợ bổ sung thêm nhóm AI Tools mới sau MVP mà không cần thay đổi cấu trúc chính hoặc URL nội dung đã publish.
- Hoàn thiện website trên nền WordPress + Elementor hiện có: viết nội dung cho 4 nhóm ưu tiên (AI video generator, AI avatar tools, AI UGC/ad creator, text-to-video) theo quy trình Content Research Brief → viết → QA (nguồn, factual claims, compliance) bằng Affiliate Skills trước khi trình duyệt, cùng các trang cơ bản Home, About, Contact, Affiliate Disclosure, Privacy Policy, Terms of Use/Terms & Conditions.
- Thiết lập nền tảng SEO cơ bản (sitemap, title/meta cơ bản, kết nối Search Console nếu khả thi) và kiểm tra để đảm bảo không có lỗi hiển thị hoặc vấn đề tốc độ nghiêm trọng trên desktop/mobile.
- Trình Nhung duyệt phiên bản trước khi deploy, triển khai lên domain futuretoolsbase.com sau khi được đồng ý, và đưa lại cho Nhung xác nhận kết quả chạy thật sau deploy.

## 4. DOES NOT do
- Không mở rộng SEO cơ bản thành SEO nâng cao (không làm content dài hạn, nghiên cứu từ khóa chuyên sâu, xây backlink...).
- Không tự thêm công cụ/theme/plugin/CDN cụ thể — các lựa chọn này sẽ chốt ở bước Architecture, sau khi kiểm tra môi trường hiện tại.
- Không đổi nền tảng khỏi WordPress + Elementor + HostArmada trong phạm vi MVP này.
- Không tự động viết hàng trăm bài nội dung.
- Không đảm bảo mọi chương trình Affiliate sẽ duyệt hồ sơ.
- Không đảm bảo tuân thủ 100% mọi luật/chính sách quốc tế — Affiliate Disclosure và Privacy Policy chỉ được rà soát/hoàn thiện ở mức cơ bản.
- Không tự động publish/deploy khi chưa có sự đồng ý của Nhung ở bước duyệt trước deploy.
- Không coi 4 nhóm AI Tools ưu tiên ban đầu là giới hạn vĩnh viễn của website — nhưng việc bổ sung nhóm mới nằm ngoài phạm vi MVP này, xử lý bằng ticket riêng trên Linear.

## 5. Data
- **Input:** ngách tổng thể (AI Tools), nhóm ưu tiên ban đầu (AI video generator, AI avatar tools, AI UGC/ad creator, text-to-video), thị trường mục tiêu quốc tế, domain (futuretoolsbase.com — đã đăng ký), ngôn ngữ (tiếng Anh), mục tiêu website.
- **Output:** website WordPress chạy thật trên futuretoolsbase.com, cấu trúc category/URL ổn định sẵn sàng mở rộng, đủ 6 trang cơ bản đã publish (Home, About, Contact, Affiliate Disclosure, Privacy Policy, Terms of Use/Terms & Conditions), nền tảng SEO cơ bản đã thiết lập.
- **Nền tảng:** WordPress + Elementor hiện có; SEO plugin hiện tại là Rank Math (đang được đánh giá tiếp tục dùng hay thay ở bước Architecture); theme/plugin cache/CDN cụ thể khác chưa chốt trong spec này, sẽ quyết định ở bước Architecture.
- **Hosting:** HostArmada.
- **Công cụ hỗ trợ nội dung:** Affiliate Skills (`02-affiliate-skills/`, lưu local, không đưa lên GitHub) dùng làm SOP cho quy trình Research/Content/QA — không phải nguồn sự thật duy nhất, luôn kết hợp kiểm tra nguồn chính thức.
- **Lưu ở đâu:**
  - Context, spec, kiến trúc → repo GitHub `affiliate-website-starter` (Private).
  - Website thật (nội dung, cấu hình) → WordPress trên hosting HostArmada, domain futuretoolsbase.com.
  - Ticket, kế hoạch triển khai → Linear.
  - Secret/API key, tài khoản WordPress/hosting/domain registrar → 1Password/vault theo dự án, không lưu trong repo hay chat.
- **Chi phí:** domain + hosting hiện do Nhung tự chi trả, ngoài phạm vi ngân sách dự án.

## 6. Done means
Coi là "xong" khi đồng thời thỏa:
- Website MVP chạy thật bằng tiếng Anh trên futuretoolsbase.com, có nội dung cơ bản cho 4 nhóm AI Tools ưu tiên (đã qua Content Research Brief và QA), có đủ 6 trang cơ bản đã publish: Home, About, Contact, Affiliate Disclosure, Privacy Policy, Terms of Use/Terms & Conditions.
- Cấu trúc category/taxonomy và URL ổn định, sẵn sàng bổ sung nhóm AI Tools mới sau này mà không cần đổi URL hoặc kiến trúc đã publish.
- Đạt các mục tiêu kỹ thuật tối thiểu: sitemap hoạt động; title/meta cơ bản được thiết lập; Search Console được kết nối nếu khả thi; website không có lỗi hiển thị nghiêm trọng trên desktop/mobile; website không có vấn đề tốc độ nghiêm trọng.
- Quy trình duyệt 2 bước được thực hiện đầy đủ: Nhung duyệt phiên bản trước khi deploy, và Nhung xác nhận kết quả chạy thật sau deploy bằng comment trên Linear ticket tương ứng.
- Hoàn thành trước ngày **20/09/2026**.

## 7. Where it can break
- DNS/hosting HostArmada chậm hoặc không ổn định → ảnh hưởng tốc độ và uptime dù nội dung đã xong.
- API key/token hoặc tài khoản WordPress/hosting/domain hết hạn hoặc bị lộ → mất kết nối hoặc mất quyền kiểm soát site.
- Nội dung do AI tạo chưa được xác minh → có thể sai thông tin, đặc biệt do rào cản tiếng Anh.
- Thiếu bước kiểm tra cố định (SEO cơ bản, Affiliate Disclosure, Privacy Policy) trước khi publish → sai sót không được phát hiện kịp thời.
- Chương trình Affiliate từ chối hồ sơ vì website chưa đáp ứng yêu cầu riêng của từng chương trình.
- Elementor/plugin gây lỗi hoặc chậm sau khi cập nhật → cần có bản backup gần nhất để khôi phục trước khi tiếp tục sửa; không thay thế website đang hoạt động nếu phiên bản mới chưa được kiểm tra.
- Cấu trúc category/URL đặt sai từ đầu → phải đổi URL khi mở rộng thêm nhóm AI Tools mới, gây mất SEO đã tích lũy.
- Bỏ qua bước duyệt trước deploy → phiên bản chưa hoàn chỉnh có thể bị đưa lên Internet ngoài ý muốn.
