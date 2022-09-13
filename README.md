# webpack-basic
Webpack là gì?
Để hiểu được webpack thì bạn phải biết lý do mà nó sinh ra.

Ngày xưa thuở mới học lập trình web thì chúng ta thường tạo 1 project với 3 file đơn giản là: index.html,style.css, app.js. Nhưng càng ngày thì css cũng như javascript càng phát triển, chúng ta SASS, LESS để biên dịch sang CSS, rồi các phiên bản Javascript mới hơn như ES6, ES2018, ES2019… Lúc này mới nảy sinh các vấn đề như sau:

Nếu anh em dùng cú pháp ES6 hay ES2018 thì các trình duyệt cũ chỉ hỗ trợ đến ES5 không thể hoạt động được
Viết code SASS, LESS thì trình duyệt không đọc được. Phải dùng một số công cụ chuyển đổi sang CSS như node-sass, Gulp, Koala,…
Viết code xong rồi còn phải nén code lại để giảm dung lượng code nhằm tăng tốc độ load trang
Khi thao tác ở môi trường dev, mỗi khi có thay đổi trên code, ta thường tự tay F5 để  reload lại trình duyệt. Nếu muốn tự động thì ta có thể dùng một số tool ngoài kia như Live Server trên VSCode,…
Bên trên là một số trong rất nhiều vấn đề mà anh em sẽ gặp phải và nếu mỗi vấn đề dùng mỗi công cụ thì không phải là lựa chọn tối ưu. Vì thế Webpack sinh ra để giải quyết tất cả vấn đề trên.

Webpack là một công cụ chạy trên môi trường NodeJs, giúp bạn đóng gói js, css, image, font… thành một hay nhiều file một cách dễ dàng.

tài liệu: https://xdevclass.com/webpack-sieu-toc-cau-hinh-dev-server-babel-loader-style-loader-file-loader/
