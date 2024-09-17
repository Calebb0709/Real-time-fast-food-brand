FROM python:3.9-slim

# Copy ứng dụng của bạn vào container
COPY . /app

# Set a working directory inside the container
WORKDIR /app



# Cài đặt các thư viện Python cần thiết
RUN pip install transformers
RUN pip install -r requirements.txt

CMD ["python", "consumer.py"]