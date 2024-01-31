# 使用官方的 Python 镜像作为基础镜像
FROM python:3.8-slim

# 设置工作目录
WORKDIR /app

# 安装 Flask 和 pip
RUN pip install --no-cache-dir Flask

# 复制应用程序代码到容器中
COPY . .

# 暴露应用程序运行的端口
EXPOSE 5000

# 启动应用程序
CMD ["python", "app.py"]
