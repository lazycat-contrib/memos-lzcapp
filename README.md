# Memos for LazyCat

[Memos](https://github.com/usememos/memos) 的懒猫微服 LPK v2 打包项目。

## 运行配置

- 镜像：`docker.1ms.run/neosmemo/memos:0.30`
- 服务端口：`5230`
- 数据目录：`/lzcapp/var/memos:/var/opt/memos`
- 包名：`community.lazycat.app.memos`

首次打开 Memos 后，请按页面引导创建管理员账号。

## 自动发布

GitHub Actions 会检查 `neosmemo/memos` 的稳定版本，构建带版本号的 LPK Release Asset，并仅发布到喵喵商店。官方懒猫应用商店发布已明确禁用。
