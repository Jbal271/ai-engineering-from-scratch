FROM python:3.12-slim

ENV PYTHONUNBUFFERED=1

RUN python -m pip install --no-cache-dir numpy==2.2.6
RUN python -m pip install --no-cache-dir torch==2.6.0 \
    --index-url https://download.pytorch.org/whl/cpu

WORKDIR /workspace

CMD ["python"]
