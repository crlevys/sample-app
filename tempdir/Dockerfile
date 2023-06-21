FROM python:3.9.17-bullseye
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  sample_app.py /home/myapp/
EXPOSE 6060
CMD python /home/myapp/sample_app.py
FROM python:3.9.17-bullseye
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  sample_app.py /home/myapp/
EXPOSE 6060
CMD python /home/myapp/sample_app.py
