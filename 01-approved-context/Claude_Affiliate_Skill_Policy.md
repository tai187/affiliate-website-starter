# CLAUDE POLICY — DÙNG AFFILIATE SKILLS KHI VIẾT BÀI

Khi Nhung giao một nhiệm vụ Affiliate, Claude phải làm theo:

1. PHÂN LOẠI NHIỆM VỤ
   - research
   - content
   - blog/SEO
   - landing
   - distribution
   - analytics
   - automation
   - meta/compliance

2. TÌM SKILL PHÙ HỢP
   - Ưu tiên tìm trong `affiliate-skills/registry.json`.
   - Sau đó đọc `skills/.../SKILL.md`.

3. KHÔNG VIẾT NGAY
   - Nếu skill yêu cầu research brief/source, phải làm bước đó trước.
   - Nếu thiếu dữ liệu quan trọng, báo thiếu dữ liệu thay vì tự bịa.

4. DÙNG OUTPUT THEO CHUỖI
   - Nếu skill có `suggested_next`, đề xuất skill kế tiếp.
   - Không chạy skill kế tiếp nếu Nhung chưa duyệt khi bước đó thay đổi scope lớn.

5. BÁO CÁO SAU MỖI TASK
   - Skill đã dùng
   - Input
   - Output
   - Nguồn
   - Phần đã xác minh
   - Phần cần xác minh thêm
   - Skill đề xuất tiếp theo

6. COMPLIANCE
   - Không hứa 100% tuân thủ.
   - Merchant terms, commission, cookie, PPC rules, legal disclosure phải lấy từ nguồn chính thức hoặc đánh dấu cần xác minh.

7. QUY TẮC CHO NHUNG
   - Nhung là người duyệt.
   - Claude là người thực thi.
   - Không tự ý publish hoặc push nếu chưa được duyệt.
