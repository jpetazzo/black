FROM python:3

WORKDIR /src
COPY . .
RUN pip install .

RUN git config --global user.email "nobody@example.com"
RUN git config --global user.name "BlackBot"

ENTRYPOINT ["/src/gallery/entrypoint.sh"]
