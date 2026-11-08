# claude-n8n-starter

Bộ kit của The AI Growth cho học viên AI Agents Mastery và AI Agent Cho Doanh Nghiệp: chạy n8n trên máy bạn bằng Docker và điều khiển n8n bằng lời nói trong app Claude Desktop (tab Code).

## Bắt đầu

1. Bấm nút xanh **Code** → **Download ZIP**, giải nén, đổi tên folder thành `claude-n8n-starter`.
2. Mở app Claude, tab **Code**, chọn **Local**, chọn folder này, bấm **Trust**, chọn chế độ **Auto**.
3. Gõ vào khung chat:

```
Cài n8n cho mình qua Docker, link repo đây: https://github.com/n8n-io/n8n. Máy mình là <MacBook / Windows 11>, chưa cài Docker.
```

Hướng dẫn đầy đủ và câu lệnh mẫu: [HUONG-DAN.md](HUONG-DAN.md).

## Trong folder có gì

| File | Dùng để |
|---|---|
| `AGENTS.md`, `CLAUDE.md` | Luật làm việc của Claude trong folder này |
| `.claude/settings.json` | Lệnh được tự chạy, lệnh phải hỏi; khai báo plugin `n8n-skills` |
| `.claude/skills/cai-dat-n8n/` | Quy trình cài, bật lại, cập nhật, sao lưu n8n |
| `n8n/compose.yml` | Cấu hình chạy n8n bằng Docker, chỉ mở trên máy bạn |
| `workflows/mau/` | Workflow mẫu để nhập thử |
| `TIEN-DO.md`, `BAI-HOC.md` | Claude ghi tiến độ cài và bài học khi sửa lỗi |

Không đưa API key vào folder này trên GitHub. Key nằm trong credential của n8n hoặc file `.env` trên máy bạn.
