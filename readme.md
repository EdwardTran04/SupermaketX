## Giới thiệu

Doanh thu bán hàng (Sales Revenue) là giá trị kinh tế mà doanh nghiệp nhận được từ các hoạt động sản xuất và kinh doanh trong lĩnh vực mà doanh nghiệp tham gia. Doanh thu bán hàng không chỉ là nguồn thu nhập chính các nhà đầu tư hằng theo đuổi, mà còn là một chỉ số quan trọng để đánh giá hiệu quả kinh doanh của doanh nghiệp, để từ đó doanh nghiệp có các biện pháp nâng cao hiệu quả sử dụng và xoay vòng vốn. 
Tệp `Supermarket_X.csv` bao gồm dữ liệu lịch sử về doanh số bán hàng của siêu thị X từ ngày 5 tháng 2 năm 2010 đến ngày 1 tháng 11 năm 2012. Thông qua việc phân tích hồi quy, bộ dữ liệu này sẽ cung cấp những thông tin có giá trị trong việc dự báo doanh thu trong tương lai.

## Mục tiêu 

Phân tích các yếu tố ảnh hưởng đến doanh thu bán hàng theo tuần của 45 cửa hàng thuộc chuỗi siêu thị X nhằm đưa ra dự báo doanh thu cho các tuần tiếp theo dựa trên kết quả phân tích thu được.

## Mô tả biến 

Dữ liệu được thu thập từ 45 cửa hàng của siêu thị X từ 2010-2012. Mô tả cụ thể về các biến được thể hiện dưới bảng sau:

|Tên biến|Mô tả|
|---|---|
|`Store`|Số cửa hàng|
|`Date` |Tuần của doanh số bán hàng|
|`Weekly_Sales`|Doanh số bán hàng cho cửa hàng cụ thể|
|`Holiday_Flag`|1 - Tuần nghỉ lễ, 0 - Tuần không phải là tuần nghỉ lễ|
|`Temperature`|Nhiệt độ vào ngày bán hàng|
|`Fuel_Price`|Giá nhiên liệu trong khu vực|
|`CPI`|Chỉ số giá tiêu dùng hiện hành|
|`Unemployment`|Tỷ lệ thất nghiệp hiện hành|

Trong đó, các sự kiện ngày lễ bao gồm: 
- Siêu Bowl: 12 tháng 2 năm 2010, 11 tháng 2 năm 2011, 10 tháng 2 năm 2012
- Ngày Lao động: 10 tháng 9 năm 2010, 9 tháng 9 năm 2011, 7 tháng 9 năm 2012
- Lễ Tạ ơn: 26 tháng 11 năm 2010, 25 tháng 11 năm 2011, 23 tháng 11 năm 2012
- Lễ Giáng sinh: 31 tháng 12 năm 2010, 30 tháng 12 năm 2011, 28 tháng 12 năm 2012
