# extensionVSC

setUp:
beforeCreate: trước khi khởi tạo đối tượng Vue.
created: được gọi khi đối tượng Vue khởi tạo hoàn thành. Tại đã có this rồi.
beforeMount: được gọi trước khi khởi tạo DOM đầu tiên. Mục đích sử dụng: khởi tạo các sự kiện(event) cho các thành phần trong DOM.
mounted: được gọi khi khởi tạo DOM thành công. Mục đích sử dụng: gọi xuống server lấy dữ liệu để binding lên DOM.
beforeUpdate: được gọi trước khi DOM được cập nhật do có sự thay đổi về reactive state. Mục đích sử dụng: 
updated: được gọi khi DOM đã được cập nhật do có sự thay đổi về reactive state. Mục đích sử dụng: 
beforeUnmount: được gọi khi chuẩn bị dừng dùng component và có đầy đủ các thành phần của đối tượng. Mục đích sử dụng: sử dụng để xử lý các tác vụ liên quan đến.
unmounted: Mục đích sử dụng: xóa đi các sự kiện DOM đã khai báo ở beforeMount nếu có.
