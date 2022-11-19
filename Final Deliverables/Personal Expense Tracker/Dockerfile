  FROM python:3.7.0
  LABEL maintainer="Aishwarya, aish19106.cs@rmkec.ac.in"
  RUN apt-get update
  RUN mkdir /app
  WORKDIR /app
  COPY . /app
  RUN pip install -r requirements.txt
  EXPOSE 5000
  ENTRYPOINT [ "python" ]
  CMD [ "app.py" ]


