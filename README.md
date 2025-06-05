# Đề Thi - Thiết Kế Giao Diện Website Học Tiếng Anh

## Lưu ý trước khi làm bài:
• Bài làm được đặt trong thư mục: `STT_HoVaTen_MaDe` (VD: `01_LeBaoAn_De3`). Trong thư mục này có các file: `cau1.html`, `cau2.html`, `cau3.html`, `cau4.html`, `cau5.html` và các file khác (nếu có).  
• Chỉ sử dụng HTML, CSS, JS, không sử dụng thêm bất kỳ thư viện, framework nào.  
• Thiết kế sử dụng các màu sắc dưới đây, ngoài ra có thể dùng thêm các màu đơn sắc khác (Đen, trắng, xám):

| Color       | Hex      | RGB           |
|-------------|----------|---------------|
| Vàng        | `#ffe700`| (255,231,0)   |
| Xanh lá 1   | `#00e56b`| (0,229,107)   |
| Xanh lá 2   | `#00b253`| (0,178,83)    |
| Xanh dương 1| `#2fcbff`| (47,203,255)  |
| Xanh dương 2| `#2f63ff`| (47,99,255)   |

---

## Câu 1 (2 điểm)
• Tạo một trang HTML (`cau1.html`) cho một website học tiếng Anh, tên của website là “English Learning”, Logo sử dụng ảnh vector (ảnh nhúng code) hoặc sử dụng ảnh svg, tạo ra một header cho website với các thẻ phù hợp.  
• Tạo ra một navigation phù hợp cho website này bằng cách sử dụng các thẻ `<div>`, đặt navigation dưới header nói trên.  
• Thêm một bài viết giới thiệu về 1 khóa học tiếng Anh, trong đó có sử dụng các thẻ `<h2>`, `<img>`, `<strong>` và các thẻ khác (nếu cần).

---

## Câu 2 (2 điểm)
• Tạo ra 1 trang HTML (`cau2.html`) trong đó có 4 phần tử `<div>`, phần tử này có thuộc tính class là “item”; 1 phần tử `<div>` khác có thuộc tính class là “advert”.  
• Tạo CSS cho class `item` với các thuộc tính độ rộng, chiều cao, màu nền. Tạo CSS cho class `advert` với độ rộng 100%, chiều cao 200px, đường viền 2px, kiểu nét liền, có dùng màu nền và màu viền khác với màu khai báo trong lớp `item`.

---

## Câu 3 (2 điểm)
• Tạo chuỗi JSON chứa 4 đối tượng là 4 bài giới thiệu về 4 khóa học tiếng Anh, mỗi bài viết bao gồm các thông tin như: tên khóa học, mô tả, học phí, thời gian khai giảng,...  
• Sử dụng vòng lặp `while` để in các đối tượng trên ra trang HTML (`cau3.html`), thông tin mỗi đối tượng để trong 1 thẻ `<div>`.

---

## Câu 4 (2 điểm)
• Tạo ra 1 trang HTML (`cau4.html`) trong đó có 1 form đăng ký khóa học với các thông tin: Họ và tên, Địa chỉ email, Số điện thoại, Khóa học muốn đăng ký, Thời gian ưu tiên học. Viết mã JS kiểm tra data trước khi submit.  
• Thiết kế trang web này đáp ứng với các thiết bị khác nhau tương ứng với các kích thước (Điện thoại - 414px, Máy bảng - 1024px, Máy tính - 1440px).

---

## Câu 5 (2 điểm)
Kết hợp những mã đã viết ở các câu trên, chỉnh sửa nó để tạo thành một Website hoàn thiện hơn và có tính thẩm mỹ, website có thiết kế đáp ứng và được lưu trong file `cau5.html`:  
• Website sử dụng header, navigation trong câu 1 để làm phần đầu của trang, bổ sung thêm 1 slogan bên dưới tên Website.  
• Phần navigation có liên kết đến các file HTML trong các câu 1-4 đã làm.  
• Sử dụng CSS `advert` ở câu 2 để tạo một khối thông tin quảng cáo, khi người dùng di chuột qua thì màu nền và màu viền thay đổi, phần chữ chuyển sang in nghiêng.  
• Sử dụng mã JS để hiển thị 4 khóa học đã khai báo trong câu 3, sử dụng CSS `item` ở câu 2, và `flexbox` để cấu hình cho 4 “item” này xuất hiện trên 1 hàng, căn giữa màn hình.  
• Đưa form đã thiết kế trong câu 4 vào Website này.

---
