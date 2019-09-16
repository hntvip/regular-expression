# regular-expression

Tóm tắt một số khuôn mẫu cơ bản của Regular Expression:

* /abc/ : chuỗi các kí tự abc 
* /[abc]: bất kỳ kí tự nào thuộc tập hợp a, b, c
* /[^abc]: bất kỳ kí tự nào không thuộc tập a, b, c
* /[0-9]/: bất kỳ kí tự nào thuộc đoạn từ 0 đến 9
* /x+/: thành phần x xuất hiện >= 1 lần
* /x*/: thành phần x xuất hiện >= 0 lần (có thể không xuất hiện)
* /x?/: thành phần x xuất hiện 0 hoặc 1 lần
* /x{2, 4}/: thành phần x xuất hiện từ 2 đến 4 lần
* /(abc)/: cụm abc
* /a|b|c/: bất kì pattern nào trong 3 loại a, b, c
* /\d/: chữ số từ 0 đến 9
* /\w/: chữ cái
* /\s/: kí tự trắng (dấu cách, tab, dòng mới,...)
* /./ : bất kỳ kí tự nào trừ dòng mới
* /\b/: ranh giới từ
* /^/: bắt đầu string
* /$/: kết thúc string
