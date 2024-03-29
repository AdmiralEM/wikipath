# WikiPath.app

Welcome to WikiPath.app, an innovative web application that revolutionizes the exploration and interaction with information on Wikipedia. By mapping your journey through articles as a dynamic mind-map, WikiPath.app offers a unique and engaging way to visualize the interconnectedness of knowledge.

## Overview

WikiPath.app is more than just a Wikipedia viewer; it's an exploratory tool that captures and visualizes the path of your learning journey. As you navigate through Wikipedia articles, the app tracks your route and displays it as an interactive mind-map, illuminating the relationships between diverse topics.

## Features

- **Integrated Wikipedia Viewer**: Seamlessly browse Wikipedia articles within the app.
- **Interactive Mind-Map Visualization**: Transform your browsing history into a vivid mind-map showing the links between topics.
- **Path Management Tools**: Save, name, and revisit your exploration paths.
- **Analytics Dashboard**: Analyze your browsing patterns with detailed statistics.
- **Responsive and Accessible Design**: Enjoy a user-friendly interface adaptable to various devices and screen sizes.

## Technology Stack

Built on the MERN stack (MongoDB, Express.js, React, Node.js), WikiPath.app leverages modern web technologies to create a robust, scalable, and interactive experience.

## Development Environment

This project uses a containerized development environment to ensure consistency across different setups and ease the onboarding process for new contributors.

### Prerequisites

- Docker Desktop
- Docker Compose
- Windows Subsystem for Linux (WSL) 2
- Visual Studio Code (VS Code)
- Git

### Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AdmiralEm/wikipath.git
   cd wikipath
   ```

2. **Start Docker Desktop**:
   Ensure Docker Desktop is running with WSL 2 backend enabled.

3. **Open with VS Code**:
   Open the project folder with VS Code for a seamless coding experience.

4. **Build and Run the Docker Containers**:
   ```bash
   docker-compose up --build
   ```

### Structure

- `backend`: Contains the Node.js/Express.js application.
- `frontend`: Contains the React application.
- `mongo`: MongoDB service configuration.
- `docker-compose.yml`: Defines the services, networks, and volumes for Docker.

### Development Workflow

- Code in your local environment (WSL distro).
- Save changes and see them reflected immediately in the running containers thanks to Docker bind mounts.
- Use VS Code for editing, debugging, and version control.

### Testing

More to come on this.

### Deployment

More to come on this.

### Additional Resources

- Docker Documentation: [Get Started with Docker](https://docs.docker.com/get-started/)
- WSL 2 Documentation: [WSL 2 Overview](https://docs.microsoft.com/en-us/windows/wsl/compare-versions)
- VS Code Documentation: [Getting Started with VS Code](https://code.visualstudio.com/docs)

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**. Check out our [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute.

## Miscellaneous

If you like the sound of this and what to help out in other ways, feel free to .[Buy Me A Coffee](https://www.buymeacoffee.com/bluewaters). I mean, there isn't much yet, but I figured I'd get this out here just ince case.
