# How to develop and deploy the project?

1. Create a new GitHub repository using the [Node.js and TypeScript template](https://github.com/new?template_name=mits-nodejs-typescript-v1&template_owner=marketable-it-skills).
2. Place your solution code inside the `/src` folder.
3. Pushing to GitHub triggers GitHub Actions (see `.github/`) to:
   - Build a Docker image
   - Push it to GitHub Container Registry
4. In `docker-compose.yml`, update:
   `image: ghcr.io/<your-github-account>/<your-repo-name>:latest`
5. Run locally:
   ```bash
   docker compose up -d
   ```
6. Visit: [http://localhost:3000](http://localhost:3000)

## Development Setup

### Prerequisites
- Node.js 18+ and npm
- Docker and Docker Compose
- Access to the provided AI services

### Local Development
1. Install dependencies:
   ```bash
   npm install
   ```

2. Set up environment variables:
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

3. Start the AI services (for development):
   ```bash
   cd assets/ai-services
   docker compose up -d
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. The API will be available at `http://localhost:3000`

### Testing the API
Use the provided OpenAPI specification to test endpoints:
- View API docs: Open `assets/handout-competitor/ai-api/api-docs.html` in your browser
- Test with tools like Postman, curl, or the provided test files
- Ensure all authentication and quota requirements are working

### Database Setup
1. Import the provided database:
   ```bash
   mysql -u root -p < assets/handout-competitor/database/euroskills2023.sql
   ```

2. Update your database connection in the environment configuration