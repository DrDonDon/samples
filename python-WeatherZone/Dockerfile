FROM python:3.7-alpine
WORKDIR /job
COPY ./requirements.txt .
RUN pip install -r requirements.txt
COPY . .
ENTRYPOINT [ "python" ]
CMD [ "index.py" ]