# HTML5 - NOTES - Ghi lại những lưu ý khi làm việc với HTML5
## Định nghĩa
- Viết tắt là *Hyper Text Markup Language*
- Mô tả cấu trúc của một trang web
- Bao gồm một danh sách các phần tử (element), các phần tử cho trình duyệt biết cách hiển thị nội dung trang web
- Các phần tử có tác dụng dán nhãn nội dung, ví dụ như "tiêu đề", "đoạn văn", "liên kết", ...
### Một trang html đơn giản:
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
### Phần tử (element) là gì?
- Một phần tử html được xác định bởi thẻ (**tag**) bắt đầu, một số nội dung và thẻ kết thúc:  
  ```<tagname> Nội dung ... </tagname>```
- Phần tử html là mọi thứ từ thẻ bắt đầu đến thẻ kết thúc:
  ```
  <h1>Tiêu đề đầu tiên của tôi</h1>
  
  <p>Đoạn đầu tiên của tôi.</p>
  ```
- Lưu ý: Một số phần tử html không có nội dung (như phần tử <**br**>). Những phần tử này được gọi là phần tử rỗng. Các phần tử rỗng không có thẻ kết thúc.
### Trình duyệt web
- Mục đích của trình duyệt web (Chrome, Edge, Firefox, Safari) là đọc tài liệu HTML và hiển thị chúng một cách chính xác.
- Trình duyệt không hiển thị các thẻ HTML nhưng sử dụng chúng để xác định cách hiển thị tài liệu:
## TIPS
- Tạo nhanh nội dung trang html trong Visual Studio Code bằng cách nhập **html:5**, sau đó bấm **Tab**
