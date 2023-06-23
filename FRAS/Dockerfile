FROM python:3.7

WORKDIR                /app
COPY requirements.txt  .

RUN pip install --upgrade pip ; pip install -r requirements.txt

COPY .  .

CMD echo '--- next step  '; \
    echo '--- next step  docker image ls  # eg will get fras_app_i'; \
    echo '--- next step  docker run -it fras_app_i bash -c "python main.py" '; \
    echo
