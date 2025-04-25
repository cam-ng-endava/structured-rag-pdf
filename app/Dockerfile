FROM python:3.11

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

EXPOSE 8003

ENTRYPOINT ["streamlit", "run", "streamlit_app.py", "--server.port=8003"]