# Laptop price prediction — Deep Learning

Dự đoán giá laptop từ thông số cấu hình bằng mô hình deep learning (Keras) và demo web Flask.

## Stack
Python · Keras/TensorFlow · scikit-learn · Pandas/NumPy · Flask

## Thành phần
- `data_preprocessing.py`, `data_analysis.py` — tiền xử lý và phân tích dữ liệu
- `model.py`, `main_train.py` — định nghĩa và huấn luyện mô hình
- `main.py`, `templates/`, `static/` — web demo
- `laptop_prices.csv` — dữ liệu

## Cách chạy
```bash
pip install -r requirements.txt
python main_train.py   # huấn luyện
python main.py         # chạy demo
```
