---
title: "Opus5 Workflow Library V1.0"
version: "1.0"
tags: [moc, index]
---

# 🧭 Opus 5 Workflow Library V1.0

**50 Production Workflows** cho builder cá nhân / one-man company, dùng **Opus 5** qua cả **Claude Chat** lẫn **Claude Code**.

Đây là vault Obsidian — mở thư mục `OP OPUS 5` bằng Obsidian ("Open folder as vault") để có graph view và liên kết `[[wikilink]]` giữa các workflow.

## Cách dùng vault này

1. Mỗi workflow là 1 file `.md` độc lập, theo đúng 1 cấu trúc 9 mục (xem [[_Template]]).
2. Không biết bắt đầu từ đâu? Vào category gần nhất với việc bạn đang làm, đọc mục **Khi nào dùng** trước để chọn đúng bài.
3. Copy phần **Prompt Template** vào Claude Chat, hoặc theo hướng dẫn ở mục **Phiên bản Claude Code** nếu việc phù hợp chạy qua CLI.
4. Mục **Khi nào nên dùng Deep Research** giúp bạn quyết định có cần bật Deep Research thay vì hỏi thẳng hay không.
5. Muốn thêm workflow riêng? Nhân bản [[_Template]] và điền theo đúng cấu trúc.

---

## 00 · Foundations
- [[00.01-setup-claude-cho-solo-builder]] — Thiết lập Claude cho Solo Builder (Chat + Code + Projects)
- [[00.02-chon-cong-cu-chat-vs-code-vs-agent-sdk]] — Chọn đúng công cụ: Claude Chat vs Claude Code vs Agent SDK
- [[00.03-viet-claude-md-system-prompt-ca-nhan]] — Xây dựng CLAUDE.md / System Prompt cá nhân hoá

## 01 · Learn
- [[01.01-hoc-chu-de-moi-tu-zero-den-hieu-sau]] — Học một chủ đề mới từ Zero đến Hiểu sâu (Feynman + Opus)
- [[01.02-giai-thich-lai-kien-thuc-phuc-tap]] — Giải thích lại kiến thức phức tạp theo trình độ của mình
- [[01.03-tao-lo-trinh-hoc-ky-nang-moi]] — Tạo lộ trình học (Learning Roadmap) cho kỹ năng mới

## 02 · Research
- [[02.01-deep-research-chu-de-thi-truong]] — Deep Research một chủ đề thị trường/ngành
- [[02.02-tong-hop-so-sanh-nhieu-nguon]] — Tổng hợp và so sánh nhiều nguồn tài liệu
- [[02.03-fact-check-truoc-khi-cong-bo]] — Fact-check và kiểm chứng thông tin trước khi công bố
- [[02.04-theo-doi-doi-thu-canh-tranh]] — Theo dõi đối thủ cạnh tranh (Competitive Research)

## 03 · Thinking
- [[03.01-ra-quyet-dinh-kho-decision-framework]] — Ra quyết định khó với khung tư duy
- [[03.02-brainstorm-y-tuong-kinh-doanh]] — Brainstorm ý tưởng kinh doanh mới
- [[03.03-phan-bien-y-tuong-cua-chinh-minh]] — Phản biện lại ý tưởng của chính mình (Devil's Advocate)

## 04 · Writing
- [[04.01-viet-blog-newsletter-dung-giong-van]] — Viết bài blog/newsletter chuẩn giọng văn cá nhân
- [[04.02-viet-email-dm-thuyet-phuc]] — Viết email/DM thuyết phục khách hàng hoặc đối tác
- [[04.03-bien-tap-rut-gon-bai-viet-dai]] — Biên tập và rút gọn bài viết dài
- [[04.04-viet-kich-ban-video-podcast]] — Viết kịch bản video/podcast ngắn

## 05 · Coding
- [[05.01-tu-y-tuong-den-mvp-claude-code]] — Từ ý tưởng đến MVP (Claude Code end-to-end)
- [[05.02-debug-loi-production-tu-log]] — Debug lỗi production với log thực tế
- [[05.03-code-review-truoc-khi-merge]] — Code review trước khi merge
- [[05.04-viet-test-tu-dong-cho-tinh-nang-moi]] — Viết test tự động cho tính năng mới
- [[05.05-refactor-codebase-cu-khong-co-test]] — Refactor codebase cũ không có test
- [[05.06-deploy-va-kiem-tra-sau-build]] — Deploy và kiểm tra ứng dụng sau khi build

## 06 · AI Agent
- [[06.01-thiet-ke-agent-don-gian]] — Thiết kế Agent đơn giản cho tác vụ lặp lại
- [[06.02-xay-multi-agent-workflow]] — Xây dựng multi-agent workflow (orchestrator + subagent)
- [[06.03-debug-agent-lap-vong-bi-treo]] — Debug Agent bị lặp vòng hoặc bị treo
- [[06.04-danh-gia-chat-luong-output-agent]] — Đánh giá chất lượng output của Agent (Agent Eval)

## 07 · RAG
- [[07.01-xay-rag-co-ban-tai-lieu-noi-bo]] — Xây dựng RAG cơ bản cho tài liệu nội bộ
- [[07.02-toi-uu-chunking-va-retrieval]] — Tối ưu chunking và retrieval cho RAG
- [[07.03-danh-gia-do-chinh-xac-rag]] — Đánh giá độ chính xác của hệ thống RAG

## 08 · Data
- [[08.01-phan-tich-du-lieu-csv-excel]] — Phân tích dữ liệu kinh doanh từ file CSV/Excel
- [[08.02-viet-sql-tu-ngon-ngu-tu-nhien]] — Viết SQL query từ yêu cầu ngôn ngữ tự nhiên
- [[08.03-truc-quan-hoa-du-lieu-nhanh]] — Trực quan hoá dữ liệu (Data Visualization) nhanh

## 09 · Business
- [[09.01-viet-business-plan-pitch-deck]] — Viết Business Plan / Pitch Deck cho sản phẩm mới
- [[09.02-dinh-gia-san-pham-dich-vu]] — Định giá sản phẩm/dịch vụ (Pricing Strategy)
- [[09.03-cham-soc-khach-hang-tu-dong-hoa]] — Chăm sóc khách hàng tự động hoá
- [[09.04-phan-tich-tai-chinh-doanh-nghiep-nho]] — Phân tích tài chính doanh nghiệp nhỏ (Cash Flow, P&L)

## 10 · Design
- [[10.01-thiet-ke-ui-ux-tu-mo-ta]] — Thiết kế UI/UX từ mô tả bằng lời
- [[10.02-tao-design-system-style-guide]] — Tạo Design System / Style Guide cơ bản
- [[10.03-review-gop-y-thiet-ke]] — Review và góp ý thiết kế (Design Critique)

## 11 · Education
- [[11.01-soan-giao-an-khoa-hoc-ngan]] — Soạn giáo án / khoá học ngắn
- [[11.02-cham-bai-phan-hoi-hoc-vien]] — Chấm bài và phản hồi cho học viên

## 12 · Crypto
- [[12.01-phan-tich-on-chain-thi-truong]] — Phân tích on-chain / thị trường crypto
- [[12.02-danh-gia-whitepaper-du-an-moi]] — Đánh giá whitepaper / dự án crypto mới
- [[12.03-theo-doi-danh-muc-dau-tu-crypto]] — Theo dõi danh mục đầu tư crypto cá nhân

## 13 · Automation
- [[13.01-tu-dong-hoa-quy-trinh-claude-code-script]] — Tự động hoá quy trình lặp lại với Claude Code + Script
- [[13.02-xay-cron-job-scheduled-agent]] — Xây dựng Cron Job / Scheduled Agent
- [[13.03-tich-hop-claude-slack-email-notion-mcp]] — Tích hợp Claude vào Slack/Email/Notion (MCP)

## 14 · Meta Prompt
- [[14.01-viet-prompt-template-tai-su-dung]] — Viết Prompt Template tái sử dụng cho workflow riêng
- [[14.02-danh-gia-cai-thien-prompt-eval-loop]] — Đánh giá và cải thiện Prompt (Prompt Evaluation Loop)

---

*Opus5 Workflow Library V1.0 — 50 workflows / 14 categories / 1 mục tiêu: builder cá nhân dùng Opus 5 làm việc như một team.*
