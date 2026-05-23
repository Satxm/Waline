# Netlify Waline

**数据库**使用 Netlify 的 Neon 插件。使用 PostgreSQL 也需要先导入 [waline.pgsql](https://github.com/walinejs/waline/blob/main/assets/waline.pgsql) 创建好表和表结构。之后在项目中配置如下环境变量。

|环境变量名称|必填|默认值|备注|
|---|---|---|---|
|PG_DB|✅||PostgreSQL 数据库库名|
|PG_USER|✅||PostgreSQL 数据库的用户名|
|PG_PASSWORD|✅||PostgreSQL 数据库的密码|
|PG_HOST||127.0.0.1|PostgreSQL 服务的地址|
|PG_PORT||3211|PostgreSQL 服务的端口|
|PG_PREFIX||wl_|PostgreSQL 数据表的表前缀|
|PG_SSL||false|是否使用 SSL 连接 PostgreSQL 数据库|
|POSTGRES_DATABASE|||同 PG_DB|
|POSTGRES_USER|||同 PG_USER|
|POSTGRES_PASSWORD|||同 PG_PASSWORD|
|POSTGRES_HOST||127.0.0.1|同 PG_HOST|
|POSTGRES_PORT||3211|同 PG_PORT|
|POSTGRES_PREFIX||wl_|同 PG_PREFIX|
|POSTGRES_SSL||false|同 POSTGRES_SSL|
