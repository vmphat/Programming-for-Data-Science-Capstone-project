# <font color=lightblue>ĐỒ ÁN CUỐI KỲ - LẬP TRÌNH CHO KHOA HỌC DỮ LIỆU</font>

## <font color=lightblue>Nhóm `10` - `Origini`</font>

## <font color=lightblue>Danh sách thành viên</font>

| Họ và tên       | Mã số sinh viên |
| --------------: | :-------------  |
| Trần Đình Quang | 21127406        |
| Vũ Minh Phát    | 21127739        |

## <font color=lightblue>Nơi lưu trữ phụ</font>

- Việc lưu trữ toàn bộ dữ liệu lên GitHub sẽ có chút khó khăn nên nhóm mình đã sử dụng thêm Google Drive làm nơi lưu trữ phụ, mọi người có thể truy cập đến đó thông qua [đường dẫn này](https://drive.google.com/drive/folders/1Bik9i9GaovlYXdHqdtKB1boVdW2uV568?usp=drive_link).

## <font color=lightblue>Thông tin về tập dữ liệu được sử dụng</font>

- Nhóm `10` sử dụng tập dữ liệu được cung cấp từ cuộc thi "Google Analytics Customer Revenue Prediction" trên [Kaggle](https://www.kaggle.com/competitions/ga-customer-revenue-prediction/overview).

- Nhóm tác giả đã cho phép chúng ta sử dụng dữ liệu này một cách miễn phí.

- Vì tập dữ liệu này có dung lượng quá lớn nên nhóm mình không thể đưa dữ liệu lên GitHub. Mọi người có thể lấy dữ liệu được nhóm mình sử dụng thông qua [đường dẫn này](https://drive.google.com/drive/u/1/folders/1QnPcja15R4kyzS7W459Y6TJ9DcvKz5l6).

## <font color=lightblue>Câu hỏi để khám phá dữ liệu</font>

Nhóm đặt ra 5 câu hỏi để khám phá dữ liệu, các bạn có thể xem trong chap 3.

## <font color=lightblue>Tóm tắt kế hoạch thực hiện đồ án</font>

- Tất cả thông tin xung quanh việc lên kế hoạch, phân chia công việc, kết quả thực hiện của từng thành viên đều được ghi chép đầy đủ và có thể truy cập thông qua [đường dẫn này](https://drive.google.com/drive/folders/1rRYi0b87Tr6vhHEf1AHSWIbjotL5eZ_l?usp=drive_link).

- Hoặc mọi người cũng có thể xem trong folder `./reports`.

## <font color=lightblue>Cài đặt môi trường lập trình của bạn với Anaconda</font>

Đầu tiên, bạn nên [tải về và cài đặt Anaconda](https://www.anaconda.com/download) cho hệ điều hành của bạn. Sau đó, bắt đầu cài đặt môi trường phát triển của bạn bằng cách sử dụng ```requirements.txt```. 

**Lưu ý:** Giả sử bạn muốn sử dụng Python 3.10. Vì vậy, nếu bạn muốn cài đặt các gói này trong phiên bản Python khác, hãy kiểm tra lại tất cả các gói bằng lệnh ```conda search -c conda-forge -f  <package name>``` để xác minh phiên bản của từng gói và thay đổi nó trong tệp ```requirements.txt``` file. 

```bash
# create conda virtual environment
conda create --name min_ds-env python=3.10 -y

# activate created conda virtual environment
conda activate min_ds-env

# install dependencies
pip install -r requirements.txt
```

## <font color=lightblue>Giải thích cấu trúc</font>

```
├── data
│   ├── external             <- Data from third party sources.
│   ├── interim              <- Intermediate data that has been transformed.
│   ├── processed            <- The final, canonical data sets for modeling.
│   └── raw                  <- The original, immutable data dump.
│
│
├── notebooks                <- Jupyter notebooks. Naming convention is a number (for ordering),
│                               the creator's initials, and a short `-` delimited description, e.g.
│                               `1.0-initial-data-exploration`.
│
│
├── references               <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports                  <- Data dictionaries, manuals, and all other explanatory materials.
│   └── figures              <- Generated graphics and figures to be used in reporting
│
├── LICENSE
│
├── README.md                 <- The top-level README for developers using this project.
│
├── requirements.txt          <- The requirements file for reproducing the analysis environment
```

## <font color=lightblue>Sử dụng</font>

### Cách 1: Các bạn có thể clone về máy dùng git bằng lệnh

```bash
git clone https://github.com/vmphat/Programming-for-Data-Science-Capstone-project
```

### Cách 2:

Vào mục `<> Code` và chọn mục `Download ZIP` sau đó giải nén.

### Lưu ý:

Các bạn xem lại phần `Nơi lưu trữ phụ` để download dữ liệu.

## <font color=lightblue>Nguồn tham khảo</font>

- Tất cả tài liệu tham khảo đều được nhóm mình đề cập đầy đủ ở file `list_references.md` trong folder `./references`.
