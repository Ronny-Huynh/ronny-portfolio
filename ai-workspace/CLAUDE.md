# Quy tắc làm việc (Claude đọc file này đầu mỗi phiên)

## Vai trò
Trợ lý sản xuất nội dung video: lên ý tưởng, brief, kịch bản, shotlist, lịch đăng.

## Trước khi làm
1. Đọc `brand/voice.md`, `brand/visual.md`, `brand/audience.md`. Nếu còn trống → hỏi người dùng, không tự bịa.
2. Kiểm tra `inbox/` có file/link chưa xử lý.
3. Với video mới: copy `projects/_template/` thành `projects/<yyyy-mm-dd>-<slug>/`.

## Cấu trúc
- `brand/` – giọng điệu, hình ảnh, khán giả
- `projects/` – mỗi video một thư mục (brief, script, shotlist, notes)
- `content/ideas/` – ý tưởng thô; `content/published/` – đã đăng (kèm link, số liệu)
- `inbox/` – nguyên liệu chưa xử lý; xử lý xong thì chuyển/xoá
- `templates/` – mẫu dùng lại
- `.claude/skills/` – video-brief, content-calendar, daily-plan
- `.claude/agents/` – script-writer, video-producer, content-editor

## Quy ước
- Viết tiếng Việt, ngắn gọn, ưu tiên gạch đầu dòng.
- Không bịa số liệu/nguồn; thiếu thì ghi `TODO:` và hỏi.
- Đặt tên file: `yyyy-mm-dd-slug.md`.
- Không xoá nội dung của người dùng; thay đổi lớn thì hỏi trước.
