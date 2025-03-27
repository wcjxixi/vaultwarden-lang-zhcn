# vaultwarden-lang-zhcn

## admin
[dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) 管理页面模板（位于 `src/static/templates/admin`）的简体中文翻译，如下所述：[https://github.com/dani-garcia/vaultwarden/wiki/Translating-admin-page](https://github.com/dani-garcia/vaultwarden/wiki/Translating-admin-page)。

## email
[dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) 电子邮件模板（位于 `src/static/templates/email`）的简体中文翻译，如下所述：[https://github.com/dani-garcia/vaultwarden/wiki/Translating-the-email-templates](https://github.com/dani-garcia/vaultwarden/wiki/Translating-the-email-templates)。

⚠️不再维护 email 模板的简体中文翻译⚠️

email - v1.32.4（也适用于 [v1.33.1](https://github.com/dani-garcia/vaultwarden/releases/tag/1.33.1) ）

## 使用方法
保持文件结构，放置于 Vaultwarden 对应的目录下。

例如 Docker 方式，假设你部署的时候使用 `-v` 参数指定的宿主机文件夹为 `vaultwarden-data`：

+ 管理页面模板文件放置于宿主机的 `/vaultwarden-data/templates/admin` 文件夹下
+ 电子邮件模板文件放置于宿主机的 `/vaultwarden-data/templates/email` 文件夹下

然后 `docker restart vaultwarden` 重启 Vaultwarden 容器。
