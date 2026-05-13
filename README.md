# NguyenAnhQuan-AWSFCJ

Đây là project báo cáo thực tập AWS của tôi, sử dụng Hugo để tạo trang web tĩnh.

## Nội dung

- **1-Worklog**: Nhật ký công việc hàng tuần
- **2-Proposal**: Đề xuất dự án
- **3-BlogsTranslated**: Bài viết dịch
- **4-EventParticipated**: Sự kiện tham gia
- **5-Workshop**: Workshop AWS
- **6-Self-evaluation**: Tự đánh giá
- **7-Feedback**: Phản hồi

## Cách chạy

### Yêu cầu
- [Hugo](https://gohugo.io/getting-started/installing/) (phiên bản extended nếu cần SCSS/Sass)
- Git

### Chạy local
```bash
git clone https://github.com/NguyenAnhQuan2588/NguyenAnhQuan-AWSFCJ.git
cd NguyenAnhQuan-AWSFCJ
hugo server -D
```

Truy cập: http://localhost:1313/

### Build production
```bash
hugo -D
```

File sẽ được tạo trong thư mục `public/`.

## Deploy

Project này được deploy tự động lên GitHub Pages tại: https://nguyenanhquan2588.github.io/NguyenAnhQuan-AWSFCJ/

## Cấu trúc

- `config.toml`: Cấu hình Hugo
- `content/`: Nội dung các trang
- `layouts/`: Template tùy chỉnh
- `static/`: File tĩnh (CSS, JS, hình ảnh)
- `themes/hugo-theme-learn/`: Theme Hugo Learn

## Liên hệ

NguyenAnhQuan2588