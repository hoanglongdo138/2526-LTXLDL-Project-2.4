# Dự án: Vastopolis Epidemic Analysis - Nhóm [Tên Nhóm]

## Cấu trúc thư mục

.
├── raw/                    # Chứa dữ liệu thô (weather.csv, microblog.csv...)
├── processed/              # Chứa dữ liệu đã làm sạch và các bảng thống kê
├── figures/                # Chứa các biểu đồ kết quả (.png)
├── reports/                # Chứa báo cáo PDF và file LaTeX
├── src/                    # Mã nguồn chính
│   ├── 1_data_cleaning.ipynb
│   ├── 2_data_aggregation.ipynb
│   └── 3_visualization.ipynb
├── requirements.txt        # Các thư viện cần thiết
└── README.md               # Hướng dẫn sử dụng

## Yêu cầu hệ thống

Python 3.8+

Các thư viện được liệt kê trong requirements.txt

🚀 Hướng dẫn chạy lại (Reproducibility)

**Bước 1:** Cài đặt môi trường

Khuyến khích sử dụng môi trường ảo (virtualenv):

python -m venv venv
source venv/bin/activate  # Trên Windows: venv\Scripts\activate
pip install -r requirements.txt


**Bước 2:** Cấu hình Seed

Để đảm bảo kết quả nhất quán, dự án sử dụng cấu hình seed như sau:

Numpy/Random Seed: 42

Được khai báo tại đầu mỗi file notebook.

**Bước 3:** Chạy Pipeline

Chạy các notebook theo thứ tự sau để tái tạo kết quả:

src/1_data_cleaning.ipynb: Đọc dữ liệu thô, làm sạch và chuẩn hóa văn bản.

src/2_data_aggregation.ipynb: Nối dữ liệu thời tiết, thống kê từ khóa theo giờ.

src/3_visualization.ipynb: Vẽ bản đồ và các biểu đồ phân tích.

## Kết quả chính

Báo cáo chi tiết: reports/report-[tên-nhóm].pdf

Commit hash bản nộp: [Điền hash vào đây]

📝 Ghi chú về dữ liệu

Dữ liệu thô cần được tải từ Google Drive của môn học và đặt vào thư mục raw/ trước khi chạy code.