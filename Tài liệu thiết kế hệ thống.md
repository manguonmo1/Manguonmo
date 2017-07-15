PHẦN 1: KHẢO SÁT, PHÂN TÍCH VÀ THIẾT KẾ PHẦN MỀM
1.	Khảo sát hiện trạng
	Khảo sát và tìm hiểu hệ thống hiện tại mà khách hang đang làm việc
	Các quy tắc quản lý của cửa hàng: 
	Quản lý hàng nhập về: gồm có mã sản phẩm, tên sản phẩm, số lượng, nhà cung cấp, đơn giá, tổng tiền.
	Quản lý hàng bán ra: gồm có mã sản phẩm, tên sản phẩm, số lượng, nhà cung cấp, đơn giá, tổng tiền, tên khách hàng
	Quản lý tài chính: gồm có tổng tiền đã chi, tổng tiền đã thu và lãi suất thu được.
	Quản lý nhân viên: gồm có mã nhân viên, tên nhân viên, địa chỉ, ngày sinh, giới tính, chức vụ, số điện thoại.
	Quản lý khách hàng: gồm mã số khách, tên khách hàng, địa chỉ, số điện thoại, loại khách hàng…
	Các công thức và quy định:
	Công thức tính lãi = tổng thu – tổng chi
	Các quy định về hàng hóa:
•	Mặt hàng bán chạy nhất là mặt hàng bán được với số lượng nhiều nhất trong tháng.
•	Mặt hàng còn tồn là mặt hàng bán được ít hơn 1/5 số tổng lượng nhập về.
	Các đòi hỏi yêu cầu của công việc mà người sử dụng hệ thống yêu cầu bao gồm:
	Khả năng lưu trữ, cập nhật, hiển thị, tìm kiếm thông tin hàng hóa
	Khả năng thống kê được danh sách các mặt hàng hiện có, đã hết, tồn, hay bán chạy nhất… khả năng thống kê lãi suất, doanh thu.
	Chương trình chạy được trên môi trường nguồn mở
	Các thao tác thực hiện dễ dàng, thuận tiện.
	Các nguồn thông tin điều tra
	Tìm thông tin qua tham khảo các phần mềm trên mạng, từ sách báo sổ sách tài liệu và các cửa hàng kinh doanh giày dép khác…
	Phương pháp điều tra
	Nghiên cứu tài liệu viết trên mạng
	Quan sát hoạt động của một số hệ thống đã có
	Phỏng vấn trực tiếp một số chủ cửa hàng

2. Phân tích hệ thống
2.1 Biểu đồ phân cấp chức năng
![bi u d phan c p ch c nang](https://user-images.githubusercontent.com/27817852/28237690-a430d5de-696f-11e7-922a-f17f1af64fab.png)

2.2 Phân tích về biểu đồ phân cấp chức năng
a. Đặc tả về chức năng
	Chương trình có khả năng lưu trữ, cập nhật thông tin về các loại giày dép, nhân viên và khách hàng.
	Chương trình có khả năng cho phép xem danh sách các loại giày dép hiện có trong cửa hàng.
	Cho phép tìm kiếm thông tin về các chủng loại giày dép có trong cửa hàng.
	Thống kê doanh thu, lãi suất bán hàng.
	Thông tin có thể được in ra máy.


b. Phân tích hệ thống chức năng
	Cập nhật thông tin
-	Nhập hàng mới:
	Tên sản phẩm
	Mã sản phẩm
	Mã nhà cung cấp
	Số lượng
	Đơn giá
	Tổng tiền
	Ngày nhập
-	Nhập thông tin nhân viên
	Tên nhân viên
	Mã nhân viên
	Địa chỉ
	Số điện thoại
	Giới tính
-	Nhập thông tin khách hàng
	Tên khách hàng
	Mã khách hàng
	Địa chỉ
	Số lượng
	Loại khách hàng
-	Nhập thông tin nhà cung cấp
	Mã nhà cung cấp
	Tên nhà cung cấp
	Địa chỉ
	Email
	Số điện thoại
-	Sửa đổi thông tin:
	Xóa thông tin: Lấy nội dung thông tin từ kho dữ liệu và xóa khỏi danh sách
	Bổ sung thông tin
	Thay đổi thông tin
	Tìm kiếm thông tin
	Tìm kiếm theo nhà cung cấp, tên sản phẩm, giá,…
	Thống kê
	Thống kê nhập-xuất hàng
	Thống kê tổng doanh thu, lãi suất, số nợ
	Thống kê hàng tồn, hàng bán chạy
	Thống kê quản lý nhân viện
	Thống kê quản lý khách hàng
	In ấn
	In hóa đơn
2.	Biểu đồ luồng dữ liệu
-	Mức bối cảnh

 ![m c b i c nh](https://user-images.githubusercontent.com/27817852/28237713-53d18c9a-6970-11e7-9bbb-6fcda7093e8e.png)
 
-	Mức đỉnh

 ![m c d nh](https://user-images.githubusercontent.com/27817852/28237720-710bc9a6-6970-11e7-9138-e2993d0a39ee.png)

 
3.	Thiết kế cơ sở dữ liệu
-	Sản phẩm

 ![csdlsp](https://user-images.githubusercontent.com/27817852/28237722-7f6de830-6970-11e7-84df-a26a1252ef81.png)

-	Loại sản phẩm

 ![lo i sp](https://user-images.githubusercontent.com/27817852/28237730-9d408246-6970-11e7-81ad-8bd2b8661684.png)
 
-	Hóa đơn

 ![hoa d n](https://user-images.githubusercontent.com/27817852/28237737-ab7cee12-6970-11e7-8498-72cf0bd15cce.png)

-	Chi tiết hóa đơn

 ![cthd](https://user-images.githubusercontent.com/27817852/28237742-ba36ea2a-6970-11e7-9d04-9a18ef550e95.png)
 
-	Phiếu nhập

 ![phi u nh p](https://user-images.githubusercontent.com/27817852/28237750-c4d67bf8-6970-11e7-8f9e-3955808d5888.png)

-	Chi tiết phiếu nhập
 
![ct phi u nh p](https://user-images.githubusercontent.com/27817852/28237752-ce4a6dca-6970-11e7-9298-7d386a7350fd.png)

-	Chức vụ

 ![ch c v](https://user-images.githubusercontent.com/27817852/28237754-d8e4ec92-6970-11e7-9c63-2a45f7bb2633.png)


-	Hãng sản xuất
 
![hang s n xu t](https://user-images.githubusercontent.com/27817852/28237755-e19c475e-6970-11e7-86d0-18289b6de593.png)


-	Nhà phân phối

 ![nha phan ph i](https://user-images.githubusercontent.com/27817852/28237760-eaec16b8-6970-11e7-9186-44858b474c8a.png)
 
-	Khách hàng

 ![kh](https://user-images.githubusercontent.com/27817852/28237769-f8637296-6970-11e7-93d6-9f9bc491ebae.png)
-	Loại khách hàng

 ![lo i kh](https://user-images.githubusercontent.com/27817852/28237770-fce1d704-6970-11e7-8ed5-eedb38501e91.png)
-	Nhân viên

 ![nv](https://user-images.githubusercontent.com/27817852/28237773-09710198-6971-11e7-80bf-b76da0cf7ede.png)
-	Quyền

 ![quy n](https://user-images.githubusercontent.com/27817852/28237774-0f6376ee-6971-11e7-8a8e-21c3c9840bac.png)
-	User

 ![user](https://user-images.githubusercontent.com/27817852/28237776-125a5b74-6971-11e7-9a95-d1b34482d249.png)
4.	Biểu đồ dữ liệu quan hệ
 
![quan h](https://user-images.githubusercontent.com/27817852/28237778-2647a1dc-6971-11e7-8a7d-1a813f36956f.png)

 
5.	Thiết kế các biểu mẫu
-	Hóa đơn bán hàng

 ![bi u m u ban](https://user-images.githubusercontent.com/27817852/28237780-2f914d4c-6971-11e7-9488-2a03b0e89635.png)
 
-	Hóa đơn nhập hàng

 ![bi u m u nh p](https://user-images.githubusercontent.com/27817852/28237781-318830de-6971-11e7-97fc-e4337700c6fc.png)
 
PHẦN 2: XÂY DỰNG HỆ THỐNG

1.	Thiết kế giao diện
-	Form đăng nhập

 ![form dang nh p](https://user-images.githubusercontent.com/27817852/28237785-415e2158-6971-11e7-87e6-f62cacfb57e9.png)
-	Form đăng ký

 ![form dang ky](https://user-images.githubusercontent.com/27817852/28237787-427f6b1e-6971-11e7-9371-a25f076552de.png)
 
-	Form hóa đơn và chi tiết hóa đơn

 ![form hoa d n](https://user-images.githubusercontent.com/27817852/28237789-48846136-6971-11e7-8742-87b8345aa43c.png)
 
-	Form sản phẩm

 ![form sp](https://user-images.githubusercontent.com/27817852/28237791-4e480cee-6971-11e7-8892-4ef3aa5c7053.png)
 
-	Form khách hàng

 ![form kh](https://user-images.githubusercontent.com/27817852/28237805-aeb2a6f2-6971-11e7-9bd8-981af1474d4d.png)
 
-	Form nhân viên

 ![form nv](https://user-images.githubusercontent.com/27817852/28237806-b4b97ea4-6971-11e7-8350-dc1c42a33f9a.png)
 
-	Form đối tác (nhà phân phối)

 ![form d i tac](https://user-images.githubusercontent.com/27817852/28237807-b64e922c-6971-11e7-996f-9f6af550b30e.png)
 
-	Form doanh thu

 ![form doanh thu](https://user-images.githubusercontent.com/27817852/28237809-bad753f6-6971-11e7-8185-401f58846f06.png)
 
-	Form liên hệ

 ![form lien h](https://user-images.githubusercontent.com/27817852/28237810-bca430aa-6971-11e7-9bfb-3ed5e14b9fd0.png)


