---
title: "Tên Workflow"
category: "NN Tên Category"
id: NN.MM
tools: [Claude Chat, Claude Code]
tags: [category-slug]
version: "1.0"
---

# Tên Workflow

## Mục tiêu
Workflow này giúp bạn đạt được điều gì, trong bao lâu, với chất lượng ra sao. 1-2 câu, cụ thể, đo lường được — không viết chung chung kiểu "giúp bạn làm việc hiệu quả hơn".

## Khi nào dùng
- Tình huống cụ thể 1 kích hoạt việc dùng workflow này
- Tình huống cụ thể 2
- (Tuỳ chọn) Khi nào KHÔNG nên dùng workflow này — dùng cái khác thay thế

## Input
Những gì bạn cần chuẩn bị trước khi bắt đầu: dữ liệu, file, ngữ cảnh, quyết định cần chốt trước.
- Input bắt buộc 1
- Input bắt buộc 2
- Input tuỳ chọn (nếu có sẽ cho kết quả tốt hơn)

## Prompt Template
Đoạn prompt copy-paste được ngay vào Claude Chat, có placeholder `{{...}}` để điền:

```
Bạn là {{vai trò}}. Nhiệm vụ: {{mô tả nhiệm vụ cụ thể}}.

Bối cảnh:
{{ngữ cảnh, dữ liệu đầu vào}}

Yêu cầu:
1. {{yêu cầu 1}}
2. {{yêu cầu 2}}

Định dạng output: {{mô tả định dạng mong muốn}}
```

## Checklist
- [ ] Bước kiểm tra 1
- [ ] Bước kiểm tra 2
- [ ] Bước kiểm tra 3

## Expected Output
Mô tả output "tốt" trông như thế nào — độ dài, cấu trúc, tiêu chí chấp nhận được. Nếu có thể, cho 1 ví dụ ngắn.

## Common mistakes
- Lỗi thường gặp 1 và vì sao nó xảy ra
- Lỗi thường gặp 2
- Lỗi thường gặp 3

## Phiên bản Claude Code
Cách chạy workflow này qua Claude Code CLI thay vì Claude Chat (nếu phù hợp): cấu trúc project, lệnh CLI, subagent/skill liên quan, hoặc ghi rõ "workflow này phù hợp Claude Chat hơn, không cần Claude Code" nếu đúng vậy.

## Khi nào nên dùng Deep Research
Tiêu chí cụ thể để quyết định chuyển sang Deep Research thay vì hỏi trực tiếp: độ phức tạp câu hỏi, số lượng nguồn cần tổng hợp, mức độ cập nhật thông tin cần thiết. Nếu workflow này hiếm khi cần Deep Research, ghi rõ lý do.
