# vaultwarden-lang-zhcn

## email
[dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) 电子邮件模板（位于 `src/static/templates/email`）的简体中文翻译，如下所述：[https://github.com/dani-garcia/vaultwarden/wiki/Translating-the-email-templates](https://github.com/dani-garcia/vaultwarden/wiki/Translating-the-email-templates)。

⚠️ email - v1.28.1 表示适用于 [v1.28.1](https://github.com/dani-garcia/vaultwarden/releases/tag/1.28.1)（经测试 email - v1.28.1 也适用于 [v1.29.0](https://github.com/dani-garcia/vaultwarden/releases/tag/1.29.0)）
⚠️ email - v1.32.4 也适用于 [v1.33.1](https://github.com/dani-garcia/vaultwarden/releases/tag/1.33.1)

## admin
[dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) 管理页面（位于 `src/static/templates/admin`）的简体中文翻译。

⚠️ admin - v1.30.5 表示适用于 [v1.30.5](https://github.com/dani-garcia/vaultwarden/releases/tag/1.30.5)，以此类推
⚠️ admin - v1.32.6 也适用于 [v1.33.1](https://github.com/dani-garcia/vaultwarden/releases/tag/1.33.1)

## 使用方法
保持文件结构，放置于 Vaultwarden 对应的目录下。

例如 Docker 方式，假设你部署的时候使用 `-v` 参数指定的宿主机文件夹为 `vaultwarden-data`：

+ 电子邮件模板文件放置于宿主机的 `/vaultwarden-data/templates/email` 文件夹下
+ 管理后台模板文件放置于宿主机的 `/vaultwarden-data/templates/admin` 文件夹下

然后 `docker restart vaultwarden` 重启 Vaultwarden 容器。
