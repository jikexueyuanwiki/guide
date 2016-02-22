# 第四步，配置 Webhook

## 为什么要配置 Webhook

为了能使您在 Github 上的任何更新都能与我们的在线内容同步，需要配置 Webhook

## 配置 Webhook 的步骤

### 1. Github 项目首页点击右侧 Settings

![webhook1](images/webhook1.png)

### 2. 点击左侧 Webhooks & Services

![webhook2](images/webhook2.png)

### 3. 点击 Add webhook 按钮

![webhook3](images/webhook3.png)

### 4. 输入 Github 密码

![webhook4](images/webhook4.png)

### 5. 将我们的 Webhook 地址粘贴到 Payload URL，Secret 留空

**Webhook 地址: http://wiki.jikexueyuan.com/api/github**

![webhook5](images/webhook5.png)

### 6. 点击 Add Webhook 按钮，添加 Webhook

![webhook6](images/webhook6.png)

### 7. 添加完成   

![webhook7](images/webhook7.png)

配置完 WebHook后，就能够上线了，下面[第五步，通知我们](inform-us.md)
