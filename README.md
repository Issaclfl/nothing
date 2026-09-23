# 蕾塞 · 动态立绘（NFC 雨夜页）

发丝衣角随风、雨夜街景、自动播放《你的泪 我的雨季》。

## 本地预览

直接双击 `index.html`，或：

```powershell
cd C:\Users\Lawson\Desktop\reze-live-portrait
python -m http.server 8080
```

浏览器打开 `http://localhost:8080`。

## 发布到 GitHub Pages（账号 IsaacIfl）

1. 在 GitHub 新建仓库：`nothing`（Public）
2. 在本文件夹初始化并推送：

```powershell
cd C:\Users\Lawson\Desktop\reze-live-portrait
git init
git add .
git commit -m "Reze live portrait for NFC"
git branch -M main
git remote add origin https://github.com/Issaclfl/nothing.git
git push -u origin main
```

3. 仓库 → Settings → Pages → Source 选 `Deploy from a branch`，Branch 选 `main` / `/ (root)`，Save
4. 等 1–2 分钟，访问：

   `https://isaacifl.github.io/nothing/`

   （若 Pages 用户名大小写不同，以仓库 Settings → Pages 显示的 URL 为准）

## 写入 NFC

1. 手机安装 NFC 写入类 App（如 NFC Tools）
2. 写入 **URL / Web Link** 记录：
   `https://isaacifl.github.io/nothing/`
3. 贴到卡片/挂饰上，用手机背面一贴即可打开

## 说明

- NFC 标签只存网址，不存图片/音乐文件
- 手机浏览器可能拦截有声自动播放，需点一下「进入雨夜」
- 请确认音乐与图片仅供个人使用，勿公开传播版权素材
