# Descriptive Statistics

___

### I. Định nghĩa

- Các cột dữ liệu được thống kê dựa trên giá trị trung bình về các căn hộ gia đình được thu thập từ các bang của Mỹ 

- "Home Value": Giá trung bình của căn hộ, nhà

- "HH Inc" (Household Income): Thu nhập trung bình từ hộ gia đình

- "Per Cap Inc" (Per Capita Income): Thu nhập trung bình trên đầu người

- "Pct Owner Occ" (Percent of homes that are Owner Occupied): tỷ lệ phần trăm số nhà có chủ sở hữu

___

### II. Nhận định riêng và chung cho từng cột giá trị

***1. Nhận xét chung***
- Tất cả các cột đều có giá trị mean và median không quá chênh lệch (khoảng 1% với "Pct Owner Occ", khoảng 2% với "HH Inc" và "Per Cap Inc", 8% với "Home Value")

> &rarr; Sự xuất hiện của các extreme observation (các biến có giá trị rất lớn hoặc rất nhỏ) xuất hiện không nhiều

- Đa phần các cột dữ liệu ("Home Value", "Per Cap Inc", "Pct Owner Occ") có dao động ở phạm vi hẹp, tần suất xuất hiện của các giá trị chênh lệch lớn, riêng cột "HH Inc" sự biến thiên cao.

***2. Nhận xét riêng***

**- cột Home Value:**

- Bang có giá nhà trung bình thấp nhất là "*West Virgina*" chỉ khoảng 94500    trong khi ở "*Hawaii*" giá nhà lên tới 537,400 &rarr; Các giá trị trong cột "Home Value" dao động trong range là 442,900

- Từ biểu đồ Frequency Histogram, giá nhà dao động chênh lệch khá lớn và có tần suất khá lệch nhau. Điều này có thể do phụ thuộc vào vị trí địa lý, các hoạt động chính trị hoặc do các năng lượng tự nhiên. Như đã nêu trên, hòn đảo "*Haiwaii*" là nơi tập trung nhiều hoạt động du lịch, có nguồn tài nguyên biển dồi dào &rarr; giá nhà cao (trong khoảng 49,3110 - 53,400) 

- Trong khi đó, phần lớn các khu vực khác chỉ có giá dao động từ 94,500 - 138,790 (lên tới 18/51 bang, chiếm hơn 1/3 tổng số bang ở Mỹ)

- Ngoài ra cũng có nhiều khu vực với giá nhà trong khoảng (138790 - 183080) hay (22,370 - 271,660)

- Biểu đồ boxplot cũng đã phần nào chứng minh điều đó, phần lớn giá nhà nằm trong khoảng trên 120,000 và dưới 260,000 và có giá trị trung bình là 173300. Ngoài ra còn có các outliers (có giá nhà cao hơn hẳn so với phần còn lại của dữ liệu) là "*Distric of Columbia*", "*California*", "*Hawaii*"

**- cột: HH Inc:**

- Trái với biểu đồ "Home Value", xu hướng tập trung của dữ liệu nằm trong range cao (32,766) từ (37,881 - 70,647) nhưng giá trị median lại ở mức thấp (bảng HH Inc Boxplot) 

- Phần lớn các bang của mỹ có thu nhập trung bình theo hộ gia đình nằm trong khoảng (41,158 - 57,541), trong khoảng này có tần suất xuất hiện khá đồng đều (37/51 bang)

- 14 bang còn lại có thu nhập theo hộ gia đình nằm rải rác ở những khoảng giá trị khác như (37,881 - 41,158), (60,817 - 64,094), ...

**- cột: Per Cap Inc**

- Thu nhập bình quân trên đầu người của các bang ở Mỹ tập trung trong khoảng (22,187 - 31,028) đặc biệt là khoảng (24,397 - 26,607) lên tới 14/51 bang

- Ngoài ra, chỉ có khoảng 10 bang có thu nhập bình quân đầu người nằm ở ngoài khoảng trên và được phân bổ ở các vùng khác nhau 

- Từ biểu đồ boxplot, chỉ có 1 outlier là "*District of Columbia*" với thu nhập bình quân đầu người là 42,078, cao hơn hẳn các dữ liệu còn lại

**- cột: Pct Owner Occ**

- Đa phần các nhà ở các bang của Mỹ đều đã có chủ sở hữu, giá trị trung vị rơi vào khoảng 70%. Nhìn vào biểu đồ boxplot, phần lớn dữ liệu tập trung vào nửa trên của biểu đồ và được phân bố khá đồng đều. 

- Ngoài ra ở 1 vài bang như "*District of Columbia*" (43.5%), "*New York*"(55.2%), "*California*" (57.4%),"*Hawaii*", "*Nevada*" có thể là do đây là nơi tập trung nhiều khách du lịch, người nước ngoài và cũng là các thành phố lớn, tập trung nhiều điểm du lịch nên giá nhà cao &rarr; tỉ lệ nhà có chủ sở hữu thấp. Đây cũng chính là các outliers của cột dữ liệu "Pct Owner Occ"

___

### III. So sánh thông số các cột với nhau

- Biểu đồ tán xạ "Home Value & HH Inc", "Home Value & Per Cap Inc", "HH Inc & Per Cap Inc" là các biểu đồ đồng biến (có tương quan dương). Các biểu đồ này cũng là biểu đồ tuyến tính (r != 0) do giá trị tập trung ở gần đường thẳng hồi quy. Sự khác nhau giữa "Home Value" và "HH Inc" cũng như "HH Inc" và "Per Cap Inc" là khá lớn do có độ dốc cao và (correlation coefficient trong khoảng 0.83)

- Biểu đồ tán xạ  "Home Value & Pct Owner Occ", "HH Inc & Pct Owner Occ", "HH Inc & Pct Owner Occ" là các biểu đồ phi tuyến tính và nghịch biến (có tương quan âm)

- Trong các biến, biến HH Inc có mối quan hệ mạnh nhất với Home Value (r giữa 2 biến này là lớn nhất) 