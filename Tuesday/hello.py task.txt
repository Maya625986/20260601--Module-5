print("Hello, I just used Docker!")

result = 144 / 12
print(result)

FROM python:3.10
WORKDIR /app
COPY calculator.py .
CMD ["python", "calculator.py"]

docker build -t calculator-app .

docker run calculator-app