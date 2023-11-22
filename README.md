# ChatYourSister
a chat software


# 构建项目：
docker build -t chat .

# 运行容器：
docker run -dp 3000:80 --name chat --restart=always chat
