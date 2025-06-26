# 🎯 Dự án Cuối kỳ - Machine Learning for Recommender Systems

Đây là dự án cuối kỳ của môn học **Machine Learning for Recommender Systems**. Mục tiêu của dự án là xây dựng, huấn luyện, và so sánh các thuật toán hệ thống khuyến nghị trên dữ liệu thực tế.

---

## 🗂️ Cấu trúc dự án

```plaintext
Final-Machine-Learning-for-Recommender-Systems/
├── Imagine in Hệ Khuyến Nghị/           # Bài làm chia theo 4 chặng chính
│   ├── Chặng 1_ Chuẩn bị dữ liệu/
│   ├── Chặng 2_ Lọc cộng tác (Memory-based)/
│   ├── Chặng 3_ Lọc cộng tác (Model-based)/
│   └── Chặng 4_ Xây dựng hệ thống khuyến nghị cho bệnh nhân tiểu đường/
│
├── ratings_data/                        # Bộ dữ liệu train/test/val
│   ├── train.csv
│   ├── val.csv
│   ├── test.csv
│   └── ratings_full.csv
│
├── Đinh Lê Quỳnh Phương - 2211090031/  # Thư mục báo cáo và notebook tổng hợp
│   ├── Quỳnh_Phương_Bài_tập_thực_hành_final.ipynb
│   ├── Đinh_Lê_Quỳnh_Phương-2211090031.pdf
│   └── Đề tiểu luận.pdf
│
├── ket_qua_so_sanh_rmse.xlsx            # File kết quả đánh giá RMSE
├── quỳnh_phương_bài_tập_thực_hành_final.py
├── requirements.txt                     # Danh sách thư viện cần cài
└── README.md                            # Tài liệu này
```

---

## 📌 Mục tiêu dự án

- Áp dụng các thuật toán học máy để xây dựng hệ thống gợi ý.
- So sánh và đánh giá các kỹ thuật:
  - Collaborative Filtering (User-Based, Item-Based)
  - Matrix Factorization (SVD, SVD++)
  - Content-Based Filtering
  - Hybrid Recommender
- Phân tích hiệu quả mô hình qua các chỉ số đánh giá.

---

## 🧠 Phương pháp sử dụng

- ✅ Lọc cộng tác dựa trên người dùng
- ✅ Lọc cộng tác dựa trên sản phẩm
- ✅ SVD, SVD++
- ✅ Content-Based Filtering
- ✅ Mô hình kết hợp (Hybrid)
- ✅ Tree-based Models: Decision Tree, Random Forest, XGBoost

---

## 📊 Chỉ số đánh giá

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- Precision@K, Recall@K
- NDCG (Normalized Discounted Cumulative Gain)

---

## ▶️ Hướng dẫn chạy

### 1. Tải về:
```bash
git clone https://github.com/quynhphuong1209/Final-Machine-Learning-for-Recommender-Systems.git
cd Final-Machine-Learning-for-Recommender-Systems
```
### 2. Cài đặt thư viện:
```bash
pip install -r requirements.txt
```
### 3. Mở notebook:
```bash
jupyter notebook "Đinh Lê Quỳnh Phương - 2211090031/Quỳnh_Phương_Bài_tập_thực_hành_final.ipynb"
```
## 💾 Dữ liệu sử dụng
- MovieLens 100K
- Dữ liệu giả lập về thuốc và đánh giá của bệnh nhân tiểu đường

# 👩‍💻 Tác giả
- Đinh Lê Quỳnh Phương
- 🎓 Trường Đại học Y tế Công cộng
- 🆔 MSSV: 2211090031
- 📬 GitHub: @quynhphuong1209
