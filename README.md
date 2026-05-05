# 黄振宇 - 个人简历网站

一个沉浸式暗色风格的个人简历单页网站，展示教育背景、社会实践、技能与自我评价。

## 在线访问

**https://www.jiahao.pw**

## 技术栈

- **HTML5** 语义化标签
- **CSS3** 自定义属性、Grid、Flexbox、backdrop-filter 毛玻璃效果
- **原生 JavaScript** Intersection Observer 滚动动画、打字机特效、数字滚动计数

## 特性

- 暗色沉浸式设计，CSS 变量统一管理主题色
- 鼠标跟随的背景光晕效果
- 滚动渐入动画（Intersection Observer）
- 打字机动画展示姓名
- 关键数字滚动计数动画
- 项目卡片折叠/展开交互
- 图片灯箱（Lightbox）点击放大，支持键盘 Escape 关闭
- 响应式布局，适配移动端
- 头像呼吸光环动效

## 项目结构

```
├── index.html          # 主页面（HTML + CSS + JS 一体）
├── img/                # 图片资源
│   ├── avatar.jpg      # 头像
│   ├── cet1.png        # 四六级备考平台截图
│   ├── cet2.png
│   ├── daxuecun1~3.png # 大学村项目截图
│   ├── xianyu1~3.jpg   # 闲鱼电商截图
│   └── douyin1~2.jpg   # 抖音运营截图
├── 黄振宇个人简历.docx   # 原始简历文件
└── README.md
```

## 本地运行

直接用浏览器打开 `index.html` 即可，无需构建步骤。

```bash
# 或使用任意本地服务器
npx serve .
```

## 部署

项目已部署至 Vercel，推送到 `main` 分支后自动部署。

```bash
npx vercel --yes --prod
```

## 联系方式

- GitHub: [MuckeGG](https://github.com/MuckeGG)
