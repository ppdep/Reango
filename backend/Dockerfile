FROM python:3.9.1

WORKDIR /backend

COPY . .

RUN pip install -r requirements.txt

EXPOSE 8000

# CMD ["python", "manage.py", "runserver"]