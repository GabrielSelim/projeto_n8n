# n8n Project

This project provides a setup for running n8n, an open-source workflow automation tool, using Docker. Below are the instructions for setting up, configuring, and running the application.

## Prerequisites

- Docker installed on your machine
- Docker Compose installed on your machine

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd n8n-project
   ```

2. **Configure Environment Variables:**

   Create a `.env` file in the root directory and define your environment variables. You can use the provided `.env.example` as a reference.

3. **Build and Run the Application:**

   Use Docker Compose to build and run the application:

   ```bash
   docker-compose up -d
   ```

   This command will start the n8n service along with any other services defined in the `docker-compose.yml` file.

4. **Access n8n:**

   Once the services are running, you can access n8n by navigating to `http://localhost:5678` in your web browser.

## Stopping the Application

To stop the running containers, use:

```bash
docker-compose down
```

## Additional Information

- For more details on configuring n8n, refer to the [n8n documentation](https://docs.n8n.io).
- Ensure that you do not expose sensitive information in your `.env` file.

## License

This project is licensed under the MIT License.