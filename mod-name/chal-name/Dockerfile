FROM ubuntu:24.04
RUN pip install pyyaml'
COPY .init .
COPY grep_template.py .
COPY input.yml .

CMD [".init"]
