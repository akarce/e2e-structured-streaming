# e2e-structured-streaming
End-to-end data pipeline that ingests, processes, and stores data. It uses Apache Airflow to schedule scripts that fetch data from an API, sends the data to Kafka, and processes it with Spark before writing to Cassandra. The pipeline, built with Python and Apache Zookeeper, is containerized with Docker for easy deployment and scalability.
