# Learning Log

## 1. Lỗi khi sử dụng `groupby()`

### Mô tả lỗi
Ban đầu em chưa hiểu cách hoạt động của `groupby()` trong Pandas.  
Khi chạy code, em chỉ thấy dữ liệu được nhóm lại nhưng chưa biết cách tính toán trên từng nhóm.

### Nơi tìm giải pháp
- Pandas Documentation
- YouTube tutorials
- Thử nghiệm trực tiếp trong Jupyter Notebook

### Kết quả
Em cho rằng `groupby()` thường được kết hợp với:
- `.mean()`
- `.sum()`
- `.count()`

Ví dụ:

```python
df.groupby("sex")["survived"].mean()
2. Lỗi khi kiểm tra missing values
Mô tả lỗi

Lúc đầu em nghĩ dataset Titanic không có dữ liệu thiếu vì head() hiển thị bình thường.
Sau đó khi dùng info() em phát hiện nhiều cột có số lượng non-null thấp hơn tổng số dòng.

Nơi tìm giải pháp
Hàm info()
Hàm isnull().sum()
Stack Overflow
Kết quả

Em học được cách kiểm tra số lượng và phần trăm missing values:

missing_count = df.isnull().sum()

missing_percent = (df.isnull().sum() / len(df)) * 100

Điều này giúp Em xác định cột nào cần xử lý trước khi phân tích dữ liệu.
Điều Tự Học Được Ngoài Bài Giảng
Pivot Table trong Pandas

Em tự tìm hiểu thêm về pivot_table() trong Pandas.
Function này giúp tổng hợp dữ liệu tương tự Pivot Table trong Excel và rất hữu ích trong Data Analysis.

Ví dụ:

Tính trung bình
Đếm số lượng
Tổng hợp doanh thu theo nhóm

Ví dụ code:

df.pivot_table(
    values="fare",
    index="sex",
    columns="pclass",
    aggfunc="mean"
)
Reflection
Điều khó nhất

Điều khó nhất là hiểu cách chọn function phù hợp giữa groupby(), pivot_table() và value_counts().

Điều thú vị nhất

Điều thú vị nhất là có thể tìm ra nhiều insight từ dataset Titanic chỉ bằng vài dòng code Pandas.

Câu hỏi chưa có câu trả lời

Liệu có thể xây dựng mô hình Machine Learning để dự đoán chính xác hành khách nào sẽ sống sót trên Titanic không?









# Extra Learning Activities

## 1. YouTube Video About Pandas / Data Exploration

### Video
Python Pandas Tutorial by freeCodeCamp

### Điều học được
Em học được cách sử dụng `groupby()` để phân tích dữ liệu theo từng nhóm khác nhau.  
Ngoài ra video còn giải thích cách dùng `describe()` và `value_counts()` để khám phá dataset nhanh hơn.

---

# BONUS

## 2. Kaggle Titanic Notebook

### Notebook tham khảo
Titanic Data Science Solutions trên Kaggle

### 2 kỹ thuật mới học được

1. Feature Engineering  
Tạo thêm cột mới từ dữ liệu cũ, ví dụ tách title từ tên hành khách như Mr, Mrs, Miss.

2. Filling Missing Values  
Sử dụng median hoặc mean để điền dữ liệu thiếu thay vì xóa toàn bộ dòng.

---

## 3. Theo dõi người làm Data Science trên LinkedIn

### Người theo dõi
Andrew Ng

### Lý do chọn
Andrew Ng là một trong những người nổi tiếng nhất trong lĩnh vực AI và Data Science.  
Ông chia sẻ nhiều kiến thức hữu ích về Machine Learning và định hướng nghề nghiệp cho người mới học.
