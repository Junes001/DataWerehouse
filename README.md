# DataWerehouse
ETL-project
We used 3 different datasets from the public platform Kaggle which lead us to the Gun Violence Archive website. The data in the three files included the following information:

Accidental death
Mass Shootings
Accidental injuries
The fields of interest include the following:

Incident date
State
City/county
Number killed
Number injured
The following sources for our datasets used:

https://www.kaggle.com/gunviolencearchive/gun-violence-database

https://www.gunviolencearchive.org/reports

https://www.gunviolencearchive.org/mass-shooting

https://www.gunviolencearchive.org/accidental-deaths

Transformation
Để chuyển đổi dữ liệu công khai và sử dụng nó trong nghiên cứu của chúng tôi, chúng tôi đã thực hiện như sau:

Sử dụng các hàm Pandas trong Jupyter Notebook để tải cả ba tệp CSV.
Xem lại các tệp và chuyển thành khung dữ liệu
Đã xóa cột của nhà điều hành và cột địa chỉ do thiếu thông tin không liên quan đến trọng tâm của nghiên cứu này.
Xác định trùng lặp bằng cách thực hiện phối bên trong trên cột id sự cố trên cả ba tập dữ liệu.
Tạo truy vấn để giải quyết giả thuyết của chúng tôi bằng cách nhóm dữ liệu theo tiểu bang và nhận tổng số người thiệt mạng và số người bị thương. Chúng tôi sắp xếp dữ liệu theo thứ tự giảm dần để chúng tôi có thể thấy trực quan trạng thái nào có số cao nhất.
Load
The last step was to transfer our final output into a Database. We created a database and respective table to match the columns from the final Panda's Data Frame using Postgres database using PG admin to store our original clean data sets. We reconnected to the database and generated additional tables for the data frames.

Summary
There were some limitations to our findings due to the data available. However, we were able to address our hypothesis quetion in our intial project proposal listed in the ETL Project Final Write UP.
