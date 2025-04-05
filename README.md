# Static Website with Docker Deployment

This project demonstrates how to deploy a static website using Docker and Nginx. The website is containerized for easy deployment and scalability.

## Project Structure

```
.
├── Dockerfile          # Docker configuration file
├── nginx.conf         # Nginx server configuration
├── index.html         # Main website content
└── README.md          # Project documentation
```

## Features

- Static website served using Nginx
- Dockerized for easy deployment
- GitHub Pages deployment support
- Responsive design

## Local Development

To run the website locally using Docker:

1. Build the Docker image:
   ```bash
   docker build -t static-website .
   ```

2. Run the container:
   ```bash
   docker run -d -p 80:80 static-website
   ```

3. Access the website at `http://localhost`

## Deployment

### GitHub Pages

The website is deployed using GitHub Pages and can be accessed at:
https://aj7075.github.io/Deploying_A_Static_Website_Using_Docker/

### Docker Deployment

To deploy using Docker:

1. Pull the latest changes:
   ```bash
   git pull origin main
   ```

2. Build and run the Docker container:
   ```bash
   docker build -t static-website .
   docker run -d -p 80:80 static-website
   ```

## Technologies Used

- HTML5
- CSS3
- Nginx
- Docker
- GitHub Pages

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Your Name - [@your_twitter](https://twitter.com/your_twitter)

Project Link: [https://github.com/aj7075/Deploying_A_Static_Website_Using_Docker](https://github.com/aj7075/Deploying_A_Static_Website_Using_Docker) 