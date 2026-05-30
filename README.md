# 📷 image-hosting

> 免费图床 - 基于 GitHub 的免费图片托管仓库
>
> ## 简介
>
> 本仓库用作免费图床，利用 GitHub 存储图片，并通过 jsDelivr CDN 或 raw.githubusercontent.com 提供快速访问链接。
>
> ## 使用方法
>
> ### 方法一：通过 GitHub 网页上传
>
> 1. 进入本仓库，点击 **Add file** → **Upload files**
> 2. 2. 拖拽或选择图片文件上传
>    3. 3. 填写 commit 信息，点击 **Commit changes**
>       4. 4. 上传成功后，点击图片文件，获取图片 URL
>         
>          5. ### 方法二：使用 Git 命令行上传
>         
>          6. ```bash
>             git clone https://github.com/big-muffin408/image-hosting.git
>             cd image-hosting
>             # 将图片复制到仓库目录
>             git add .
>             git commit -m "上传图片"
>             git push
>             ```
>
> ## 图片链接格式
>
> 上传图片后，可以使用以下格式的链接：
>
> ### 原始链接（raw）
>
> ```
> https://raw.githubusercontent.com/big-muffin408/image-hosting/main/图片文件名
> ```
>
> ### jsDelivr CDN 加速链接（国内访问更快）
>
> ```
> https://cdn.jsdelivr.net/gh/big-muffin408/image-hosting@main/图片文件名
> ```
>
> ### Markdown 引用格式
>
> ```markdown
> ![图片描述](https://cdn.jsdelivr.net/gh/big-muffin408/image-hosting@main/图片文件名)
> ```
>
> ## 建议的目录结构
>
> ```
> image-hosting/
> ├── README.md
> ├── 2025/           # 按年份分类
> │   ├── 01/         # 按月份分类
> │   └── 02/
> └── images/         # 通用图片目录
> ```
>
> ## 注意事项
>
> - 本仓库为 **公开仓库**，上传的图片任何人都可以访问，请勿上传隐私图片
> - - GitHub 单个仓库建议不超过 1GB，单个文件不超过 100MB
>   - - 支持常见图片格式：jpg、png、gif、svg、webp 等
>     - - 使用 jsDelivr CDN 时，新上传的图片可能需要几分钟才能生效
