# awesome-readme-form

Form README cá nhân — chắt từ 3 repo nổi tiếng + kinh nghiệm thực tế, để lần sau viết README không phải nghĩ lại từ đầu.

## Chắt từ đâu

| Nguồn | ★ | Lấy cái gì |
| --- | --- | --- |
| [Best-README-Template](https://github.com/othneildrew/Best-README-Template) | 16k | Khung mục chuẩn: shields → logo → About → Built With → Getting Started → Usage → Roadmap → Contributing → License → Contact |
| [awesome-readme](https://github.com/matiassingers/awesome-readme) | 21k | 141 README mẫu — đúc ra quy tắc chung: logo/banner, ảnh demo ngay đầu, badges, TOC, install copy-paste được |
| [dbader/readme-template](https://github.com/dbader/readme-template) | 2k | Bản tối giản cho repo nhỏ: blurb 1–2 câu, install, usage, release history |

## Checklist (áp vào repo mới, xóa mục không cần)

- [ ] Shields (badges) đầu file: build, version, downloads, license — lấy ở [shields.io](https://shields.io)
- [ ] Logo/banner giữa trang + tên + mô tả 1–2 câu + link Demo / Report Bug / Request Feature
- [ ] Table of Contents gọn (dùng `<details>` nếu dài) + link back to top cuối mỗi mục
- [ ] About: nêu vấn đề giải quyết + ảnh/GIF demo NGAY — không để chữ khô
- [ ] Features: gạch đầu dòng hướng người dùng — cấm chi tiết nội bộ (tên lib, polling, font, panel About…)
- [ ] Built With: framework/lib chính, dạng badge
- [ ] Getting Started: Prerequisites + Installation copy-paste chạy được, chia theo OS nếu cần
- [ ] Usage: ví dụ ngắn + link docs đầy đủ
- [ ] Screenshots: bảng 2 cột, ghim `width` (xem mục Ảnh)
- [ ] Roadmap hoặc Release history (chọn 1, repo nhỏ thì bỏ cả 2 cũng được)
- [ ] Contributing (5 bước fork → PR), License, Contact
- [ ] Link/badge dùng kiểu reference `[][id]`, khai báo cuối file cho gọn

## Ảnh (kinh nghiệm xương máu)

- Bảng markdown KHÔNG tự cân ảnh — luôn ghim cỡ: `<img src="..." width="400" alt="...">`
- Ảnh chụp màn hình khổ lớn thì resize trước khi commit: `sips -Z 1600 in.png --out out.png`
- Tính năng động → 1 GIF demo thay cho 5 ảnh tĩnh
- 2 ảnh cạnh nhau thì cùng `width`; ảnh đơn để full-width cũng được

## Cách dùng

1. Copy [TEMPLATE.md](TEMPLATE.md) thành `README.md` của repo mới
2. Điền từng mục theo checklist, xóa mục thừa
3. Đọc lại 1 lượt với con mắt người lạ: hiểu repo làm gì trong 10 giây không?
