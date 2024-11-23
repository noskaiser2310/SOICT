FROM python:3.9

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY . /app

# Nếu bạn *không* dùng Docker Volume cho dữ liệu:
# COPY data/ /app/data

CMD ["/app/docker/start-jupyter.sh"] # Đường dẫn đầy đủ