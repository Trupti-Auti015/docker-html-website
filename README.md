# Docker HTML Website

## 📌 Project Overview

This project demonstrates how to containerize a simple static HTML website using Docker. The website is served through an Nginx web server running inside a Docker container.

This project helps beginners understand Docker basics, image creation, container execution, and web application deployment.

---

## 🚀 Technologies Used

* HTML5
* CSS3
* Docker
* Nginx
* Git
* GitHub

---

## 📂 Project Structure

```
docker-html-website/
│── index.html
│── style.css
│── Dockerfile
└── README.md
```

---

## ⚙️ Prerequisites

Before running this project, make sure you have:

* Docker Desktop installed
* Git installed
* A GitHub account

---

## 🛠️ Steps to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Trupti-Auti015/docker-html-website.git
```

### 2. Go to the Project Folder

```bash
cd docker-html-website
```

### 3. Build the Docker Image

```bash
docker build -t docker-html-website .
```

### 4. Run the Docker Container

```bash
docker run -d -p 8080:80 docker-html-website
```

### 5. Open in Browser

Visit:

```
http://localhost:8080
```

The HTML website will be displayed in your browser.

---

## 🐳 Docker Commands Used

Build Image

```bash
docker build -t docker-html-website .
```

Run Container

```bash
docker run -d -p 8080:80 docker-html-website
```

List Running Containers

```bash
docker ps
```

Stop Container

```bash
docker stop <container_id>
```

Remove Container

```bash
docker rm <container_id>
```

List Docker Images

```bash
docker images
```

---

## 📖 Learning Outcomes

* Understanding Docker images and containers
* Writing a Dockerfile
* Building Docker images
* Running containers
* Hosting a static website with Nginx
* Using Docker commands
* Uploading projects to GitHub

---

## 📸 Output

After running the container successfully, open:

```
http://localhost:8080
```

to view the website.

---

## 👩‍💻 Author

**Trupti Auti**

GitHub: https://github.com/Trupti-Auti015

---

## ⭐ Conclusion

This project demonstrates the complete workflow of Dockerizing a static HTML website. It provides hands-on experience with creating Docker images, running containers, and serving web applications using Nginx.
