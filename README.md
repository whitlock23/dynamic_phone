# dynamic_phone

一个用原生 HTML + JS 复刻的"动态捡手机"网页，模拟 iOS 交互：锁屏（密码 1234）、桌面、KakaoTalk 聊天、相册、FaceTime、X / 推特、备忘录、日历、Instagram、浏览器搜索等。

## 本地预览

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 结构

- `index.html` — UI 和路由渲染
- `data.js` — 全部内容数据（主人资料、聊天、推文、相册），改这个文件就能换成"另一个人的手机"
- `img/` — 壁纸、头像和推文配图

## 密码

`1234`
