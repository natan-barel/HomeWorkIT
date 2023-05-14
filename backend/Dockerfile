FROM python:3.10-alpine
WORKDIR /app
COPY . /app
# Install Python libraries
RUN pip install --no-cache-dir -r requirements.txt
# Run the Python script
ENV FLASK_APP="app.py"
EXPOSE 80
CMD flask run --port=80 --host=0.0.0.0