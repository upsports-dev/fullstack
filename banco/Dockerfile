# Use the official PostgreSQL image from Docker Hub
FROM postgres:latest

# Set environment variables for PostgreSQL
ENV POSTGRES_USER jogo
ENV POSTGRES_PASSWORD jogo
ENV POSTGRES_DB jogo

# Copy the SQL script to create the "jogo" table
#COPY create_table.sql /docker-entrypoint-initdb.d/

# Expose the PostgreSQL port
EXPOSE 5432