---
layout: default
lang: vi
title: Chim Canary và Canary Deployment
date: 2025-08-02
category: software-engineer
---

# Chim Canary và Canary Deployment

Chuyện kể rằng vào khoảng đầu thế kỷ 20, thợ mỏ ở Anh, Mỹ, Canada thường mang theo con chim hoàng yến xuống hầm than. Chim được dùng để phát hiện khí độc (CO) hơn là làm thú cưng. Chim rất nhạy, chỉ cần tí khí độc là nó lăn ra xỉu ngay, còn thợ mỏ thì nhìn chim mà quyết định đào tiếp hay chạy.

Ngày nay, các kỹ sư phần mềm mượn hình tượng đó khi triển khai phần mềm phiên bản mới. Họ cho một lượng truy cập nhỏ thử nghiệm trước. Nếu phiên bản mới đùng ra lỗi thì chuyển hết truy cập về phiên bản cũ. Cách làm này gọi là Canary Deployment hay là Triển khai Canary – chính là tên con chim hoàng yến bằng tiếng Anh.