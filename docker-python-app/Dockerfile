From python

COPY requirements.txt /usr/src/app/

RUN pip install --no-cache-dir -r /usr/src/app/requirements.txt

WORKDIR /usr/src/app

COPY app.py .

EXPOSE 5000

CMD ["python3","/usr/src/app/app.py"]
