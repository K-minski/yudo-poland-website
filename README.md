# YUDO Poland Website
Rebuild with react-router v7

## Getting Started

### Installation
Clone project from repository:
```
git clone https://github.com/K-minski/yudo-poland-website.git
```


Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

## Styling

This project uses [styled-components](https://styled-components.com/) instead of css

---

Built with ❤️ using React Router.
