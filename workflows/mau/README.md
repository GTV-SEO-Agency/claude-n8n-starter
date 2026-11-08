# Workflow mẫu

Claude đọc các mẫu trong folder này trước khi dựng workflow mới, nên dựng đúng ý nhanh hơn. Bạn cũng có thể nhập thẳng một mẫu vào n8n để chạy thử.

| Folder | Có gì |
|---|---|
| `TAG_mau_*.json` | 4 mẫu nhập thử của kit: xin chào, tỷ giá mỗi sáng, lead form chấm điểm, trợ lý tư vấn khoá học |
| `tag-build/` | 40 workflow The AI Growth đã dựng và dạy trong khoá: content marketing, video, RAG chatbot, trợ lý AI, sale có người duyệt |
| `cong-dong/` | 104 workflow cộng đồng n8n do The AI Growth chọn lọc, chia theo 9 nhóm việc |

## Trước khi dùng một mẫu

1. Mẫu đã bỏ hết credential, API key, email, ID file Google Drive, Sheet, Notion, Telegram chat. Chỗ cần điền có dạng `<YOUR_API_KEY>`, `<YOUR_ID>` hoặc ô trống.
2. Nhập mẫu vào n8n, rồi gắn credential của bạn cho từng node có tam giác đỏ.
3. Chọn lại file Sheet, folder Drive, database Notion của bạn ở các node đó.
4. Chạy thử với dữ liệu mẫu trước khi bật.

Câu lệnh gợi ý cho Claude: "Dựa vào mẫu trong `workflows/mau/tag-build/Content Marketing AI Agent/`, dựng cho tôi workflow …".

## Nguồn

- `tag-build/`: The AI Growth tự dựng.
- `cong-dong/`: lấy từ thư viện template cộng đồng của n8n (n8n.io/workflows) và các tác giả chia sẻ công khai. Ghi chú trong từng workflow giữ tên và link của tác giả gốc.
