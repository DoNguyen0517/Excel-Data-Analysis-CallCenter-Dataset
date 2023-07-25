# Excel Call Center Dashboard
![Excel Call Center Project](https://github.com/DoNguyen0517/Excel-Data-Analysis-CallCenter-Dataset/assets/138648091/5cd06e15-c3c8-401f-be1b-2a6f6ac132ed)


### Giới thiệu

Kho lưu trữ này chứa mã và tài liệu cho quy trình phân tích dữ liệu của bộ dữ liệu Call_Center. 
Mục tiêu của dự án này là làm sạch và cải thiện bộ dữ liệu cung cấp thông tin về các cuộc gọi đến trung tâm, từ đó xây dựng dashboard trực quan hóa các thông tin cần thiết cho phân tích.


### Nguồn dữ liệu và tổng quan

Bộ dữ liệu Call_Center được sử dụng trong dự án này được lấy từ một chia sẻ trên github.
Nó bao gồm các thuộc tính của các cuộc gọi, thông tin khách hàng, cuộc gọi, số liệu thống kê và các thông tin liên quan khác.

Bộ dữ liệu gốc của Call_Center chứa hơn 32.000 bản ghi dữ liệu cuộc gọi. Mỗi bản ghi đại diện cho một cuộc gọi duy nhất và bao gồm các thuộc tính khác nhau như tên, csat_score, vùng, thành phố, thời gian gọi v.v..


### Câu hỏi phân tích

1. Có tổng bao nhiêu cuộc gọi đã được tiếp nhận trong tháng của tất cả Call Center
2. Lượng hoạt động của từng channel như thế nào?
3. Sắc thái cuộc gọi (Sentiment) nhìn chung đang có xu hướng thế nào?
4. Sắc thái cuộc gọi theo từng Call Center như thế nào?
5. Call Center nào đang hoạt động công suất cao nhất?
6. Lý do chính cho các cuộc gọi là gì?
7. Các khu vực nào có lượng cuộc gọi nhiều nhất?


### Các công cụ được sử dụng

Excel


### Quy trình thực hiện 

1. **Data Understanding** - Tập dữ liệu đã được kiểm tra kỹ lưỡng để hiểu cấu trúc, các cột và ý nghĩa của chúng.
   Dữ liệu không có từ điển dữ liệu kèm theo. Với sự trợ giúp của các nguồn trực tuyến, tôi đã có thể tạo một nguồn 
   giúp tôi hiểu được ý nghĩa của tất cả các cột.
2. **Data Cleaning and Formatting** - Thực hiện chỉnh sửa định dạng các cột Số về đúng định dạng (csat_score, call duration), chỉnh sửa định dạng ngày tháng(call_timestamp), tạo thêm cột ngày (call_day)để thực hiện phân tích dễ dàng và trực quan hơn.
3. **Create Pivot Tables** - Tạo các Pivot Tables mang những đặc tính ý nghĩa cho việc phân tích (cuộc gọi theo call center, theo khu vực, hiệu suất theo call center...), tạo điều kiện cho trực quan hóa dữ liệu.
4. **Create Dashboard** - Tạo các biểu đồ cột, biểu đồ thanh, donut, các slicers để dễ dàng tương tác vào cụ thể dữ liệu, thực hiện đổ màu, sắp xếp trình bày dashboard gọn gàng, dễ nhìn cho việc phân tích thuận tiện hơn.
5. **Validation and quality checks** - Kiểm tra lại các tương tác với Dashboard để đảm bảo hoạt động được đủ nhu cầu phân tích.


### Tóm tắt các Findings

1. Tổng các cuộc gọi đến trong tháng được tiếp nhận đều đặn (trung bình hơn 1000 cuộc gọi mỗi ngày)
2. Channel Call Center có lượng hoạt động nhiều nhất với 31% lượt tiếp nhận cuộc gọi, tiếp theo đó lần lượt là Chat Bot, Email, Web
3. Sắc thái các cuộc gọi được tiếp nhận nhìn chung mang sắc thái tiêu cực và trung tính, các cuộc gọi mang sắc thái tích cực chỉ chiếm khoảng 20%
4. Theo từng call center, Los Angeles/CA tiếp nhận các cuộc gọi với tỉ lệ tiêu cực là cao nhất, đây cũng là nơi tiếp nhận nhiều cuộc gọi mang sắc thái tiêu cực nhất
5. Call Center Los Angeles/CA là nơi hoạt động với công suất cao nhất, lượng tiếp nhận cuộc gọi lớn nhất với gần 14.000 cuộc gọi trong tháng
6. Lí do chính cho các cuộc gọi ở toàn bộ các centre là các thắc mắc về thanh toán hóa đơn chiếm tới hơn 70% nội dung của các cuộc gọi
7. Bang Texas, California, Florida là các khu vực có nhiều cuộc gọi nhất, chiếm tới hơn 10.000 cuộc gọi trong tổng hơn 32.000 cuộc gọi
