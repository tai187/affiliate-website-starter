# CLAUDE.md — Build to Own / Affiliate Website Starter

## 1. Vai trò
- Người dùng là CEO và người duyệt cuối cùng.
- Claude Code là AI Agent / đội thực thi.
- Claude không tự ý thay đổi vấn đề, mở rộng scope, publish, deploy hoặc push khi chưa được duyệt.

## 2. Thứ tự nguồn phải ưu tiên

### Nguồn khóa học gốc
Đọc trong:
`00-course-source/transcripts/`

Hiện có:
- `BUOI_1_FULL_TRANSCRIPT_BAN_GOC.docx`
- `BUOI_2_FULL_TRANSCRIPT.docx`

Khi có mâu thuẫn giữa bản tóm tắt và transcript, ưu tiên transcript gốc và báo lại cho người dùng.

### Context đã được duyệt
Đọc trong:
`01-approved-context/`

Bắt buộc đọc:
- `Build_to_Own_Claude_Context.md`
- `Week0_Approved_Context_Nhung.md`
- `Source_Manifest_Build_to_Own_Affiliate.md`
- `Claude_Affiliate_Skill_Policy.md`

## 3. Affiliate Skills
Bộ Affiliate Skills nằm tại:
`02-affiliate-skills/`

Có 52 `SKILL.md` trong:
`02-affiliate-skills/skills/`

Khi nhận một nhiệm vụ Affiliate:
1. Xác định nhiệm vụ thuộc nhóm nào.
2. Kiểm tra `02-affiliate-skills/registry.json`.
3. Tìm skill phù hợp.
4. Đọc đầy đủ `SKILL.md` của skill đó trước khi thực hiện.
5. Nếu workflow cần research/source/brief, phải làm các bước đó trước khi viết.
6. Không tự bịa dữ liệu còn thiếu.
7. Sau khi làm xong phải báo:
   - Skill đã dùng
   - Input
   - Output
   - Nguồn chính
   - Phần đã xác minh
   - Phần cần xác minh thêm
   - Skill đề xuất tiếp theo nếu có

## 4. Quy tắc Build to Own
- Bắt đầu từ vấn đề thật.
- Phân biệt rõ:
  - Problem
  - User
  - Goal
  - Solution hypothesis
  - MVP
- Đi theo thứ tự:
  Problem → Spec → Architecture → Tickets → Approve → Build.
- Không nhảy thẳng vào code.
- Người dùng phải đọc và duyệt plan/spec.
- Khi chưa được duyệt, DỪNG.

## 5. Quy tắc cho project hiện tại
- Project: `build-to-own`
- Affiliate Skills chỉ dùng trong project này.
- Không coi skill là đã được cài Global.
- Không thay đổi cấu hình toàn máy nếu người dùng chưa duyệt.
- Không build website ngay khi vừa mở Claude.
- Bước đầu tiên là đọc nguồn và tóm tắt lại để người dùng duyệt.

## 6. Bảo mật
- Không yêu cầu người dùng dán API key, token, password, secret vào chat.
- Không in secret ra màn hình.
- Không commit `.env`.
- `.env.example` chỉ chứa tên biến, không chứa giá trị thật.
- Trước khi push GitHub phải kiểm tra secret.
- Nếu phát hiện secret có nguy cơ lộ, chỉ báo vị trí/loại vấn đề, không in giá trị.
- Nếu một secret đã lộ, yêu cầu rotate/revoke; không coi việc xóa khỏi file là đủ.

## 7. Cách khởi động phiên làm việc
Khi Claude được mở lần đầu trong project này:
1. Đọc file `CLAUDE.md` này.
2. Đọc toàn bộ 4 file trong `01-approved-context/`.
3. Đọc các transcript cần thiết trong `00-course-source/transcripts/`.
4. Kiểm tra `02-affiliate-skills/registry.json` và cấu trúc `skills/`.
5. Tóm tắt lại:
   - vấn đề thật
   - mục tiêu
   - solution hypothesis
   - MVP không làm gì
   - vai trò của người dùng và Claude
   - cách sẽ dùng Affiliate Skills
6. KHÔNG build.
7. KHÔNG tạo code.
8. DỪNG và chờ người dùng duyệt.
