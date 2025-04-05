# 🚀 React Application CI/CD Pipeline with GitHub Actions & AWS EC2

This project demonstrates how to build and deploy a React application using a CI/CD pipeline powered by **GitHub Actions** and hosted on an **AWS EC2** instance.

## 📦 Tech Stack

- **Frontend**: React.js
- **CI/CD**: GitHub Actions
- **Deployment Server**: AWS EC2 (Ubuntu)
- **Web Server**: Nginx (serving the production build)

## ⚙️ CI/CD Workflow Overview

Every time code is pushed to the `main` branch:

1. GitHub Actions installs dependencies
2. Builds the React app
3. Connects to the EC2 instance via SSH
4. Uploads the build files
5. Restarts the web server (Nginx)

## 📁 Project Structure


## 🖥️ Deployment Instructions

Make sure to:

- Create an EC2 instance (Ubuntu recommended)
- Install Node.js, Nginx, and Git
- Add GitHub Secrets:
  - `HOST` – EC2 Public IP/DNS
  - `USER` – EC2 username (e.g., `ubuntu` or `ec2-user`)
  - `KEY` – SSH private key content (paste the full key as a secret)

## 🙌 Author

Project setup by **Unnativ**  
🔗 GitHub: [@unnativ87](https://github.com/unnativ87)
