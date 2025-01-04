# MyGate Network 机器人
![banner](image.png)

## 功能特性

- **自动生成节点ID**
- **自动连接/保持节点活跃**
- **自动重连节点**

- **支持多账号**
- **支持使用代理**
- **目前不支持单个账号创建多个节点**

## 环境要求

- 已安装 Node.js
- `tokens.txt` 文件包含 my-gate 平台的 token，获取方法如下：
- 打开 my-gate 平台 [https://mygate.network/](https://app.mygate.network/login?code=LfBWAQ)
- 使用 Gmail 登录
- 按 F12 打开开发者工具，选择 Network 标签
- 复制 token 并保存到 `tokens.txt` 文件中

    ![token](image-1.png)!

## 安装步骤

1. 克隆仓库：
    ```sh
    git clone https://github.com/Zlkcyber/mygateBot.git
    cd mygateBot
    ```

2. 安装依赖：
    ```sh
    npm install
    ```
3. 在 `tokens.txt` 文件中输入你的 token，每行一个用户；
    ```sh
    nano tokens.txt
    ```
4. 可选：使用代理：
- 将代理粘贴到 `proxy.txt` 文件中，格式为 `http://用户名:密码@IP:端口`
    ```sh
    nano proxy.txt
    ```
5. 运行脚本：
    ```sh
    npm run start
    ```

## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

本项目采用 [MIT 许可证](LICENSE)。
