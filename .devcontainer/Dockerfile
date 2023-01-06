FROM meltano/meltano:latest-python3.9

WORKDIR /home/

COPY . .

#RUN bash ./setup.sh

# To query results.
RUN pip install duckdb
ENV PATH="$PATH:/venv/bin/meltano"
