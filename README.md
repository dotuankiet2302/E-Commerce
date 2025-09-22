# E-commerce Customer Behavior Analysis  

## Giới thiệu
Đây là **mini project** trong vai trò **CX Data Analyst**, nhằm phân tích hành vi khách hàng của một website thương mại điện tử.  
Mục tiêu chính:  
- Hiểu rõ **doanh thu theo thời gian**  
- Xác định **sản phẩm bán chạy** và **quốc gia mang lại doanh thu**  
- Phân tích **hành vi khách hàng** bằng mô hình **RFM (Recency, Frequency, Monetary)**  
- Đưa ra **insight** hỗ trợ chiến lược chăm sóc khách hàng & remarketing.  

## Dataset
- **Nguồn:** [E-commerce Data - Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data)  
- **Mô tả:** Dữ liệu đơn hàng của một e-commerce tại UK từ năm 2010–2011.  
- **Kích thước:** ~50MB (do quá lớn nên không đính kèm trực tiếp trong repo).  

👉 Cần tải dataset từ Kaggle và đặt file `data.csv` cùng thư mục với notebook để chạy được.  

## ⚙️ Cách chạy project
1. Clone repo về máy:
   ```bash
  git clone https://github.com/<your-username>/ecommerce-analysis.git
  cd ecommerce-analysis
2. Tạo môi trường ảo (tuỳ chọn):
  python -m venv venv
  source venv/bin/activate   # Mac/Linux
  venv\Scripts\activate      # Windows
3. Cài đặt thư viện cần thiết:
  pip install -r requirements.txt
  pip install pandas matplotlib seaborn
4. Chạy notebook:
  jupyter notebook ecommerce_analysis.ipynb

Phân tích chính
1. Doanh thu theo tháng

Doanh thu tăng trưởng theo mùa, đặc biệt vào dịp cuối năm.

2. Top sản phẩm bán chạy

Chủ yếu là các sản phẩm gia dụng nhỏ lẻ, dễ mua nhiều.

3. Doanh thu theo quốc gia

UK chiếm ~80% doanh thu.

Một số quốc gia khác như Hà Lan, Đức, Pháp cũng đóng góp đáng kể.

4. RFM Analysis

Recency (R): Khách hàng quay lại gần đây nhất.

Frequency (F): Số lần mua hàng.

Monetary (M): Tổng chi tiêu.

Nhóm khách hàng VIP (R=4, F=4, M=4) chiếm số ít nhưng đóng góp phần lớn doanh thu.

Rất nhiều khách hàng chỉ mua 1 lần → cơ hội lớn cho remarketing.

Insight & Kết luận

Doanh thu tập trung chủ yếu ở UK → cần đa dạng hoá thị trường.

Nhóm sản phẩm nhỏ lẻ, giá rẻ bán chạy → cơ hội upsell/cross-sell.

Nhóm khách VIP cần chiến lược giữ chân (loyalty program, ưu đãi đặc biệt).

Nhóm khách hàng chỉ mua 1 lần → cần remarketing/email campaign để tăng frequency.

Hướng phát triển tiếp theo

Áp dụng Cluster Analysis (K-Means) để phân nhóm khách hàng chi tiết hơn.

Xây dựng dashboard trực quan bằng Power BI hoặc Tableau.

Phân tích thêm yếu tố giỏ hàng (basket analysis) để gợi ý sản phẩm.
  
