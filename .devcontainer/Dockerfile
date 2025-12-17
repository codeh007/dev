# .devcontainer/Dockerfile

# 基于你预先构建的基础镜像
FROM gitgit188/gomtm:latest

# 切换到 root 来安装全局工具 (假设你的镜像默认是 user，如果默认是 root 可去掉 sudo)
# USER root

# 解决痛点：预先安装 gomtm-cli，这样启动 Codespaces 时就不用等了
# RUN sudo npm i -g gomtm-cli

# 如果你的基础镜像没有 sudo，这里可能需要安装 sudo，
# 但通常 Codespaces 推荐的镜像都需要 sudo 支持。

# 切回默认用户 (根据你提供的配置，这里的用户是 user)
# USER user

RUN echo "hello"