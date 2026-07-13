# 陶大富个人官网

这个目录用于 GitHub Pages 免费托管。

## 文件说明

- `index.html`：官网首页和人物资料页
- `taodafu-ip-operator.jpg`：陶大富个人照片
- `CNAME`：自定义域名配置，当前为 `taodafuip.top`
- `robots.txt`：搜索引擎抓取规则
- `sitemap.xml`：站点地图

## GitHub Pages 设置

1. 新建公开仓库，例如 `taodafuip`
2. 上传本目录全部文件到仓库根目录
3. 进入仓库 `Settings` → `Pages`
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main`，目录选择 `/root`
6. Custom domain 填写 `taodafuip.top`
7. 保存后等待 GitHub Pages 生效

## 域名 DNS 设置

在域名解析后台添加：

- `A` 记录，主机记录 `@`，指向 `185.199.108.153`
- `A` 记录，主机记录 `@`，指向 `185.199.109.153`
- `A` 记录，主机记录 `@`，指向 `185.199.110.153`
- `A` 记录，主机记录 `@`，指向 `185.199.111.153`
- `CNAME` 记录，主机记录 `www`，指向 `你的GitHub用户名.github.io`

生效后访问：

`https://taodafuip.top/`

