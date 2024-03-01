FROM python


WORKDIR /myapp

COPY . .

RUN pip install Flask

EXPOSE 5000

CMD [ "python", "app.py" ]