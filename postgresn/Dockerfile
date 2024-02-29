# Use the official PostgreSQL image as the base image
FROM postgres:latest

# Set environment variables for PostgreSQL
ENV POSTGRES_USER=customer
ENV POSTGRES_PASSWORD=cust
ENV POSTGRES_DB=custdb

# Expose the PostgreSQL port
EXPOSE 5432

# Create a volume for PostgreSQL data
VOLUME /var/lib/postgresql/data

CMD ["postgres"]