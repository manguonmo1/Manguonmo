PHẦN 1: NGÔN NGỮ LẬP TRÌNH JAVA

1. Ngôn ngữ lập trình Java
Java (đọc như "Gia-va") là một ngôn ngữ lập trình hướng đối tượng và dựa trên các lớp (class). Khác với phần lớn ngôn ngữ lập trình thông thường, thay vì biên dịch mã nguồn thành mã máy hoặc thông dịch mã nguồn khi chạy, Java được thiết kế để biên dịch mã nguồn thành bytecode, bytecode sau đó sẽ được chạy trong môi trường thực thi (runtime environment).
Trước đây, Java chạy chậm hơn những ngôn ngữ dịch thẳng ra mã máy như C và C++, nhưng sau này nhờ công nghệ "biên dịch tại chỗ" - Just in time compilation, khoảng cách này đã được thu hẹp, và trong một số trường hợp đặc biệt Java có thể chạy nhanh hơn. Java chạy nhanh hơn những ngôn ngữ thông dịch như Python, Perl, PHP gấp nhiều lần. Java chạy tương đương so với C#, một ngôn ngữ khá tương đồng về mặt cú pháp và quá trình dịch/chạy.
Cú pháp Java được vay mượn nhiều từ C & C++ nhưng có cú pháp hướng đối tượng đơn giản hơn và ít tính năng xử lý cấp thấp hơn. Do đó việc viết một chương trình bằng Java dễ hơn, đơn giản hơn, đỡ tốn công sửa lỗi hơn.
2. Lịch sử hình thành
Java được khởi đầu bởi James Gosling và bạn đồng nghiệp ở Sun Microsystems năm 1991. Ban đầu ngôn ngữ này được gọi là Oak (có nghĩa là cây sồi; do bên ngoài cơ quan của ông Gosling có trồng nhiều loại cây này), họ dự định ngôn ngữ đó thay cho C++, nhưng các tính năng giống Objective C. Không nên lẫn lộn Java với JavaScript, hai ngôn ngữ đó chỉ giống tên và loại cú pháp như C. Công ty Sun Microsystems đang giữ bản quyền và phát triển Java thường xuyên. Tháng 04/2011, công ty Sun Microsystems tiếp tục cho ra bản JDK 1.6.24.
Java được tạo ra với tiêu chí "Viết (code) một lần, thực thi khắp nơi" ("Write Once, Run Anywhere" (WORA)). Chương trình phần mềm viết bằng Java có thể chạy trên mọi nền tảng (platform) khác nhau thông qua một môi trường thực thi với điều kiện có môi trường thực thi thích hợp hỗ trợ nền tảng đó. Môi trường thực thi của Sun Microsystems hiện hỗ trợ Sun Solaris, Linux, Mac OS, FreeBSD & Windows. Ngoài ra, một số công ty, tổ chức cũng như cá nhân khác cũng phát triển môi trường thực thi Java cho những hệ điều hành khác như BEA, IBM, HP.... Trong đó đáng nói đến nhất là IBM Java Platform hỗ trợ Windows, Linux, AIX & z/OS.
Java được sử dụng chủ yếu trên môi trường NetBeans và Oracle. Sau khi Oracle mua lại công ty Sun Microsystems năm 2009-2010, Oracle đã mô tả họ là "người quản lý công nghệ Java với cam kết không ngừng để bồi dưỡng một cộng đồng tham gia và minh bạch".
3. Phương châm
Có 5 mục tiêu chính trong việc xây dựng ngôn ngữ Java:
- Đơn giản, hướng đối tượng và quen thuộc.
- Mạnh mẽ và an toàn.
- Kiến trúc trung lập và di động.
- Thực thi với hiệu suất cao.
- Dịch ra bytecode, phân luồng và năng động.
4. Phiên bản
Các phiên bản Java đã phát hành:
•	JDK 1.0 (23 tháng 01, 1996)
•	JDK 1.1 (19 tháng 2 năm 1997)
•	JDK 1.1.5 (Pumpkin) 03 tháng 12 năm 1997
•	JDK 1.1.6 (Abigail) 24 tháng 4 năm 1998
•	JDK 1.1.7 (Brutus) 28 tháng 9 năm 1998
•	JDK 1.1.8 (Chelsea) 08 tháng 4 năm 1999
•	J2SE 1.2 (Playground) 08 tháng 12 năm 1998
•	J2SE 1.2.1 (không có) 30 tháng 3 năm 1999
•	J2SE 1.2.2 (Cricket) 08 tháng 7 năm 1999
•	J2SE 1.3 (Kestrel) 08 tháng 5 năm 2000
•	J2SE 1.3.1 (Ladybird) 17 tháng 5 năm 2001
•	J2SE 1.4.0 (Merlin) 06 tháng 02, 2002
•	J2SE 1.4.1 (Hopper) 16 tháng 9 năm 2002
•	J2SE 1.4.2 (Mantis) 26 tháng 6 năm 2003
•	J2SE 5 (1.5.0) (Tiger) 30 tháng 9 năm 2004
•	Java SE 6 (còn gọi là Mustang), được công bố 11 tháng 12 năm 2006, thông tin chính tại http://java.sun.com/javase/6/. Các bản cập nhật 2 và 3 được đưa ra vào năm 2007, bản cập nhật 4 đưa ra tháng 1 năm 2008.
•	JDK 6.18, 2010
•	Java SE 7 (còn gọi là Dolphin), được bắt đầu từ tháng 8 năm 2006 và công bố ngày 28 tháng 7 năm 2011.
•	JDK 8, 18 tháng 3 năm 2014
5. Ưu nhược điểm
Ưu điểm:
•	Java cũng là một mã nguồn mở rõ ràng.
•	Khi sử dụng Java giúp bạn tiết kiệm thời gian viết code vì có sự hỗ trợ đắc lực của Visual Studio.
•	Java cũng rất đơn giản, dễ học bạn không cần mất nhiều thời gian để tìm hiểu.
•	Ưu điểm nổi bật của Java là độc lập với hệ thống xử lý và hệ điều hành nên nó có thể hoạt động trên bất cứ một môi trường nào.
•	Cộng đồng của Java khá nhiều nên bạn sẽ có nhiều sự hỗ trợ mỗi khi cần thiết.
Nhược điểm:
•	Nhược điểm lớn nhất của Java là tốc độ chậm.
•	Tính bảo mật của mã nguồn sourcecode không cao.

 
PHẦN 2: KHẢO SÁT, PHÂN TÍCH VÀ THIẾT KẾ PHẦN MỀM
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
 
PHẦN 3: XÂY DỰNG HỆ THỐNG

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

Phần chưa hoàn thiện
- Form doanh thu: chưa hoàn thiện

![doanhthu](https://user-images.githubusercontent.com/27817852/28253827-b3e1eab4-6ad1-11e7-939a-9aafddefbd51.png)
- Form liên hệ: chưa hoàn thiện

![lienhe](https://user-images.githubusercontent.com/27817852/28253832-bde2dd8e-6ad1-11e7-9eda-338e80fa2f7e.png)
