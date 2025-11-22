---
layout: default
title: "JAMstack Static Demo"
---

Đây là demo nhỏ cho môn **Kiến trúc phần mềm**.

- Site này được build bằng **Jekyll (Static Site Generator)** trên GitHub Pages.
- Nội dung (Markdown) được render sẵn thành **HTML tĩnh ở build-time**.
- Sau đó GitHub Pages host static content này trên **Storage + CDN** của GitHub.

Trang này là ví dụ thực tế cho pattern **Static Content Hosting** trong kiến trúc JAMstack:
- Markup được build sẵn.
- File tĩnh được phân phối qua CDN.
- Nếu cần dữ liệu động, frontend sẽ gọi thêm **API** (không nằm trong site tĩnh này).
