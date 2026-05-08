# Startup Funding Analysis

## Mục tiêu
Phân tích xu hướng đầu tư startup toàn cầu từ dữ liệu Crunchbase (`investments_VC.csv`) nhằm hiểu rõ ngành nào được ưa chuộng, quốc gia nào dẫn đầu và vòng gọi vốn nào phổ biến nhất trong hệ sinh thái startup thế giới

---

## Câu hỏi phân tích

1. Ngành nào nhận nhiều vốn đầu tư nhất? ![Biểu đồ 1](bieu_do_1.png)
2. Quốc gia nào có nhiều startup nhất? ![Biểu đồ 2](bieu_do_2.png)
3. Xu hướng startup theo năm như thế nào? ![Biểu đồ 3](bieu_do_3.png)
4. Vòng gọi vốn nào phổ biến nhất? ![Biểu đồ 4](bieu_do_4.png)

---

## Tools sử dụng

- **Python** — Pandas, Matplotlib, Seaborn
- **Jupyter Notebook**
- **Dữ liệu:** `investments_VC.csv` (Crunchbase)

---

## Cấu trúc thư mục

```
startup-funding-analysis/
├── data/
│   ├── investments_VC.csv
│   ├── bieu_do_1.png      # Top 10 ngành nhận nhiều vốn nhất
│   ├── bieu_do_2.png      # Top 10 quốc gia có nhiều startup nhất
│   ├── bieu_do_3.png      # Xu hướng startup theo năm
│   └── bieu_do_4.png      # Tổng vốn theo vòng gọi vốn
├── notebook
│   └── startup_analysis.ipynb
├── insights.md
└── README.md
```

---

## Tác giả: Lê Thành Trung
> Dự án phân tích dữ liệu cá nhân, sử dụng dữ liệu Crunchbase công khai
