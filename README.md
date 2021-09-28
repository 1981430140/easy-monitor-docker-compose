## 快速启动

**1.克隆**
```bash
git clone https://github.com/1981430140/easy-monitor-docker-compose.git
```
**2. 修改 docker-compose.yml 文件中的配置信息， 部署到服务器时主要修改 `XPROFILER_CONSOLE_URL` 为服务器地址，本地运行默认即可， 其他的根据自己需要修改配置**

**3.启动 / 停止**

```bash
# start
docker-compose up -d

# stop
docker-compose down

```
**4. 浏览 http://127.0.0.1:8443**