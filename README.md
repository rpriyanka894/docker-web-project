## Project Screenshot
!Project Screenshot

# Dockerized Static Website

This project demonstrates how to containerize a static website using **Docker** for easy deployment and portability.

---

## 📌 Features
- Simple static website built with HTML/CSS.
- Dockerfile for creating a lightweight container.
- Instructions to build, run, and access the website locally.

---

## 🛠️ Technologies Used
- **Docker**
- **Linux**
- **Git**

---

## 🚀 How to Build, Run, and Access the Website
Follow these steps:

```bash
# Clone the repository
git clone https://github.com/rpriyanka894/docker-web-project.git

# Build the Docker image
docker build -t my-website .

# Run the container
docker run -d -p 8080:80 my-website

# Access the website
# Open your browser and go to:
http://localhost:8080

