
# LẬP TRÌNH  FRONT-END

### I. NỘI DUNG TÌM HIỂU

##### 1. ES6 là gì?

###### - ES6 là chữ viết tắt của ECMAScript 6, là phiên bản mới nhất của chuẩn ECMAScript. ECMAScript do hiệp hội các nhà sản xuất máy tính Châu Âu đề xuất làm tiêu chuẩn của ngôn ngữ Javascript. Bạn cứ nghĩ xem hiện nay có khá nhiều trình duyệt Browser ra đời và nếu mỗi Browser lại có cách chạy Javascript khác nhau thì các trang web không thể hoạt động trên tất cả các trình duyệt đó được, vì vậy cần có một chuẩn chung để bắt buộc các browser phải phát triển dựa theo chuẩn đó.
######  ES6 ra đời vào năm 2015 nên cái tên ES2015 được lấy làm tên chính thức với nhiều tính năng mới học hỏi các ngôn ngữ cấp cao khác.

######  -Biến (const) trong ES6: dùng để khai báo một hằng số - là một giá trị không thay đổi được trong suốt quá trình chạy.
######  - (let) tạo ra một biến chỉ có thể truy cập được trong block bao quanh nó, khác với (let) 
######  (var) - tạo ra một biến có phạm vi truy cập xuyên suốt function chứa nó.

######  Sử dụng var:

```javascript
function foo() {
   var x = 10;
   if (true) {
      var x = 20; // x ở đây cũng là x ở trên
      console.log(x); // in ra 20
   }
   console.log(x); // vẫn là 20
}
```
