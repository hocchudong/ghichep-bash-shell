#Một số câu lệnh Shell hay dùng :

##1. Câu lệnh echo 
Ý nghĩa : in giá trị
Cú pháp câu lệnh :

```
echo [options] [string, variables...]
```
Các `option` trong câu lệnh :

|Option|Ý nghĩa|
|------|-------|
|-i|in giá trị vào file|
|-n|Không xuống dòng|
|-e|Cho phép thực hiện các option với dấu \|
|\a|Chuông cảnh báo|
|\b|Xóa đi ký tự bên tay trái|
|\c|Không xuống dòng đồng thời chặn toàn bộ các ký tự bên phải|
|\n|Tạo 1 dòng mới|
|\t|Tạo 1 khoảng cách|

Ví dụ : echo -e "An apple a day keeps away \a\t\tdoctor\n"
Giá trị trả về :
```An apple a day keeps away               doctor


```
