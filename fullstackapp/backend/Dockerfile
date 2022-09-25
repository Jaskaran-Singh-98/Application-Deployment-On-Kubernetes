FROM python:3.7


WORKDIR /app
ADD . /app/
RUN pip install -r requirements.txt

ENV DATABASE_URI="localhost"
ENV FLASK_APP=main.py
ENV FLASK_ENV production

EXPOSE 5000
CMD ["python", "/app/main.py"]