FROM python:3.6
COPY requirements.txt ./
RUN pip install -r requirements.txt
COPY ./hits/app.py ./
RUN mkdir logs
RUN chmod 777 logs

EXPOSE 5000

CMD python app.py
