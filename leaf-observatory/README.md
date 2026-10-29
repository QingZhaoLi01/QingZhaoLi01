# 叶序 LEAF

以真实叶片纹理、四季色彩和物理风场构成的交互视觉实验。

## 本地运行

无需安装依赖或构建。在本目录运行：

```sh
python3 -m http.server 8080
```

浏览器打开 `http://localhost:8080`。

## 体验

- 按 `Asia/Shanghai` 日期和北半球气象季节进入当前季节。
- 每季约两屏多滚动距离，长时间停留后缓慢过渡，持续循环。
- Matter.js 模拟重力、空气阻力、风力及叶片翻转。
- 指针影响气流，可唤起阵风、调节风力、暂停动效或开启合成风声。
- 响应式布局，支持系统的减少动态效果设置。

## 文件

- `index.html`：页面结构与说明。
- `style.css`：视觉样式和手机适配。
- `app.js`：四季、物理模拟与交互。
- `assets/leaf.png`：基于摄影纹理处理的透明叶片。
- `assets/matter.min.js`：Matter.js 0.20.0（MIT License，许可证见文件头）。

## 素材说明

叶片原始素材来源：[PNGWing](https://www.pngwing.com/tr/free-png-yzxvl)，经生成式工具处理透明背景。季节颜色为艺术化演绎；冬季使用枯叶褐色。使用素材时请遵守原站授权条款；本项目未对第三方素材授予额外许可。

字体通过 Google Fonts 加载 DM Sans 与 Noto Serif SC；网络不可用时使用系统字体。风场为物理模拟数据，并非实时气象观测。

当前在线版本：https://leaf-observatory.gfghjkl.chatgpt.site （访问权限依原站设置）。
