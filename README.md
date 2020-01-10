# Data Science Final Project:
## Đề tài: phân loại văn bản
#### Câu hỏi đặt ra
Cho một đoạn văn bản (tiếng Anh), làm sao để biết loại văn bản đó thuộc chủ đề nào.
#### Ứng dụng
Giúp các trang web tin tức, các diễn đàn tự động kiểm tra các bài post từ user thuộc thể loại nào và phân vào lớp cụ thể.
#### Thu thập dữ liệu
Dữ liệu thu thập từ https://vietnamnews.vn/ (đã kiểm tra file robots.txt và hợp lệ)
![robots.txt](https://github.com/tuandoan998/DS_Final_Project/blob/master/misc/img/robots_check.png)   


Dữ liệu bao gồm 5 nhãn (thể loại), mỗi mẫu gồm các cột (id, title, text, label):
- polictics-laws
- society
- economy
- sports
- environment   

Cấu trúc project:   
- Thư mục data: chứa dữ liệu được crawl sẵn (vietnamnews_backup.csv) và file thông tin cho các nhãn (label.txt)
- Thưc mục scripts: chứa 2 file notebook: crawl_all.ipynb, pipe_line.ipynb
- Slide
- Phân công công việc

