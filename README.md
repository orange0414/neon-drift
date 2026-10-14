# NEON DRIFT · 霓虹穿梭

一个零依赖、适合手机和 iPad 的 HTML5 触屏小游戏。躲避红色陨石、收集金色能量球，争取最高分。

## 本地游玩

使用浏览器打开 `index.html` 即可。游戏逻辑无需网络；最高分保存在当前浏览器的 `localStorage` 中。

## GitHub Pages 部署

1. 在 GitHub 新建公开仓库，例如 `neon-drift`。
2. 将 `index.html` 和 `README.md` 上传至仓库根目录（不要只上传 ZIP）。
3. 进入 **Settings → Pages → Build and deployment**，选择 **Deploy from a branch**。
4. Branch 选 `main`，Folder 选 `/(root)`，点击 **Save**。
5. Pages 发布后，访问 `https://你的用户名.github.io/neon-drift/`。

## 操作

- 手机 / iPad：按住画面滑动以移动飞船。
- 电脑：鼠标按住拖动或按 `←` / `→` 键。
- 暂停按钮或空格暂停。
- 每局 3 条生命；金色能量球 +25 分；最高分自动保存在本机浏览器中。

## 说明

纯静态部署，无需服务器和数据库。最高分不会跨设备同步；清除浏览器网站数据可能重置纪录。