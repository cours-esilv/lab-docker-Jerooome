FROM python

COPY . /app/back

RUN pip install --no-cache-dir -r /app/back/requirements.txt

ENV FLASK_APP=/app/back/app.py

# Run app.py when the container launches
CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]