FROM python:3

COPY src /src

WORKDIR /src/frontend/

RUN pip install -r requirements.txt

EXPOSE 8000
CMD [ "python", "frontend.py" ]