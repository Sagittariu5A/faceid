FROM tensorflow/tensorflow:latest

WORKDIR /home/faceid

COPY . .

RUN python3 -m pip install -r requirements.txt

CMD [ "python3", "./faceid.py"]
