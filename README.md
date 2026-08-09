# 《山河谋》GitHub Pages 发布包

本目录已经按 GitHub Pages 的根目录结构整理完成，可直接上传到仓库根目录。

## 必须保持的结构

```text
/
├── index.html
├── assets/
│   ├── bgm/
│   └── video/
├── README.md
├── .nojekyll
└── 视频生成提示词归档.md
```

不要将整个发布包再套入一层子文件夹，否则 GitHub Pages 无法在仓库根目录找到 `index.html`。

## 部署

1. 将本目录内的全部文件和文件夹上传到 GitHub 仓库根目录。
2. 打开仓库的 **Settings → Pages**。
3. Source 选择 **Deploy from a branch**。
4. Branch 选择 **main**，目录选择 **/ (root)**，然后保存。
5. 等待 Actions 构建成功后访问：`https://你的用户名.github.io/仓库名/`。

## 已校验内容

- 页面入口为 `index.html`。
- 所有 41 个运行时媒体引用均存在。
- 已包含 4 段实际使用的视频：开场、午门剧情、萧决剧情、沈砚剧情。
- 未提供的重生转场视频插槽已在发布版中安全关闭，不会产生无效请求。
- BGM 授权信息位于 `assets/bgm/CREDITS_AND_LICENSE.md`。

