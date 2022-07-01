FROM jupyter/minimal-notebook

RUN pip install pandas numpy

WORKDIR /app
COPY pipeline.py pipeline.py

ENTRYPOINT [ "python", "pipeline.py" ]