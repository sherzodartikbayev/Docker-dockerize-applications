# Dockerize Applications Collection 🐳

<img width="300" height="280" alt="Docker_Dont_Proportions_300x248" src="https://github.com/user-attachments/assets/0e790c84-decc-429a-9756-aeee62f0dd6f" />

A collection of reference implementations and configurations for dockerizing various modern web applications. This repository serves as a practical guide and template collection for containerizing environments ranging from simple HTML/JS setups to full-stack MERN and Next.js applications.

## 📁 Repository Structure

The repository is organized into distinct project directories, each demonstrating a specific Docker use case:

* **`hello-docker`** – A minimal, lightweight setup to test and understand basic Docker containerization.
* **`react-docker`** – Standard React single-page application (SPA) optimized for containerized development and production serving.
* **`vite-project`** – Fast, modern frontend setup using Vite, configured to run smoothly inside a Docker container with hot-module replacement (HMR).
* **`next-docker`** – Production-ready Next.js configuration supporting server-side rendering (SSR), optimized layers, and build caching.
* **`mern-docker`** – A full-stack architecture containing a multi-container setup (MongoDB, Express.js, React, Node.js) orchestrated using Docker Compose.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your machine:
* [Docker](https://www.docker.com/products/docker-desktop/) (and Docker Compose for multi-container setups)
* [Git](https://git-scm.com/)

### Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sherzodartikbayev/Docker-dockerize-applications.git](https://github.com/sherzodartikbayev/Docker-dockerize-applications.git)
   cd Docker-dockerize-applications
  ``
  
2. **Navigate to a specific project:**
   ```bash
    cd next-docker # Or any other directory
  ``
  
3. **Build the Docker image:**
   ```bash
    docker build -t my-app-name .
  ``
  
4. **Run the container:**
   ```bash
    docker run -p 3000:3000 my-app-name
  ``

## 🛠️ Tech Stack & Languages Used
- Docker
- Node.js
- React.js
- Vite
- MongoDB
- Express.js
- Next.js
- Tailwind CSS
