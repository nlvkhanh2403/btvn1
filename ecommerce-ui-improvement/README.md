# E-commerce UI Improvement

## 1. Giới thiệu

Đây là bài tập cải tiến giao diện thương mại điện tử dựa trên việc khảo sát website **Cái Lò Nướng**.

Website mẫu tập trung vào giao diện **chi tiết sản phẩm bánh**, giúp người dùng xem hình ảnh, thông tin sản phẩm, lựa chọn kích thước, quà tặng kèm, số lượng và thực hiện thao tác thêm sản phẩm vào giỏ hàng.

Phần cải tiến tập trung vào việc sắp xếp lại bố cục và thông tin trên trang chi tiết sản phẩm nhằm giúp giao diện dễ quan sát, rõ ràng và thuận tiện hơn khi mua hàng.

---

## 2. Website tham khảo

- **Tên website:** Cái Lò Nướng
- **URL:** https://cailonuong.com/
- **Khu vực đã khảo sát:**
  - Trang chủ
  - Danh mục sản phẩm
  - Chi tiết sản phẩm
  - Tìm kiếm
  - Giỏ hàng

Website Cái Lò Nướng cung cấp các sản phẩm như bánh mousse, bánh kem bắp, bánh flan gato, cookie, bánh mì và combo bánh. Các chức năng chính gồm tìm kiếm, duyệt danh mục, xem chi tiết sản phẩm, thêm vào giỏ hàng và đặt hàng. 

---

## 3. Chức năng

Giao diện được xây dựng với các chức năng chính:

- Hiển thị thông tin chi tiết sản phẩm.
- Hiển thị hình ảnh và album ảnh sản phẩm.
- Hiển thị tên, mô tả và giá sản phẩm.
- Lựa chọn kích thước sản phẩm.
- Lựa chọn quà tặng kèm.
- Điều chỉnh số lượng sản phẩm.
- Thêm sản phẩm vào giỏ hàng.
- Hiển thị số lượng sản phẩm trong giỏ hàng.
- Hiển thị các sản phẩm liên quan.
- Bố cục responsive, hỗ trợ nhiều kích thước màn hình.

> Lưu ý: Đây là giao diện demo, không sử dụng backend hoặc cơ sở dữ liệu.

---

## 4. Công nghệ

- HTML5
- CSS3
- JavaScript cơ bản

HTML được sử dụng để xây dựng cấu trúc trang, CSS dùng để định dạng giao diện và responsive, JavaScript cơ bản được sử dụng cho một số tương tác như chuyển ảnh, thay đổi kích thước bánh, điều chỉnh số lượng và cập nhật số lượng sản phẩm trong giỏ hàng.

---

## 5. Cách chạy

### Cách 1: Mở trực tiếp bằng trình duyệt

1. Clone hoặc tải repository về máy.
2. Mở thư mục dự án.
3. Mở file `index.html` bằng trình duyệt.
4. Có thể sử dụng Chrome hoặc Microsoft Edge để kiểm tra giao diện.

### Cách 2: Sử dụng VS Code

1. Mở thư mục dự án bằng Visual Studio Code.
2. Mở file `index.html`.
3. Chọn **Open with Live Server** nếu đã cài extension Live Server.
4. Kiểm tra giao diện trên trình duyệt.

---

## 6. Cải tiến đã thực hiện

### 6.1. Vấn đề ban đầu

Qua quá trình khảo sát, trang chi tiết sản phẩm có lượng thông tin tương đối nhiều và hình ảnh sản phẩm chiếm diện tích lớn. Điều này có thể khiến khách hàng khó quan sát tổng thể và khó xác định nhanh các thông tin quan trọng trước khi mua.

Ngoài ra, phần quà tặng kèm chưa thể hiện thật rõ mối quan hệ với sản phẩm chính.

### 6.2. Phương án cải tiến

Giao diện được cải tiến theo 3 hướng chính:

1. **Tối ưu bố cục hình ảnh sản phẩm**
   - Sử dụng bố cục hai cột.
   - Hình ảnh chính được đặt ở khu vực dễ quan sát.
   - Bổ sung album ảnh và thumbnail để xem nhiều hình ảnh.

2. **Sắp xếp lại thông tin mua hàng**
   - Làm nổi bật tên sản phẩm và giá.
   - Gom các lựa chọn kích thước vào một khu vực riêng.
   - Đặt số lượng và nút "Thêm vào giỏ hàng" ở vị trí dễ nhận biết.

3. **Cải thiện khu vực quà tặng kèm**
   - Tách khu vực quà tặng khỏi các thông tin khác.
   - Hiển thị rõ tên quà tặng và trạng thái miễn phí.
   - Giúp người dùng dễ hiểu rằng đây là lựa chọn đi kèm sản phẩm chính.

### 6.3. Điều chỉnh sau khi kiểm tra

Sau khi kiểm tra giao diện trên trình duyệt, em nhận thấy một số hình ảnh sản phẩm chưa phù hợp với sản phẩm được lựa chọn. Vì vậy, em đã chỉnh sửa mã HTML để thay thế các đường dẫn hình ảnh bằng hình ảnh phù hợp hơn.

Ngoài ra, phần nhận diện thương hiệu cũng được rà soát và điều chỉnh để phù hợp với website tham khảo.

Kết quả là giao diện có hình ảnh phù hợp hơn với nội dung sản phẩm và tổng thể trang thống nhất hơn với website tham khảo.

---

## 7. Hỗ trợ từ AI

AI được sử dụng trong quá trình thực hiện bài tập với vai trò hỗ trợ phân tích và phát triển giao diện.

### AI hỗ trợ:

- Phân tích cấu trúc và chức năng của website tham khảo.
- Xác định các vấn đề có thể cải thiện về UI/UX.
- Đề xuất phương án bố trí lại trang chi tiết sản phẩm.
- Đề xuất cách tổ chức thông tin sản phẩm.
- Hỗ trợ viết và giải thích HTML/CSS.
- Hỗ trợ xử lý responsive cho máy tính và điện thoại.
- Hỗ trợ kiểm tra và đề xuất chỉnh sửa giao diện.

### Phần tự kiểm tra và điều chỉnh:

Các đề xuất từ AI được đối chiếu với website thực tế trước khi áp dụng. Những nhận xét không có đủ bằng chứng từ website được ghi nhận là chưa thể xác minh hoặc không sử dụng.

Sau khi tạo giao diện, em trực tiếp kiểm tra kết quả trên trình duyệt và tự điều chỉnh các nội dung chưa phù hợp, đặc biệt là hình ảnh sản phẩm và nhận diện thương hiệu.

---

## 8. Cấu trúc thư mục

```text
btvn1/
│
├── index.html
├── btvn1.css
├── README.md
└── image/
    ├── banh-kem-20-10-tang-me-1.jpg
    ├── banh-kem-20-10-tang-me-2.jpg
    ├── banh-kem-20-10-tang-me-3.jpg
    └── ...
