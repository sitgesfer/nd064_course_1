FROM python:3.9
LABEL maintainer="Fernando Rivas"

COPY ./techtrends /app
WORKDIR /app
RUN pip install -r requirements.txt
RUN python init_db.py

EXPOSE 3111

CMD ["python","app.py"]