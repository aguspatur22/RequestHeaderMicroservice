# Node Express API Project

This project is a simple Node.js application using Express to demonstrate basic API functionality, including serving static files and handling API requests. It's designed to be remotely testable and includes features like CORS (Cross-Origin Resource Sharing) to support this.

## Features

- **Environment Variables**: Utilizes `dotenv` for managing environment variables.
- **CORS Enabled**: Implements CORS to allow cross-origin requests, making the API testable from any domain.
- **Static File Serving**: Serves static files from the `public` directory, allowing for a simple front-end component.
- **Basic Routing**: Includes basic routing to serve an HTML file as the homepage and handle API requests.
- **API Endpoint**: A specific API endpoint (`/api/whoami`) is provided to return JSON data including the requester's IP address, preferred languages (from the `Accept-Language` header), and browser information (from the `User-Agent` header).