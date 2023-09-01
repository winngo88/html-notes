# HTML5 - NOTES - Ghi lại những lưu ý khi làm việc với HTML5
## Định nghĩa, khái niệm
- Viết tắt là *Hyper Text Markup Language*
- Mô tả cấu trúc của một trang web
- Bao gồm một danh sách các phần tử (element), các phần tử cho trình duyệt biết cách hiển thị nội dung trang web
- Các phần tử có tác dụng dán nhãn nội dung, ví dụ như "tiêu đề", "đoạn văn", "liên kết", ...
- Một trang html đơn giản:
  ```
  <!DOCTYPE html> <!--khai báo này chỉ định rằng đây là tài liệu 'html5'-->
  <html>  <!--là phần tử (element) gốc của 1 trang html-->
  <head> <!--chứa thông tin meta về trang html-->
  <title>Page Title</title> <!--chỉ định tiêu đề cho trang html (hiển thị trên thanh tiêu đề của trình duyệt hoặc trong tab của trang)-->
  </head>
  <body> <!--phần tử xác định nội dung của tài liệu và là nơi chứa tất cả nội dung hiển thị, chẳng hạn như tiêu đề, đoạn văn, hình ảnh, siêu liên kết, bảng, danh sách, v.v.-->
  
  <h1>My First Heading</h1>  <!--phần tử xác định một tiêu đề lớn-->
  <p>My first paragraph.</p> <!--phần tử xác định một đoạn văn-->
  
  </body>
  </html>
  ```
## TIPS
- Tạo nhanh nội dung trang html trong Visual Studio Code bằng cách nhập **html:5**, sau đó bấm **Tab**
