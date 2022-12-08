## ASSIGNMENT 02 - TÍNH TOÁN VÀ PHÂN TÍCH ĐIỂM THI
***
### LƯU Ý:
Phần mềm cần cài đặt:
[Python](https://www.python.org/downloads/) 
[Visual Studio Code](https://code.visualstudio.com/download)
***
## HƯỚNG DẪN SỬ DỤNG CHƯƠNG TRÌNH:
* Chạy chương trình, chương trình sẽ hiện thông báo `Vui lòng nhập mã lớp học:`, người sử dụng nhập mã lớp học
  * Nếu mã lớp học tồn tại trong hệ thống, phần mềm hiện thông báo `Mở mã lớp thành công` và hiện cho người dùng các menu lựa chọn sau:
    * `1. Phân tích file lớp học.`
    * `2. Thống kê điểm lớp học.`
    * `3. Ghi kết quả tổng điểm ra file mới.`
    * `4. Thoát.`
   * Nếu mã lớp không tồn tại trong hệ thống, phần mềm sẽ hiện thông báo `Mã lớp không tồn tại` và xuất hiện lỗi `NameError`
* Sau khi mở mã lớp thành công, người dùng chọn menu theo số 1 - 2 - 3 - 4
  * Chọn `1. Phân tích file lớp học.`, phần mềm sẽ hiện những thông tin sau:
    * Dòng dữ liệu không hợp lệ: ID học viên không hợp lệ
    * Dòng dữ liệu không hợp lệ: không chứa đúng 26 giá trị
    * Tổng số dòng dữ liệu hợp lệ
    * Tổng số dòng dữ liệu không hợp lệ
    * ***Trường hợp không có dòng dữ liệu không hợp lệ, phần mềm sẽ chỉ hiện thị 2 dòng cuối cùng***
  * Chọn `2. Thống kê điểm lớp học.`, phần mềm sẽ hiện những thông tin sau:
    * Tổng số học viên đạt điểm cảo (hơn 80 điểm):
    * Điểm trung bình:
    * Điểm cao nhất:
    * Điểm thấp nhất:
    * Miền giá trị của điểm:
    * Giá trị trung vị:
    * Thống kê câu bị bỏ qua nhiều nhất:
       * Câu bị bỏ qua:
       * Số học viên bỏ qua:
       * Tỷ lệ bị bỏ qua:
    * Thống kê câu bị trả lời sai nhiều nhất:
       * Câu bị trả lời sai:
       * Số học viên trả lời sai:
       * Tỷ lệ bị trả lời sai:
  * Chọn `3. Ghi kết quả tổng điểm ra file mới.`, phần mềm sẽ ghi thông tin tổng điểm của từng học viên theo ID ra file mới tại thư mục `Output`
  * Chọn `4. Thoát" để thoát chương trình.
  
