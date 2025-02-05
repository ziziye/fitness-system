# Fitness System

本项目包含 Flask 后端（6000 端口）、React 前端（3000 端口）和 Spring Boot 后端（8080 端口），支持 Docker 容器化部署。

## 端口信息
- **6000** - Flask 后端
- **3000** - React 前端
- **8080** - Spring Boot 后端

## 启动所有服务（本地 & Docker）

```sh

# 启动 Flask 后端（6000 端口）
(venv)% python3 -m pip install -r requirements.txt
(venv)% python3 -m pip install flask-cors
(venv)% python3 -m pip install langchain 
(venv)% python3 -m pip install langchain_community
(venv)% python3 -m pip install python-docx
(venv)% python3 -m pip install moviepy
(venv)% pip install speechrecognition
(venv)% pip install opencv-python
(venv)% pip install pytesseract
(venv)% python3 app.py

# 启动 React 前端（3000 端口）
cd ..
cd react_frontend
（如果没下过就npm install）
npm install react-router-dom
npm install cross-spawn@latest
npm start

# 启动 Spring Boot 后端（8080 端口）
spring boot
build gradle

# 启动 Docker 容器（后台模式）
docker-compose up
docker-compose down
