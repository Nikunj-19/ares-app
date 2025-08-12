FROM python:3.9-alpine

# Copy requirements.txt from build context (which is ./backend)
ADD requirements.txt /app/requirements.txt

# Install dependencies
RUN pip install -r /app/requirements.txt

# Copy all backend code into the container
ADD . /app

WORKDIR /app

ENTRYPOINT ["python"]
CMD ["app.py"]
