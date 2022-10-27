FROM python:2.7
WORKDIR /usr/src/app
COPY requirements.txt ./
RUN easy_install distribute
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
CMD [ "python", "tracker.py" ]
