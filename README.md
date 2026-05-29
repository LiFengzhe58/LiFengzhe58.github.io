# K1ndlyLiz Blog

这是 K1ndlyLiz 的个人博客静态网站，可以直接上传到 GitHub Pages。

## 本地预览

直接双击打开 `index.html` 就可以预览。

如果你想用本地服务器预览，也可以在这个文件夹运行：

```powershell
python -m http.server 8000
```

然后访问：

```text
http://localhost:8000
```

## 发布到 GitHub Pages

1. 在 GitHub 创建仓库，仓库名建议用 `你的用户名.github.io`。
2. 把本文件夹里的所有文件上传到仓库根目录。
3. 打开仓库的 `Settings`。
4. 找到 `Pages`。
5. Source 选择 `Deploy from a branch`。
6. Branch 选择 `main` 和 `/root`。
7. 等待一会儿，访问 `https://你的用户名.github.io/`。

## 怎么改名字和文字

- 首页主标题：改 `index.html` 里的 `K1ndlyLiz`
- 关于页：改 `about.html`
- 第一篇文章：改 `posts/hello-blog.html`
- 颜色和排版：改 `assets/styles.css`
- 首页横幅图：替换 `assets/hero-blog.png`

## 怎么新增文章

1. 复制 `posts/hello-blog.html`。
2. 改文件名，比如 `posts/my-second-post.html`。
3. 修改里面的标题、日期和正文。
4. 在 `index.html` 的 `post-list` 区域新增一张文章卡片。

文章卡片模板：

```html
<article class="post-card">
  <a href="posts/my-second-post.html">
    <time datetime="2026-05-29">2026-05-29</time>
    <h3>你的文章标题</h3>
    <p>这里写一句文章摘要。</p>
    <span>阅读全文</span>
  </a>
</article>
```
