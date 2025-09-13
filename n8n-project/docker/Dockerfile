FROM n8n/n8n:latest

# Set environment variables
ENV DB_TYPE=postgresdb
ENV DB_POSTGRESDB_HOST=postgres
ENV DB_POSTGRESDB_PORT=5432
ENV DB_POSTGRESDB_DATABASE=n8n
ENV DB_POSTGRESDB_USER=n8n
ENV DB_POSTGRESDB_PASSWORD=n8n_password

# Expose the port the app runs on
EXPOSE 5678

# Start the n8n service
CMD ["n8n"]