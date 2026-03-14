# 🍃 carbon_emissions_analysis

## 📌 Introduction

![Hình ảnh khói bụi công nghiệp](https://images.unsplash.com/photo-1611273426858-450d8e3c9fce?auto=format&fit=crop&q=80&w=800)

Dự án này nhằm phân tích lượng khí thải carbon từ các công ty và ngành công nghiệp khác nhau. Mục tiêu là xác định các lĩnh vực có mức độ phát thải cao nhất bằng cách phân tích dữ liệu qua các quốc gia, năm, cũng như khám phá các xu hướng trong tương lai.

---

## 📊 Data overview

### Data Structure

Tập dữ liệu bao gồm 4 bảng chứa thông tin về lượng khí thải carbon được tạo ra trong quá trình sản xuất hàng hóa.

*(Bạn có thể chèn ảnh sơ đồ database ERD của bạn vào đây)*
`![Sơ đồ Database](link_anh_so_do_cua_ban.png)`

---

## 🔎 Data Detail

### 📍 Table `product_emissions`

Dưới đây là một mẫu dữ liệu từ bảng phát thải của từng sản phẩm:

**Query:**
```sql
SELECT * FROM product_emissions LIMIT 5;
