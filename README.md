# Con Cưng UI Improvement 

## 1. Giới thiệu dự án

**Con Cưng UI Improvement** là bài tập cá nhân thuộc học phần **Phát triển ứng dụng WEB/TMĐT**, Buổi 2: HTML & CSS.

Dự án tiếp tục phát triển giao diện website từ bài tập Buổi 1, tập trung vào việc vận dụng HTML5 và CSS3 để cải thiện cấu trúc, cách trình bày và trải nghiệm quan sát sản phẩm trên giao diện.

Website được xây dựng dưới dạng giao diện tĩnh bằng HTML và CSS, không sử dụng cơ sở dữ liệu hoặc chức năng xử lý giao dịch thực tế.

## 2. Website tham khảo và khu vực cải tiến

- **Website tham khảo:** [Con Cưng](https://concung.com/)
- **Khu vực được lựa chọn:** Danh sách sản phẩm.
- **Phạm vi cải tiến:** Khu vực hiển thị thông tin sản phẩm, bao gồm hình ảnh, tên sản phẩm, giá bán và liên kết tham khảo sản phẩm.

Giao diện được xây dựng dựa trên website Con Cưng, với mục tiêu giúp các sản phẩm được trình bày rõ ràng, có bố cục thống nhất và thuận tiện hơn khi quan sát.

## 3. Công nghệ và kỹ thuật sử dụng

### 3.1. HTML5

Các phần tử HTML được sử dụng để tổ chức nội dung và phân chia cấu trúc giao diện:

- `header`: Khu vực đầu trang.
- `nav`: Khu vực chứa các liên kết điều hướng.
- `main`: Nội dung chính của trang.
- `section`: Phân chia các khu vực nội dung.
- `article`: Đại diện cho từng thẻ sản phẩm.
- `footer`: Khu vực chân trang.
- `img`: Hiển thị hình ảnh sản phẩm, có sử dụng thuộc tính `alt`.
- `a`: Tạo liên kết tham khảo sản phẩm.

### 3.2. CSS3

Các kỹ thuật CSS được vận dụng trong quá trình cải tiến giao diện:

- **CSS Selector:** Sử dụng element selector, class selector và descendant selector để lựa chọn và định dạng các phần tử HTML.
- **Box Model:** Điều chỉnh `margin`, `padding`, `border`, `border-radius` và `box-sizing` nhằm kiểm soát kích thước, khoảng cách và hình thức của thẻ sản phẩm.
- **Flexbox:** Sử dụng để căn chỉnh các thành phần trong khu vực được lựa chọn.
- **CSS Grid:** Tổ chức danh sách sản phẩm theo dạng lưới, kiểm soát số cột và khoảng cách giữa các sản phẩm.
- **Hover và Transition:** Tạo hiệu ứng khi người dùng di chuyển con trỏ chuột đến thẻ sản phẩm hoặc các thành phần tương tác.
- **Focus-visible:** Hỗ trợ nhận biết trạng thái của các phần tử có thể tương tác khi sử dụng bàn phím.
- **Responsive Design:** Điều chỉnh bố cục để giao diện phù hợp với các kích thước màn hình khác nhau.

## 4. Những thay đổi đã thực hiện

So với giao diện ban đầu, dự án tập trung cải thiện các nội dung sau:

1. Tổ chức lại cấu trúc HTML theo các phần tử HTML5 có ngữ nghĩa.
2. Tách phần định dạng giao diện thành tệp CSS riêng và liên kết với trang HTML.
3. Cải thiện cách trình bày thẻ sản phẩm thông qua màu sắc, font chữ, khoảng cách, đường viền và góc bo.
4. Điều chỉnh bố cục danh sách sản phẩm bằng CSS Grid.
5. Sử dụng Flexbox để căn chỉnh các thành phần trong khu vực được lựa chọn.
6. Bổ sung hiệu ứng hover, transition và trạng thái focus-visible.
7. Điều chỉnh giao diện để phù hợp với nhiều kích thước màn hình.

## 5. Hướng dẫn chạy website

### Yêu cầu

- Visual Studio Code hoặc trình soạn thảo mã nguồn tương đương.
- Trình duyệt web như Google Chrome, Microsoft Edge hoặc Firefox.

### Các bước thực hiện

1. Tải repository về máy hoặc mở thư mục dự án trong Visual Studio Code.
2. Kiểm tra cấu trúc thư mục và bảo đảm các tệp HTML, CSS và hình ảnh được đặt đúng vị trí.
3. Mở tệp `index.html` bằng trình duyệt để xem giao diện website.

Có thể sử dụng tiện ích Live Server trong Visual Studio Code để chạy và theo dõi các thay đổi trên trình duyệt.

## 6. Cấu trúc thư mục

```text
con-cung-ui-improvement/
│
├── index.html
├── css/
│   └── style.css
│
├── images/
│   ├── product-1.jpg
│   ├── product-2.jpg
│   ├── product-3.jpg
│   └── product-4.jpg
│
├── README.md
└── AI_USAGE.md
```

## 7. Kiểm thử giao diện

Sau khi hoàn thiện, giao diện được kiểm tra trên trình duyệt nhằm phát hiện các vấn đề về bố cục, kích thước và khả năng hiển thị.

### 7.1. Các kích thước màn hình kiểm thử

| Kích thước | Thiết bị tham chiếu | Kết quả kiểm tra |
|---|---|---|
| 1366px | Máy tính | [Bổ sung kết quả thực tế] |
| 768px | Máy tính bảng | [Bổ sung kết quả thực tế] |
| 390px | Điện thoại | [Bổ sung kết quả thực tế] |

### 7.2. Các vấn đề phát hiện và cách khắc phục

| Vấn đề phát hiện | Nguyên nhân | Hướng khắc phục |
|---|---|---|
| [Ghi vấn đề thực tế 1] | [Nguyên nhân] | [Cách sửa] |
| [Ghi vấn đề thực tế 2] | [Nguyên nhân] | [Cách sửa] |
| [Ghi vấn đề thực tế 3] | [Nguyên nhân] | [Cách sửa] |

### 7.3. Hình ảnh minh họa

- **Giao diện trước khi cải tiến:** [Bổ sung ảnh hoặc đường dẫn ảnh]
- **Giao diện sau khi cải tiến:** [Bổ sung ảnh hoặc đường dẫn ảnh]

## 8. Sử dụng AI trong quá trình thực hiện

AI được sử dụng như một công cụ hỗ trợ học tập trong quá trình phân tích mã nguồn, tìm hiểu cú pháp HTML5/CSS3 và đề xuất hướng cải thiện giao diện.

Các nội dung có sử dụng AI bao gồm:

- Hỗ trợ rà soát cấu trúc HTML và cách sử dụng các phần tử HTML5.
- Giải thích cách hoạt động của CSS Selector và Box Model.
- Hướng dẫn vận dụng Flexbox và CSS Grid.
- Hỗ trợ tìm hiểu hiệu ứng hover, transition và responsive design.
- Hỗ trợ phát hiện nguyên nhân của một số vấn đề hiển thị và đề xuất hướng khắc phục.

Các nội dung do AI đề xuất không được áp dụng một cách máy móc. Mã nguồn được kiểm tra lại trên Visual Studio Code và trình duyệt; các phần chưa phù hợp được điều chỉnh để đáp ứng yêu cầu của bài tập và cấu trúc thực tế của dự án.

Chi tiết các prompt đã sử dụng, kết quả nhận được và phần tự kiểm tra, điều chỉnh được trình bày trong tệp [`AI_USAGE.md`](AI_USAGE.md).

## 9. Giới hạn của sản phẩm

Đây là giao diện tĩnh được xây dựng nhằm thực hành HTML5 và CSS3. Các thành phần như tìm kiếm, lọc danh mục, sắp xếp sản phẩm và liên kết tham khảo hiện chưa được tích hợp chức năng xử lý dữ liệu thực tế.

## 10. Thông tin repository

- **Tên dự án:** Con Cưng UI Improvement
- **Học phần:** Phát triển ứng dụng WEB/TMĐT
- **Nội dung:** Bài tập cá nhân Buổi 2 – HTML & CSS
- **GitHub Repository:** https://github.com/Hagiang546/con-cung-ui-improvement