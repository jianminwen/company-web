# 公司官网项目

这是一个基于 Vue.js 2.x 开发的公司官网项目。

## 技术栈

- Vue.js 2.x
- Vue Router
- Vuex
- Webpack 3.x
- Axios
- Animate.css
- Swiper
- WOW.js

## 系统要求

- Node.js >= 6.0.0
- npm >= 3.0.0

## 项目结构

```
company-web/
├── build/          # 构建相关配置
├── config/         # 项目配置文件
├── src/            # 源代码
├── static/         # 静态资源
├── .babelrc        # Babel 配置
├── .editorconfig   # 编辑器配置
├── .gitignore      # Git 忽略文件
├── .postcssrc.js   # PostCSS 配置
├── index.html      # HTML 模板
└── package.json    # 项目依赖配置
```

## 安装

1. 克隆项目
```bash
git clone [项目地址]
cd company-web
```

2. 安装依赖
```bash
npm install
```

> 注意：如果安装过程中遇到依赖错误，请尝试以下步骤：
> 1. 删除 `node_modules` 文件夹和 `package-lock.json` 文件
> 2. 清除 npm 缓存：`npm cache clean --force`
> 3. 重新安装依赖：`npm install`
> 
> 如果仍然遇到 `babel-runtime` 相关错误，请确保：
> 1. Node.js 版本符合要求（>= 6.0.0）
> 2. 尝试使用 `npm install babel-runtime --save` 单独安装

## 开发

启动开发服务器：
```bash
npm run dev
```

## 构建

构建生产环境代码：
```bash
npm run build
```

## 浏览器支持

- Chrome > 1%
- Firefox > 1%
- Safari > 1%
- Edge > 1%
- 不支持 IE8 及以下版本

## 作者

jmin

## 许可证

私有项目