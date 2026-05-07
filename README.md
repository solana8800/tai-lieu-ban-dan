Dưới đây là bản dịch tiếng Việt cho danh sách tài liệu của bạn, vẫn giữ nguyên định dạng Markdown:

## ПОК (Kiến trúc máy tính)

1. Cuốn sách đầu tiên mà tôi thực sự khuyên dùng: 
[David Harris, Sarah Harris «Digital Design and Computer Architecture»](books/Digital%20Design%20and%20Computer%20Architecture.%20ARM%20Edition%20by%20Sarah%20Harris,%20David%20Harris.pdf). 
Tốt nhất là đọc bản tiếng Anh và phiên bản ARM(*), nhưng bạn cũng có thể dùng bản MIPS hoặc bản tiếng Nga. 
Rất dễ tìm thấy ở các cửa hàng hoặc các nguồn chia sẻ, 
[bản tiếng Nga được cung cấp miễn phí.](http://microelectronica.pro/wp-content/uploads/books/digital-design-and-computer-architecture-russian-translation.pdf)
 
2. Sách của Tanenbaum: ["Modern Operating Systems"](https://os.ecci.ucr.ac.cr/slides/Andrew-S.-Tanenbaum-Modern-Operating-Systems.pdf),
các chương: 1, 2, 3 và 7 -- bắt buộc, 4, 5 nên đọc. Các chương còn lại có thể đọc sau, chúng ta sẽ 
làm việc với các nội dung đó sau này. [Chi tiết hơn về các chương này và lý do tại sao bạn cần chúng.](http://indrekis2.blogspot.com/2016/06/blog-post.html)
 
3. [Giáo trình C. Cuốn sách kinh điển của Kernighan và Ritchie](books/The%20C%20Programming%20Language%20by%20Brian%20W.%20Kernighan,%20Dennis%20M.%20Ritchie.pdf) 
là phù hợp. (Nó thực sự đơn giản và dễ hiểu -- tôi không khuyên bạn học C++ qua cuốn hướng dẫn của Stroustrup đâu :=)

4. Lưu ý: Tôi đã phải tuân thủ thông báo gỡ bỏ theo DMCA cho cuốn sách này. Hiện tại nó liên kết tới 
bản nháp chưa chỉnh sửa của tác giả được xuất bản miễn phí, không phải tệp PDF chính thức từ nhà xuất bản.
["Linkers and Loaders"](https://www.iecc.com/linker/)
[Trang Amazon](https://www.amazon.com/Linkers-Kaufmann-Software-Engineering-Programming/dp/1558604960)
Cuốn này tương đối khó đối với bạn, nhưng bằng cách này hay cách khác, chúng ta sẽ phải nắm vững các ý tưởng này.

5. Đối với những ai thấy cuốn Harris & Harris không hợp, có thể dùng: 
[David Patterson, John Hennessy «Computer Organization and Design: The Hardware/Software Interface»](books/Computer%20Organization%20and%20Design%20The%20Hardware%20Software%20Interface%20ARM%20Edition%20by%20David%20A.%20Patterson,%20John%20L.%20Hennessy.pdf)
-- cũng rất giá trị và sẽ cần thiết cho môn AKS. Nếu vẫn thấy quá khó, phương án nhẹ nhàng nhất là: 
[Andrew S. Tanenbaum, Todd Austin «Structured computer organization»](books/Structured%20Computer%20Organization%20by%20Andrew%20S.%20Tanenbaum,%20%20Todd%20Austin.pdf),
 chương 1-4 (có thể cả chương 5), nhưng chương thực sự giá trị duy nhất là chương 4, còn lại thì bình thường...

6. Về phần làm việc với các vi mạch rời ở cuối khóa, bổ sung cho cuốn Harris & Harris là 
cuốn sách rất hay: [Roger Tokheim, «Digital Electronics: Principles and Applications»](books/Digital%20Electronics%20Principles%20and%20Applications%20by%20Roger%20L.%20Tokheim.pdf)
 (có bản dịch tiếng Nga). Bạn cũng có thể dùng bản cũ năm 1988 -- những kiến thức cơ bản đó không hề thay đổi.

7. Cho phần thực hành -- giáo trình về CMake hiện đại ("Professional CMake: A practical guide")
Chúng ta sẽ sử dụng nó rất rộng rãi trong các buổi thực hành của cả ba học phần. 

8. Phần Embedded (Hệ thống nhúng) -- xem trong phần bình luận vì nó khá dài.

9. Các danh sách tài liệu cũ -- tôi sẽ biên tập lại nhiều: 
[một](http://indrekis2.blogspot.com/2017/10/blog-post_39.html), 
[hai](http://indrekis2.blogspot.com/2017/10/blog-post_11.html), 
[ba](https://dou.ua/lenta/articles/dou-books-farenyuk/).

_(*) ARM và MIPS -- đây là các kiến trúc tập lệnh (ISA), nói nôm na là hệ thống lệnh của bộ vi xử lý. Trong điện thoại và các bo mạch nhúng của chúng ta là ARM. Máy tính để bàn và laptop hiện nay hầu hết là x86. Có rất nhiều sách về MIPS (như của Hennessy và Patterson), nhưng thực tế khó gặp nó -- thường chỉ thấy trong các router hoặc thiết bị chuyên dụng khác._

---

## АКС (Kiến trúc máy tính nâng cao)

Danh sách tối thiểu các sách và bài viết cần thiết:

1. [Andrew S. Tanenbaum and Herbert Bos, "Modern Operating Systems"](https://os.ecci.ucr.ac.cr/slides/Andrew-S.-Tanenbaum-Modern-Operating-Systems.pdf) -- cuốn này gần với học phần Hệ điều hành tiếp theo hơn, nhưng đối với AKS thì các chương 1, 2, 3, 6, 8 là cần thiết. (Chương 4, 5 và 7 nên đọc, các chương còn lại có thể đợi đến mùa thu).

2. David Patterson, John Hennessy [«Computer Organization and Design: The Hardware/Software Interface»](books/Computer%20Organization%20and%20Design%20The%20Hardware%20Software%20Interface%20ARM%20Edition%20by%20David%20A.%20Patterson,%20John%20L.%20Hennessy.pdf)
và ["Computer Architecture A Quantitative Approach"](books/Computer%20Architecture,%20Sixth%20Edition%20A%20Quantitative%20Approach.pdf)
của cùng tác giả. 

3. Brian Goetz, Tim Peierls, Joshua Bloch, Joseph Bowbeer, David Holmes, Doug Lea, ["Java Concurrency in Practice"](books/Java%20Concurrency%20in%20Practice.pdf). Cuốn sách này hơi cũ một chút nhưng vẫn còn nguyên giá trị -- nó không bao gồm những tính năng mới nhất của Java, nhưng mô tả chi tiết các nguyên tắc trừu tượng mức trung bình và thấp vốn không hề thay đổi.
    Về kiến trúc bộ nhớ: "What every programmer should know about memory" bởi Ulrich Drepper.
    Về số phẩy động (Floating-point), một chủ đề quan trọng cho AI, ML, Game Dev và các tính toán kỹ thuật/khoa học khác: "What Every Computer Scientist Should Know About Floating-Point Arithmetic" (pdf). Đây là bài viết tối thiểu phải đọc! Ai muốn tìm hiểu sâu hơn thì xem tại đây.


Trên đây là những cuốn sách để đạt mức điểm D-C. Để nâng cao hơn, đạt mức A-B, hãy xem:

1. John Hennessy, David Patterson ["Computer Architecture : A Quantitative Approach"](books/Computer%20Architecture,%20Sixth%20Edition%20A%20Quantitative%20Approach.pdf)

2. David Harris, Sarah Harris [«Digital Design and Computer Architecture»](books/Digital%20Design%20and%20Computer%20Architecture.%20ARM%20Edition%20by%20Sarah%20Harris,%20David%20Harris.pdf). 

3. Anthony Williams ["C++ Concurrency in Action: Practical Multithreading"](books/C++%20Concurrency%20in%20Action.pdf)
