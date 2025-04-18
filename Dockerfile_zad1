# Użyj oficjalnego obrazu Pythona
FROM python:3.10-slim

# Ustaw katalog roboczy
WORKDIR /app

# Skopiuj pliki
COPY app.py .
COPY requirements.txt .

# Zainstaluj zależności
RUN pip install --no-cache-dir -r requirements.txt

# Otwórz port
EXPOSE 5000

# Uruchom aplikację
CMD ["python", "app.py"]
