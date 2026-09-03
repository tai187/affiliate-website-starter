# SOURCE MANIFEST — BUILD TO OWN + AFFILIATE
## Dùng cho Claude Code trong workspace `build-to-own`

> Mục tiêu: giúp Claude biết nguồn nào là nguồn khóa học, nguồn nào là bộ nghiệp vụ Affiliate, và ưu tiên nguồn thế nào khi làm bài hoặc viết content.

---

# 1. NGUỒN KHÓA HỌC BUILD TO OWN

## 1.1. Website chính thức
- https://build2own.dev/

Vai trò:
- Nguồn chính thức của chương trình Build to Own.
- Ưu tiên cao nhất cho đề bài, deadline, checklist, tài liệu và yêu cầu nộp bài.

## 1.2. Discord — message 1
- https://discord.com/channels/1539806748892995594/1539817200595107860/1542051386307514459

## 1.3. Discord — message 2
- https://discord.com/channels/1539806748892995594/1539817200595107860/1542832955523600406

Vai trò của 2 link Discord:
- Nguồn bổ sung từ cộng đồng/giáo viên trong server khóa học.
- Vì link Discord có thể cần đăng nhập và quyền server, Claude không được giả vờ đã đọc nội dung nếu chưa có nội dung được copy/export vào workspace.
- Khi cần dùng nội dung Discord, yêu cầu Nhung copy text, transcript hoặc ảnh/tài liệu vào `00-course-source/discord/`.

---

# 2. NGUỒN GITHUB CỦA SON PIAZ

## 2.1. GitHub profile
- https://github.com/sonpiaz

Vai trò:
- Điểm bắt đầu để xác định các repo chính thức liên quan đến AI Agent và Affiliate.

## 2.2. Affiliate Skills — repo chính thức
- https://github.com/Affitor/affiliate-skills

Repo này là bộ skill nghiệp vụ Affiliate.
Claude phải ưu tiên đọc đúng `SKILL.md` tương ứng trước khi làm một nhiệm vụ Affiliate.

Repo có:
- `skills/{stage}/{skill-name}/SKILL.md`
- `shared/references/`
- `registry.json`
- `CLAUDE.md`
- `README.md`

Cách cài được repo hướng dẫn:
`npx skills add Affitor/affiliate-skills`

Không chạy lệnh cài đặt khi Nhung chưa duyệt.

## 2.3. Open Affiliate
- https://github.com/Affitor/open-affiliate

Vai trò:
- Registry dữ liệu chương trình Affiliate.
- Có thể dùng làm nguồn dữ liệu program khi skill yêu cầu tìm affiliate program.

---

# 3. THỨ TỰ ƯU TIÊN NGUỒN

Khi làm bài Build to Own:
1. Đề bài Campus / build2own.dev.
2. Transcript hoặc tài liệu giáo viên đã lưu trong workspace.
3. Discord đã được copy/export vào workspace.
4. Bài Tuần 0 đã được Nhung duyệt.
5. Đề xuất của Claude.

Khi làm nghiệp vụ Affiliate:
1. `SKILL.md` của skill phù hợp trong `affiliate-skills`.
2. Shared references / compliance references của repo.
3. Nguồn dữ liệu chính thức của merchant / affiliate program.
4. Open Affiliate nếu phù hợp.
5. Nguồn web đáng tin cậy.
6. Suy luận của AI — phải đánh dấu rõ nếu chưa xác minh.

---

# 4. QUY TẮC KHI CLAUDE VIẾT BÀI AFFILIATE

Trước khi viết:
1. Xác định loại nhiệm vụ: review / comparison / listicle / tutorial / landing / SEO / research...
2. Tìm skill phù hợp trong `affiliate-skills`.
3. Đọc đầy đủ `SKILL.md` của skill đó.
4. Kiểm tra input còn thiếu.
5. Research bằng nguồn thật.
6. Chỉ viết sau khi đã có brief/source.

Sau khi viết:
1. Nói rõ skill nào đã dùng.
2. Nêu nguồn dữ liệu chính.
3. Đánh dấu:
   - ĐÃ XÁC MINH
   - CẦN KIỂM TRA THÊM
   - KHÔNG NÊN DÙNG
4. Chạy SEO/compliance check nếu workflow yêu cầu.
5. Không tự tạo claim về giá, hoa hồng, tính năng, điều khoản hoặc chính sách nếu chưa có nguồn.

---

# 5. CẤU TRÚC WORKSPACE KHUYẾN NGHỊ

build-to-own/
├── 00-course-source/
│   ├── campus/
│   ├── discord/
│   ├── transcripts/
│   └── guides/
├── 01-approved-context/
│   ├── Build_to_Own_Claude_Context.md
│   └── Week0_Approved_Context_Nhung.md
├── 02-affiliate-skills/
├── 03-spec/
├── 04-architecture/
├── 05-tickets/
├── 06-product/
├── 07-content/
├── 08-security/
└── 09-submissions/

---

# 6. QUY TẮC KHÔNG ĐƯỢC VI PHẠM

- Không bịa rằng đã đọc Discord nếu chưa có nội dung local.
- Không thay yêu cầu khóa học bằng workflow do AI tự nghĩ.
- Không viết content Affiliate chỉ từ trí nhớ khi skill yêu cầu research.
- Không dán API key/token/password vào chat hoặc commit.
- Không để `.env` vào Git.
- Không tự mở rộng MVP.
