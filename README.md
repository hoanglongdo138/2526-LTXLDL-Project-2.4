# Dự án: Vastopolis Epidemic Analysis - Nhóm AIT2006-1-2.4

## Cấu trúc thư mục

```
├── raw/                    # Chứa dữ liệu thô
├── processed/              # Chứa dữ liệu đã làm sạch và các bảng thống kê
├── figures/                # Chứa các biểu đồ kết quả (.png)
├── reports/                # Chứa báo cáo PDF và file LaTeX
├── src/                    # Mã nguồn chính
├── requirements.txt        # Các thư viện cần thiết
└── README.md               # Hướng dẫn sử dụng
```
## Yêu cầu hệ thống

- Python: 3.13
- Môi trường: miniconda
- Các thư viện được liệt kê trong requirements.txt

## Hướng dẫn chạy lại (Reproducibility)

**Bước 1:** Cài đặt thư viện

```
# Cài đặt thư viện
pip install -r requirements.txt
```


**Bước 2:** Chạy các notebook trong thư mục **/src** theo thứ tự sau để tái tạo kết quả:

1. 2_data_cleaning.ipynb: Đọc dữ liệu thô, làm sạch và chuẩn hóa văn bản.

2. 3_aggregate_data.ipynb: Nối dữ liệu thời tiết, thống kê từ khóa theo giờ.

3. 4_visualize_data.ipynb: Vẽ bản đồ và các biểu đồ phân tích.

4. main_data_visual: các biểu đồ phân tích nâng cao


## Kết quả chính

- Báo cáo chi tiết: reports/report-AIT2006-1-2.4.pdf

- Commit hash bản nộp: [Điền hash vào đây]

    📝 Ghi chú về dữ liệu

    Dữ liệu thô cần được tải từ Google Drive của môn học và đặt vào thư mục raw/ trước khi chạy code.