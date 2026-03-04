---
title: "Công nghệ xây dựng Blog này"
date: 2026-03-03 12:00:00 +0700
categories: [Giới thiệu, Công nghệ]
tags: [jekyll, chirpy, github-pages]
---

Nhiều người hỏi mình tại sao không dùng WordPress hay Medium? Câu trả lời nằm ở sự tự do và khả năng tùy biến mà **Static Site Generators** mang lại.

### Stack kỹ thuật
- **Jekyll**: Công cụ tạo website tĩnh mạnh mẽ được viết bằng Ruby.
- **Theme Chirpy**: Một theme tuyệt vời hỗ trợ đầy đủ các tính năng hiện đại.
- **GitHub Pages**: Nơi lưu trữ và triển khai trang web tự động.

> Bạn có thể tìm thấy mã nguồn của blog này tại tệp `_config.yml`{: .filepath }.
{: .prompt-tip }

### Tại sao chọn Markdown?
Markdown giúp việc soạn thảo nội dung trở nên cực kỳ nhanh chóng. Bạn chỉ cần viết text thuần và Chirpy sẽ lo phần hiển thị đẹp mắt.

```bash
# Lệnh để chạy blog ở môi trường local
bundle exec jekyll serve
```

Với stack này, mình có thể tập trung hoàn toàn vào nội dung mà không cần lo lắng về việc quản lý cơ sở dữ liệu hay bảo mật máy chủ.
