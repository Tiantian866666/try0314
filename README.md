# Heart Hello World

一个简单的静态网页示例：页面中央显示一个心形图案，心形中有 `hello world` 字样。

## 如何查看效果

### 方式 1：直接打开文件（最简单）

直接用浏览器打开项目里的 `index.html` 即可。

### 方式 2：启动本地静态服务器

在项目根目录运行：

```bash
python3 -m http.server 8000 --directory .
```

然后在浏览器打开：

- `http://localhost:8000/index.html`

> 如果你打开根路径看到 `Not Found`，请确认命令是在项目根目录执行，或直接访问上面的 `/index.html` 路径。
