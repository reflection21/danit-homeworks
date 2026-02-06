FROM python:3.13-alpine AS builder

WORKDIR /app

COPY . .

EXPOSE 8082

ENTRYPOINT ["python"]
CMD ["main.py"]