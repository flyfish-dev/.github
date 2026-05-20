# Flyfish Dev

<p align="center">
  <a href="https://viewer.flyfish.dev"><img alt="Flyfish Viewer" src="https://img.shields.io/badge/Flyfish%20Viewer-online-2563eb?style=for-the-badge"></a>
  <a href="https://demo.flyfish.group"><img alt="Office Preview Demo" src="https://img.shields.io/badge/Office%20Preview-demo-16a34a?style=for-the-badge"></a>
  <a href="https://dev.flyfish.group/shop"><img alt="Flyfish Shop" src="https://img.shields.io/badge/Shop-license-f97316?style=for-the-badge"></a>
</p>

Flyfish Dev 是飞鱼开源工作室的工程与产品交付组织，长期关注浏览器端文件预览、Office 文档解析渲染、低代码系统集成和企业私有化交付。

我们希望把复杂的文档预览能力做成可以直接接入、可以独立部署、可以持续演进的产品模块：不依赖后端转码服务，不把业务文件上传到第三方服务，尽可能在浏览器内完成解析、渲染和交互。

## 快速入口

| 入口 | 地址 | 适合谁 |
| --- | --- | --- |
| 全格式文件预览 | [viewer.flyfish.dev](https://viewer.flyfish.dev) | 想快速体验 Word、Excel、PPT、PDF、OFD、CAD、电子书等多格式预览的开发者 |
| Office 预览 Demo | [demo.flyfish.group](https://demo.flyfish.group) | 需要验证 DOC、DOCX、PPT、PPTX、XLS、XLSX 渲染效果的客户 |
| Office 产品页 | [product.flyfish.group](https://product.flyfish.group) | 需要了解授权、部署、购买和交付方案的团队 |
| 飞鱼小铺 | [dev.flyfish.group/shop](https://dev.flyfish.group/shop) | 需要购买授权、开通源码研究版或商业部署服务的用户 |
| 公开仓库入口 | [github.com/flyfish-dev](https://github.com/flyfish-dev) | 需要查看公开产物、文档和示例的开发者 |

## 精选项目

| 项目 | 定位 | 亮点 | 链接 |
| --- | --- | --- | --- |
| `file-viewer` | 全格式文件预览公开成品仓库 | 提供 Vue2.7 / Vue3 文件预览产物、在线 Demo、文档、样例和 npm 包入口，覆盖 Office、PDF、OFD、CAD、电子书、图片、音视频、Markdown、代码文本等常见业务附件 | [仓库](https://github.com/flyfish-dev/file-viewer) · [Demo](https://viewer.flyfish.dev) |
| `office-preview-js` | Office 多格式纯前端预览 Demo | 面向 DOC、DOCX、PPT、PPTX、XLS、XLSX 的静态部署演示，解析能力以 WASM 和按需加载为核心，适合验证企业内网、OA、档案、合同、标书等场景 | [仓库](https://github.com/flyfish-dev/office-preview-js) · [Demo](https://demo.flyfish.group) |
| `styled-exceljs` | 增强型 Excel 解析与渲染基础库 | 基于 SheetJS Community Edition 扩展样式、尺寸、图片绘图、图表、合并校验和浏览器 HTML 渲染能力，面向更高保真的 XLS / XLSX 预览 | [仓库](https://github.com/flyfish-dev/styled-exceljs) · [npm](https://www.npmjs.com/package/styled-exceljs) |
| `product-web` | Flyfish Office Preview 产品官网 | 承载中英文营销页、SEO 预渲染、价格说明、购买入口、客服二维码和部署介绍，是 Office 预览产品的公开展示站 | [仓库](https://github.com/flyfish-dev/product-web) · [官网](https://product.flyfish.group) |
| `pptviewer` | PowerPoint `.ppt` 预览静态产物 | 专注经典 PowerPoint 97-2003 二进制 `.ppt` 文件在线预览，包含可直接部署的静态页面和 worker 产物 | [仓库](https://github.com/flyfish-dev/pptviewer) · [Demo](https://ppt.flyfish.dev) |

## 能力矩阵

| 能力方向 | 覆盖内容 |
| --- | --- |
| Word 预览 | `.doc`、`.docx`，面向历史公文、合同、接口规范、档案材料等页面化阅读场景 |
| PowerPoint 预览 | `.ppt`、`.pptx`，支持演示文稿浏览、图片和常见图形展示，适合方案、课件、汇报材料 |
| Excel 预览 | `.xls`、`.xlsx`，关注单元格样式、合并单元格、行列尺寸、工作表切换和业务表格阅读体验 |
| 通用文件预览 | PDF、OFD、CAD、图片、音频、视频、Markdown、代码文本、电子书等多格式附件 |
| 纯前端部署 | 静态站点、Vercel、Nginx、OSS、内网服务器均可承载，适合轻量交付和私有化集成 |
| 系统集成 | 可作为 Vue 组件使用，也可独立部署后通过 iframe 嵌入 OA、知识库、CRM、工单、档案和低代码平台 |

## 我们更关注什么

- **真实业务文件。** 预览器不是只打开标准样例，而是要面对历史 `.doc`、复杂表格、企业模板、扫描件、汇报 PPT 和混合附件。
- **可部署性。** 公开产物尽量保持静态部署友好，减少后端依赖，让小团队也能快速上线。
- **按需加载。** 重型解析器和渲染器只在对应格式被打开时加载，降低首屏负担。
- **交付边界清晰。** 公开仓库用于演示、评估和公开产物分发；源码交付、商业授权、私有部署和定制开发按授权方案单独提供。
- **持续迭代。** Office 兼容性、Excel 视觉保真、PPT 图形处理、文档页面体验和多语言产品页都在持续更新。

## 推荐接入路径

| 需求 | 推荐项目 | 说明 |
| --- | --- | --- |
| 想快速接入通用文件预览组件 | `file-viewer` | 适合应用系统附件预览、知识库、流程表单、低代码平台 |
| 只关注 Office 六种格式 | `office-preview-js` | 适合验证 Office 解析渲染效果和私有化部署方案 |
| 需要增强 Excel 表格保真 | `styled-exceljs` | 适合二开表格预览、报表渲染和浏览器端工作簿展示 |
| 需要了解商业授权和服务 | `product-web` | 适合客户、采购、技术负责人快速判断购买方案 |
| 需要经典 `.ppt` 预览能力 | `pptviewer` | 适合老系统历史 PPT 文件在线浏览 |

## 联系与支持

| 类型 | 联系方式 |
| --- | --- |
| 购买入口 | [https://dev.flyfish.group/shop](https://dev.flyfish.group/shop) |
| 产品官网 | [https://product.flyfish.group](https://product.flyfish.group) |
| 在线 Demo | [https://demo.flyfish.group](https://demo.flyfish.group) |
| 售后邮箱 | [wybaby168@gmail.com](mailto:wybaby168@gmail.com) |
| 微信客服 | `Yous_Gift` |

如需评估商业接入，请尽量提供部署域名、需要支持的格式、是否离线内网部署、文件大小范围、预估访问量和前端技术栈。这样可以更快判断适合使用公开成品、单格式源码研究版、商业版还是企业版源码交付。

