FROM python:slim
EXPOSE 8000
RUN mkdir /app
VOLUME ["/app"]
WORKDIR /app
USER 1001:1001
CMD ["python3", "-m", "http.server"]