FROM python:3.8

RUN pip install ipykernel && \
        python -m ipykernel install --sys-prefix

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt