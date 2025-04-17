#Python image'ı kullanmak için:
FROM python:3.10-slim

#Çalışma dizinini ayarlamak için:
WORKDIR /app

#Gerekli dosyaları kopyalamak için:
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

#Uygulamayı kopyalamak için:
COPY app.py .

#Portu expose etmek için:
EXPOSE 5000

#Uygulamayı başlatmak için:
CMD ["python", "app.py"]
