# Use the official PostgreSQL 16 image as the base image
FROM postgres:16

# Set environment variables for database and user
ENV POSTGRES_DB=jwt_security
ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=hello

# Expose the PostgreSQL port
EXPOSE 5432

# Start PostgreSQL when the container starts
CMD ["postgres"]

# Optional: You can add initialization scripts if needed (e.g., to create tables or load data)
# COPY ./init.sql /docker-entrypoint-initdb.d/
