# ĐỒ ÁN TỐT NGHIỆP

## Tên đề tài : Nghiên cứu thư viện CatBoost AI, ứng dụng tìm những thông tin liên quan với nhau theo chiều không gian và thời gian.

Người thực hiện:
> Phạm Như Quyền
> 
> Trần Đức Thắng
> 
> Trần Đình Sang

Các file code hiện nhóm em chưa clear code hoàn toàn, chưa bổ sung hết ý. Bên dưới là mô tả sơ bộ về cource code:

- Preprocessing.ipynb : Tiền xử lý các dữ liệu nhiễu (các xe có ít điểm dữ liệu, góc quay, heading,...)

- report%2029-11-2020.ipynb : Thống kê các xe xuất hiện cùng nhau trong khoảng thời gian 60s và theo vị trí xung quanh bán kính ví 
dụ 30m; Sử dụng phương pháp vét cạn tìm các xe gần nhau và xuất phát trong cùng 1 phút; Lấy ngẫu nhiên 100 phút bất kì trong ngày

- Untitled.ipynb : file xử lý chuỗi Id với hàm Conv_str_2_list

- Untitled_04-01-2021_1.ipynb : Tìm các lộ trình của xe, Thể hiện các lộ trình xe trên bản đồ

- Untitled_1_15_2021.ipynb : Tiếp nối file 04-01, Trực quan đường phố các lộ trình bằng thư viện osmnx của Python.

- Cluster_Vehicle_DBSCAN.ipynb : Gom cụm các xe theo thời gian và khoảng cách sau đó dùng apriori tìm các xe đi chung các cụm rồi 
đưa chúng về cùng các label
 
- Cluster_Vehicle_Point_11-3-2021.ipynb

- Untitled_23_03_2021.ipynb : Xử lý file .osm đưa về file dữ liệu csv bao gồm các thông tin của node , way trong một khu vực địa lý.

- get_nearest_node.ipynb : lấy các node gần nhất với các điểm di chuyển của các xe

- list_way_vehicle_new.ipynb : kéo dữ liệu các xe từ id node về id way

- osm_way_process_31-03-2021_1.ipynb : thêm các điểm ở giữa các node trong một khu vực địa lý

- remove_froneset_vehicle_together.ipynb : Chuyển dữ liệu fronset về dạng list
