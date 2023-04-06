# olusturmak istedigimiz imagine'in kullanacagi base image:
FROM python:alpine 
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
# container icindeki bu uygulama 5000 portundan calisacakmis. containerin disindan
# bu container'a 5000 portu ile ulasilsin
EXPOSE 5000
CMD python ./index.py