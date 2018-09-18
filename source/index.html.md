---
title: Document

<!-- language_tabs: # must be one of https://git.io/vQNgJ -->
  <!-- - shell
  - ruby
  - python
  - javascript -->

toc_footers:
  - <a href='#'>Copyright 2018</a>
  - <a href='#'>NHT</a>

<!-- includes: -->
  <!-- - errors -->

search: false
---

# Tổng Quan

Tài liệu hướng dẫn cơ bản các chức năng quản trị hệ thống Thiên Đường Gia Dụng dot com

Vì nền tảng xây dựng ecommerce Thiên Đường Gia Dụng dựa trên wordpress. Nên Cơ bản cần nắm 1 số khái niệm cơ bản để có thể sử dụng tốt platform này

# Đăng Nhập

Để Đăng Nhập, Dùng link sau : http://thienduonggiadung.com/wp-admin/
Chọn mục Log in with username and password

<aside class="notice">
  Liên hệ công ty để có thông tin tài khoản quản trị
</aside>

> ![alt text](images/1.png)
![alt text](images/2.png)

# Giao Diện

## Thay đổi Top Header

![alt text](images/top_header.png)


Thanh menu bar nằm góc trên phải để các link hữu dụng.

Cách Thay Đổi link và title:

`Left Menu -> Giao Diện -> Menu`

Chọn Menu có tên : Top Bar Menu -> `Chọn`


> ![alt text](images/3.png)

Trong màn hình này có thể sửa title, url, thêm / sửa / xoá menu hoặc submenu tuỳ ý.
Sau khi sửa xong, click `Lưu Menu` để hoàn tất.
> ![alt text](images/4.png)


## Thay Đổi Menu Chính
![alt text](images/main_menu.png)
Thanh menu bar chính nằm phía dưới logo.

Cách Thay Đổi link và title:

`Left Menu -> Giao Diện -> Menu`

Chọn Menu có tên : Main Menu -> `Chọn`


> ![alt text](images/main_menu_edit.png)

Trong màn hình này có thể sửa title, url, thêm / sửa / xoá menu hoặc submenu tuỳ ý.
Sau khi sửa xong, click `Lưu Menu` để hoàn tất.

> ![alt text](images/main_menu_edit2.png)


## Thay Đổi Header

Một số tuỳ chỉnh của header nằm trong mục `Left Menu -> Porto -> Theme Options`
![alt text](images/header.png)
### Logo

Vào mục `Chung -> Logo, Biểu Tượng`

Trong mục này có thể thay đổi hình ảnh logo cho web, cho sticky (trạng thái lúc scroll lên), cho mobile

Bạn cũng có thể thay đổi kích thước sao cho phù hợp 
>![alt text](images/logo_edit.png)


### Thay đổi màu sắc

Để thay đổi màu sắc của từng item trên header, bạn vào mục `Skin`
Mục Skin này thay đổi màu sắc, font chữ của toàn bộ các item trong Web

Đối với Header, thì bạn hãy chọn `Đầu Trang`, Menu chính thì  `Menu Chính`

>![alt text](images/header_edit_color.png)

### Thay Đổi Cấu hình Form Search
Vào mục `Đầu Trang -> Form Tìm Kiếm`
>![alt text](images/header_search_edit.png)

### Thay Đổi Text Hotline, thời gian làm việc
![alt text](images/header_hotline.png)

Vào mục `Đầu Trang` . Kéo xuống dưới mục Thông tin Liên Hệ

> ![alt text](images/header_hotline_edit.png)

## Thay Đổi Banner
Từ `Left Menu` chọn `LayerSlider -> All Sliders -> Home `
>![alt text](images/banner_edit.png)

Trong màn hình , gồm ba mục Settings của Slider, Sliders, và CallBack

>![alt text](images/slider/slider1.png)

### Slider Settings
Chỉnh sửa các thông số như width, height, loại, hiển thị navigation, chung chung của slider.

>![alt text](images/slider/slider2.png)


### Sliders
Chỉnh sửa các slider riêng lẻ.

Nếu không muốn active slider nào thì chọn chế độ `HIDE` trên từng slider
![alt text](images/slider/slider3.png)

### Thay Đổi Slider

Để Thêm 1 Slider, có thể thêm mới (Add New) trong Sliders. Hoặc có thể `Duplicate` SLider.

Thêm Layer `Image` hoặc `Text` để hiện thị theo ý muốn
>![alt text](images/slider/slider4.png)
> ![alt text](images/slider/slider5.png)



<aside class="notice">
  Xem thêm hướng dẫn sử dụng của LayerSlider tại https://layerslider.kreaturamedia.com/documentation/
</aside>


# Quản Lý Danh Mục

## Danh Mục Sản Phẩm
Vào Mục `Sản Phẩm` -> `Danh Mục` 
> ![alt text](images/woo/category.png)

## Thêm Danh Mục
Nhập **Tên** và chọn **Danh Mục Cha** nếu cần thiết
>![alt text](images/woo/category_add.png)

## Sửa Danh Mục

Rê chuột hoặc double click vào từng danh mục để sửa hoặc xoá
>![alt text](images/woo/category_edit.png)

# Quản Lý Sản Phẩm

Vào Mục `Sản Phẩm` -> `Tất Cả Sản Phẩm` để Thêm Xoá Sửa **Sản Phẩm**
>![alt text](images/woo/products.png)

## Thêm Sản Phẩm
Trên Cùng ở màn hình `Tất Cả Sản Phẩm`, chọn 'Thêm Mới' hoặc 'Nhập Vào' (import)
>![alt text](images/woo/products_add_new.png)
Thứ tự các bước cần thực hiện :

(1) Nhập Tên Sản Phẩm 

(2) Nhập Mô Tả Chi Tiết

(3) Chọn Danh mục sản phẩm

(4) Update Hình ảnh đại diện và hình ảnh sản phẩm

(5) Nhập Giá Bán Thường và Giá bán Khuyến Mãi (nếu Có)

(6) Trong mục kiểm kê kho hàng , nhập số lượng sản phẩm

(7) Đối với một số sản phẩm có nhiều màu, thêm ở phần `Các Thuộc Tính` của Sản Phẩm

(8) Nhập Mô tả ngắn của Sản Phẩm 

(9) Nhập từ khoá SEO của sản phẩm

Sau khi hoàn tất, nhấn Publish Sản Phẩm 


>![alt text](images/woo/products_add_full.png)

##Xoá sản phẩm 

Ở màn hình `Tất cả sản phẩm`, nhập mã sản phẩm cần tìm -> 'Tìm sản phẩm'

Di chuyển đến sản phẩm cần xoá -> `Xoá tạm`

>![alt text]()

#Quản lý thành viên

Vào mục `Thành viên` -> `Tất cả người dùng` để Thêm Xoá Sửa **Thành Viên**
>![alt text]()

##Thêm thành viên

Trên cùng ở màn hình `Tất cẩ người dùng`, chọn 'Thêm mới' 
>![alt text]()

Điền đầy đủ thông tin vào các trường 

Sau khi hoàn tất, nhấn 'Thêm người dùng mới'

##Xoá thành viên
Ở màn hình `Tất cả người dùng`, di chuyển đến thành viên cần xoá -> `xoá`
>![alt text]()
