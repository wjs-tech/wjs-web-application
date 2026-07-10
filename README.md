# wjs-web-application

> 11年前端开发积累 · HTML/CSS 布局与业务页面实战笔记

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Maintenance](https://img.shields.io/badge/Maintained-2015--2026-blue.svg)](https://github.com/wjs-tech/wjs-web-application)

将11年前端开发积累的 HTML/CSS 实战经验进行开源沉淀，包含**可迁移的布局模式**、**各行业业务页面Demo**、**CSS 工具类封装**三大模块，见证从 Table 布局到 Flex/Grid 布局的技术演进历程。

[📖 在线展示 & 页面预览](https://wjs-tech.github.io/wjs-web-application/)

---

## ✨ 特性

- **三大模块** - 布局模式 + 业务页面 + CSS 工具类，覆盖前端页面开发全场景
- **可迁移性** - 提炼通用布局模式，可快速复用到不同行业项目
- **技术演进** - 从 2015 年 Table 布局到 2024 年容器查询，完整呈现技术发展轨迹
- **脱敏处理** - 所有业务数据均已脱敏，不含任何真实信息
- **完整注释** - 每个页面/文件都有详细注释，包含设计思路和适用场景
- **纯原生实现** - 不依赖任何框架，HTML+CSS 原生实现，开箱即用

---

## 📦 三大模块

### 🏗️ 布局模式（layout-patterns/）

可迁移复用的布局经验沉淀，从经典到现代，覆盖各种常见布局场景。

| 序号 | 布局名称 | 文件 | 年份 | 核心技术 |
|------|----------|------|------|----------|
| 1 | Table 居中布局 | [2015-table-center.html](layout-patterns/2015-table-center.html) | 2015 | table 垂直水平居中 |
| 2 | 浮动左右两栏 | [2015-float-two-column.html](layout-patterns/2015-float-two-column.html) | 2015 | float + margin |
| 3 | 浮动三栏布局 | [2015-float-three-column.html](layout-patterns/2015-float-three-column.html) | 2015 | 左右定宽中间自适应 |
| 4 | 粘性定位布局 | [2016-position-sticky.html](layout-patterns/2016-position-sticky.html) | 2016 | position: sticky |
| 5 | 圣杯布局 | [2016-holy-grail.html](layout-patterns/2016-holy-grail.html) | 2016 | 负margin经典实现 |
| 6 | 双飞翼布局 | [2016-double-wing.html](layout-patterns/2016-double-wing.html) | 2016 | 双飞翼布局 |
| 7 | Flex 弹性布局 | [2017-flex-layout.html](layout-patterns/2017-flex-layout.html) | 2017 | display: flex |
| 8 | 后台管理布局 | [2017-admin-aside.html](layout-patterns/2017-admin-aside.html) | 2017 | 左侧菜单 + 右侧内容 |
| 9 | 百分比自适应 | [2017-percentage-adaptive.html](layout-patterns/2017-percentage-adaptive.html) | 2017 | 百分比布局 |
| 10 | Grid 网格布局 | [2018-grid-layout.html](layout-patterns/2018-grid-layout.html) | 2018 | display: grid |
| 11 | 卡片瀑布流 | [2018-card-waterfall.html](layout-patterns/2018-card-waterfall.html) | 2018 | column-count |
| 12 | 等高列布局 | [2018-equal-height-columns.html](layout-patterns/2018-equal-height-columns.html) | 2018 | 等高列 |
| 13 | Sticky Footer | [2019-sticky-footer.html](layout-patterns/2019-sticky-footer.html) | 2019 | 底部粘滞布局 |
| 14 | 九宫格布局 | [2019-nine-grid.html](layout-patterns/2019-nine-grid.html) | 2019 | 九宫格 |
| 15 | Dashboard 布局 | [2020-dashboard.html](layout-patterns/2020-dashboard.html) | 2020 | 数据大屏分块布局 |
| 16 | 三明治布局 | [2020-sandwich-layout.html](layout-patterns/2020-sandwich-layout.html) | 2020 | 三段式布局 |
| 17 | 移动端自适应 | [2021-mobile-adaptive.html](layout-patterns/2021-mobile-adaptive.html) | 2021 | rem + flex 适配 |
| 18 | 手风琴折叠 | [2021-accordion.html](layout-patterns/2021-accordion.html) | 2021 | 折叠面板 |
| 19 | CSS变量主题 | [2022-css-variable-theme.html](layout-patterns/2022-css-variable-theme.html) | 2022 | 主题切换 |
| 20 | 容器查询布局 | [2024-container-queries.html](layout-patterns/2024-container-queries.html) | 2024 | Container Queries |

### 💼 业务页面（business-pages/）

各行业真实业务场景页面 Demo，数据已脱敏，可直接参考复用。

| 序号 | 行业 | 目录 | 年份 | 页面数 |
|------|------|------|------|--------|
| 1 | 银行网银系统 | [01-banking/](business-pages/01-banking/) | 2015 | 8 个 |
| 2 | 电商平台 | [02-ecommerce/](business-pages/02-ecommerce/) | 2016 | 7 个 |
| 3 | IM 即时通讯 | [03-im-system/](business-pages/03-im-system/) | 2016 | 4 个 |
| 4 | 企业管理系统 | [04-enterprise/](business-pages/04-enterprise/) | 2017 | 4 个 |
| 5 | 医院管理系统 | [05-hospital/](business-pages/05-hospital/) | 2017 | 6 个 |
| 6 | 教育学习平台 | [06-education/](business-pages/06-education/) | 2018 | 4 个 |
| 7 | 金融理财平台 | [07-finance/](business-pages/07-finance/) | 2018 | 7 个 |
| 8 | 物流管理系统 | [08-logistics/](business-pages/08-logistics/) | 2019 | 6 个 |
| 9 | 政务服务系统 | [09-government/](business-pages/09-government/) | 2019 | 4 个 |
| 10 | HR 人力资源 | [10-hr-system/](business-pages/10-hr-system/) | 2020 | 4 个 |

### 🎨 CSS 工具类（css-utils/）

常用 CSS 工具类封装，从基础到进阶，渐进式演进。

| 序号 | 分类 | 文件 | 年份 | 说明 |
|------|------|------|------|------|
| 1 | 文本工具 | [01-text.css](css-utils/01-text.css) | 2015 | 省略、对齐、换行、字重、字号 |
| 2 | 布局工具 | [02-layout.css](css-utils/02-layout.css) | 2015 | 浮动、显示、定位、溢出、宽高 |
| 3 | 颜色工具 | [03-color.css](css-utils/03-color.css) | 2016 | 文字色、背景色、边框色 |
| 4 | 边框工具 | [04-border.css](css-utils/04-border.css) | 2016 | 边框、圆角、边框样式 |
| 5 | 间距工具 | [05-spacing.css](css-utils/05-spacing.css) | 2017 | margin、padding 全方位 |
| 6 | 阴影工具 | [06-shadow.css](css-utils/06-shadow.css) | 2017 | 盒子阴影、文字阴影 |
| 7 | Flexbox 工具 | [07-flexbox.css](css-utils/07-flexbox.css) | 2018 | flex 布局全套工具类 |
| 8 | 动画工具 | [08-animation.css](css-utils/08-animation.css) | 2018 | 过渡、关键帧、变换、悬停 |
| 9 | 响应式工具 | [09-responsive.css](css-utils/09-responsive.css) | 2019 | 断点显隐、12列栅格 |
| 10 | CSS 变量主题 | [10-css-variables.css](css-utils/10-css-variables.css) | 2022 | 主题变量、暗色模式 |

---

## 🚀 快速开始

### 布局模式参考

直接在浏览器打开对应 HTML 文件查看效果，复制布局结构到你的项目中：

```html
<!-- 参考 Table 居中布局 -->
<table class="login-table">
  <tr>
    <td>
      <div class="login-box">
        <!-- 你的内容 -->
      </div>
    </td>
  </tr>
</table>
```

### CSS 工具类使用

在 HTML 中引入需要的 CSS 文件，直接使用类名：

```html
<link rel="stylesheet" href="css-utils/01-text.css">
<link rel="stylesheet" href="css-utils/05-spacing.css">

<div class="text-ellipsis m-2 p-3">
  这是一段超长文本，超出部分会显示省略号...
</div>
```

---

## 📂 目录结构

```
wjs-web-application/
├── layout-patterns/          # 布局模式笔记（可迁移复用）
│   ├── 2015-table-center.html
│   ├── 2015-float-two-column.html
│   ├── 2015-float-three-column.html
│   ├── 2016-position-sticky.html
│   ├── 2016-holy-grail.html
│   ├── 2016-double-wing.html
│   ├── 2017-flex-layout.html
│   ├── 2017-admin-aside.html
│   ├── 2017-percentage-adaptive.html
│   ├── 2018-grid-layout.html
│   ├── 2018-card-waterfall.html
│   ├── 2018-equal-height-columns.html
│   ├── 2019-sticky-footer.html
│   ├── 2019-nine-grid.html
│   ├── 2020-dashboard.html
│   ├── 2020-sandwich-layout.html
│   ├── 2021-mobile-adaptive.html
│   ├── 2021-accordion.html
│   ├── 2022-css-variable-theme.html
│   └── 2024-container-queries.html
├── business-pages/           # 业务场景页面（各行业Demo）
│   ├── 01-banking/
│   │   ├── 01-login.html
│   │   ├── 02-account-overview.html
│   │   ├── 03-transfer.html
│   │   ├── 04-transaction-record.html
│   │   ├── 05-my-wealth.html
│   │   ├── 06-credit-card.html
│   │   ├── 07-personal-center.html
│   │   ├── 08-message-center.html
│   │   └── index.html
│   ├── 02-ecommerce/
│   │   ├── 01-product-list.html
│   │   ├── 02-product-detail.html
│   │   ├── 03-shopping-cart.html
│   │   ├── 04-order-confirm.html
│   │   ├── 05-user-center.html
│   │   ├── 06-order-list.html
│   │   ├── 07-payment.html
│   │   └── index.html
│   ├── 03-im-system/
│   │   ├── 01-login.html
│   │   ├── 02-main-layout.html
│   │   ├── 03-contact-list.html
│   │   ├── 04-group-chat.html
│   │   └── index.html
│   ├── 04-enterprise/
│   │   ├── 01-admin-layout.html
│   │   ├── 02-user-manage.html
│   │   ├── 03-role-permission.html
│   │   ├── 04-dashboard.html
│   │   └── index.html
│   ├── 05-hospital/
│   │   ├── 01-outpatient-queue.html
│   │   ├── 02-patient-record.html
│   │   ├── 03-doctor-schedule.html
│   │   ├── 04-pharmacy.html
│   │   ├── 05-medical-record.html
│   │   ├── 06-nurse-station.html
│   │   └── index.html
│   ├── 06-education/
│   │   ├── 01-course-list.html
│   │   ├── 02-course-detail.html
│   │   ├── 03-exam-paper.html
│   │   ├── 04-study-report.html
│   │   └── index.html
│   ├── 07-finance/
│   │   ├── 01-finance-home.html
│   │   ├── 02-product-detail.html
│   │   ├── 03-my-assets.html
│   │   ├── 04-recharge-withdraw.html
│   │   ├── 05-fund-list.html
│   │   ├── 06-risk-assessment.html
│   │   ├── 07-transaction-record.html
│   │   └── index.html
│   ├── 08-logistics/
│   │   ├── 01-order-track.html
│   │   ├── 02-warehouse.html
│   │   ├── 03-waybill-manage.html
│   │   ├── 04-dispatch.html
│   │   ├── 05-customer-manage.html
│   │   ├── 06-finance-settlement.html
│   │   └── index.html
│   ├── 09-government/
│   │   ├── 01-gov-home.html
│   │   ├── 02-approve-list.html
│   │   ├── 03-approve-detail.html
│   │   ├── 04-notice.html
│   │   └── index.html
│   └── 10-hr-system/
│       ├── 01-employee-list.html
│       ├── 02-attendance.html
│       ├── 03-salary.html
│       ├── 04-recruitment.html
│       └── index.html
├── css-utils/                # CSS 工具类封装
│   ├── 01-text.css
│   ├── 02-layout.css
│   ├── 03-color.css
│   ├── 04-border.css
│   ├── 05-spacing.css
│   ├── 06-shadow.css
│   ├── 07-flexbox.css
│   ├── 08-animation.css
│   ├── 09-responsive.css
│   └── 10-css-variables.css
├── index.html                # 可视化展示页面
├── LICENSE                   # MIT 开源协议
└── README.md                 # 项目说明
```

---

## 🌐 浏览器兼容性

| Chrome | Edge | Firefox | Safari | IE（早期版本） |
|--------|------|---------|--------|----------------|
| ✅ 全版本 | ✅ 全版本 | ✅ 全版本 | ✅ 全版本 | ⚠️ 9+ 兼容 |

> 所有基于 Chromium 内核的浏览器（360、夸克、搜狗、UC等）均完全兼容。
> 
> 注：2018 年后的布局模式（Grid、Sticky 等）需现代浏览器支持。

---

## 📄 License

[MIT](LICENSE) © wjs (王金盛) 2015-2026
