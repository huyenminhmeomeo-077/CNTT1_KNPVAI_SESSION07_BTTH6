## 1. Câu chuyện của tôi

Tôi đang làm trợ lý đào tạo cho một trung tâm tin học. Hết môn Java cơ bản, lớp có 30 bạn và tôi cần gộp điểm để làm báo cáo.
Tôi có 4 file khác nhau:
-   File 1: Danh sách lớp và mã sinh viên.
    
-   File 2: Điểm chuyên cần và điểm bài tập.
    
-   File 3: Điểm giữa kỳ.
    
-   File 4: Điểm cuối kỳ và lời nhận xét của thầy/cô.
    
Mỗi file làm một kiểu nên hơi rối, lại có chỗ bị ghi trùng, có mấy bạn trùng tên nhau nữa. Tôi phải gom hết lại cho gọn để báo cáo.

  

## 2. Mấy quy tắc cần nhớ

Thầy/cô đưa bộ dữ liệu mẫu và dặn mấy ý sau:

-   Luôn dùng **mã sinh viên** để nhận diện, tuyệt đối không ghép điểm chỉ vì trùng tên.
    
-   Điểm mỗi mục từ 0 đến 10.
    
-   Cách tính điểm cuối môn:
    
    -   Chuyên cần: 10%
        
    -   Bài tập: 20%
        
    -   Giữa kỳ: 30%
        
    -   Cuối kỳ: 40%
        
-   Từ **5,0 điểm** trở lên là qua môn.
    
-   Mục nào bị trống thì ghi **"Thiếu dữ liệu"**, không tự bịa điểm.
    
-   Thấy ai điểm thấp cũng không tự đoán lý do.
    
## 3. Việc cần làm với AI

1.  Đọc từng file một.
    
2.  Lọc dữ liệu ra thành bảng cho dễ nhìn.
    
3.  So khớp thông tin giữa các file với nhau.
    
4.  Tìm xem ai thiếu điểm hay bị trùng dữ liệu.
    
5.  Tính điểm tổng kết theo đúng công thức.
    
6.  Chia ra ai qua môn, ai rớt môn.
    
7.  Nhìn tổng quan xem cả lớp học hành ra sao.
    
## 4. Những thứ phải nộp

-   Các câu lệnh Prompt để AI đọc và xử lý 4 file.
    
-   Câu lệnh Prompt để AI đối chiếu dữ liệu.
    
-   Bảng điểm đủ 30 bạn gồm: Mã SV, Họ tên, Chuyên cần, Bài tập, Giữa kỳ, Cuối kỳ, Tổng kết, Kết quả.
    
-   Thống kê phần trăm qua môn và rớt môn.
    
-   Danh sách mấy ca lạ (thiếu điểm, trùng thông tin...).
    
-   Một bài nhận xét tình hình học của lớp tầm 500 chữ.
