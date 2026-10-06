# 设计模板与组件 · GitHub Top 50 力量地图

> 数据快照：GitHub API 实测于 2026-10-06/07（gh CLI GraphQL/REST，账号 wulinjun007）
> 入选口径：以「UI 组件库 / 界面模板 / 设计基建（CSS 底座、图标、动效、图表）」为核心产出的公开仓库，非 archived，按 Star 降序取前 50。
> 与 2026-10-02《设计系统 TOP50》（`design-systems-top50-2026-10.md`）划界：那份是**设计规范/系统层**（含不开源规范如 Apple HIG），这份是**可安装、可复制源码的组件与模板层**。两榜在头部组件库上自然重叠约 15–20 项。

## 总览

| 指标 | 值 |
|---|---|
| 上榜项目 | 50 |
| 合计 Star | **2,135,844（约 214 万）** |
| 分类 | 组件库 20 / 动效 7 / 模板后台 8 / 图标 5 / CSS 底座 4 / 无头组件 2 / 图表 3 / 邮件组件 1 |
| Star 区间 | 18,567 – 174,987 |
| 许可构成 | MIT 绝对主流（40+），Apache-2.0 ×4，CC0 ×1，⚠️ 特例见「风险标注」 |

## 榜单（Top 50）

| # | 项目 | 分类 | Star | 许可 | 可借鉴能力（本站如何调用见 PRD §6） |
|---|---|---|---|---|---|
| 1 | [twbs/bootstrap](https://github.com/twbs/bootstrap) | 组件库 | 174,987 | MIT | 12 列栅格 + 响应式工具类鼻祖；`.btn` 语义变体是组件 API 设计范本 |
| 2 | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 组件库 | 125,209 | MIT | 「源码分发」模式：组件代码拷进项目而非装依赖；CSS 变量语义 Token（`--primary/--muted`）+ CVA 变体工程 |
| 3 | [ant-design/ant-design](https://github.com/ant-design/ant-design) | 组件库 | 99,693 | MIT | 企业级 B 端设计价值观；表格/表单/弹窗密度规范；四层主题 Token 映射 |
| 4 | [mui/material-ui](https://github.com/mui/material-ui) | 组件库 | 99,134 | MIT | Material elevation 阴影体系与动效曲线；无障碍开箱即用 |
| 5 | [tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) | CSS 底座 | 97,783 | MIT | 原子类=设计令牌落地层；间距/字号刻度约束；暗色模式策略 |
| 6 | [PanJiaChen/vue-element-admin](https://github.com/PanJiaChen/vue-element-admin) | 模板后台 | 90,161 | MIT | 中后台信息架构范本（侧边导航+权限路由+仪表盘），中文后台模板顶流 |
| 7 | [animate-css/animate.css](https://github.com/animate-css/animate.css) | 动效 | 82,853 | ⚠️ Hippocratic 2.1 | 进出场动效词表（fade/slide/zoom × 方向），用 class 约束动效防滥用 |
| 8 | [chartjs/Chart.js](https://github.com/chartjs/Chart.js) | 图表 | 67,733 | MIT | 轻量图表默认美学；「配置即图表」的 API 设计；响应式 canvas |
| 9 | [apache/echarts](https://github.com/apache/echarts) | 图表 | 67,457 | Apache-2.0 | 大数据量渲染双引擎；系列/坐标系/组件三层可视化模型 |
| 10 | [ElemeFE/element](https://github.com/ElemeFE/element) | 组件库 | 54,031 | MIT | 中文 B 端组件库启蒙；「文档即产品」范式 |
| 11 | [ionic-team/ionic-framework](https://github.com/ionic-team/ionic-framework) | 组件库 | 52,686 | MIT | 跨端自适应组件（iOS/MD 双主题）；移动手势交互 |
| 12 | [jgthms/bulma](https://github.com/jgthms/bulma) | CSS 底座 | 50,052 | MIT | 无 JS 纯 CSS 组件范式；`is-*` modifiers 语法 |
| 13 | [ColorlibHQ/AdminLTE](https://github.com/ColorlibHQ/AdminLTE) | 模板后台 | 45,638 | MIT | 经典管理台布局（顶栏+侧栏+卡片栅格）；开箱页面模板集 |
| 14 | [saadeghi/daisyui](https://github.com/saadeghi/daisyui) | 组件库 | 42,549 | MIT | Tailwind 之上的语义组件类；30+ 主题切换的令牌方案 |
| 15 | [tabler/tabler](https://github.com/tabler/tabler) | 模板后台 | 41,821 | MIT | 设计质量最高的开源后台之一；卡片化仪表盘 + 精致排版 |
| 16 | [vuetifyjs/vuetify](https://github.com/vuetifyjs/vuetify) | 组件库 | 41,037 | ⚠️ license 识别为 NOASSERTION（项目声明 MIT） | Material Design 全量实现；网格系统与断点策略 |
| 17 | [chakra-ui/chakra-ui](https://github.com/chakra-ui/chakra-ui) | 组件库 | 40,676 | MIT | 可访问性优先（WAI-ARIA 全覆盖）；style props 令牌化样式 |
| 18 | [ant-design/ant-design-pro](https://github.com/ant-design/ant-design-pro) | 模板后台 | 38,833 | MIT | 企业中台脚手架；ProTable/ProForm「组件组合优于配置爆炸」思想 |
| 19 | [refinedev/refine](https://github.com/refinedev/refine) | 模板后台 | 35,761 | MIT | headless 后台框架：数据契约与 UI 解耦 |
| 20 | [motiondivision/motion](https://github.com/motiondivision/motion) | 动效 | 33,846 | MIT | （Framer Motion）spring 物理动效；layout FLIP 动画；编排 stagger |
| 21 | [vbenjs/vue-vben-admin](https://github.com/vbenjs/vue-vben-admin) | 模板后台 | 33,554 | MIT | 现代中后台工程范本（Monorepo + 权限 + 多主题） |
| 22 | [airbnb/lottie-web](https://github.com/airbnb/lottie-web) | 动效 | 32,145 | MIT | AE 动画直出 Web；复杂品牌动效的落地方案 |
| 23 | [mantinedev/mantine](https://github.com/mantinedev/mantine) | 组件库 | 31,800 | MIT | 120+ 组件 + hooks 库；暗色模式与 CSS 变量双轨 |
| 24 | [heroui-inc/heroui](https://github.com/heroui-inc/heroui) | 组件库 | 30,877 | Apache-2.0 | Tailwind + Framer Motion 的现代组件美学；玻璃拟态 |
| 25 | [foundation/yeti](https://github.com/foundation/yeti) | CSS 底座 | 29,799 | ⚠️ license 识别为 NOASSERTION（项目声明 MIT） | 语义化栅格与响应式先驱（已更名、低维护，历史参考位） |
| 26 | [pmndrs/react-spring](https://github.com/pmndrs/react-spring) | 动效 | 29,167 | MIT | 弹簧物理插值动画，中断可续 |
| 27 | [GreenSock/GSAP](https://github.com/GreenSock/GSAP) | 动效 | 28,844 | 标准许可需自查（仓库未标 SPDX） | 时间轴编排动效标杆；ScrollTrigger 滚动叙事 |
| 28 | [tailwindlabs/headlessui](https://github.com/tailwindlabs/headlessui) | 无头组件 | 28,767 | MIT | 无样式逻辑组件（Dialog/Menu/Listbox）：行为与样式分离 |
| 29 | [michalsnik/aos](https://github.com/michalsnik/aos) | 动效 | 28,059 | MIT | 滚动触发进场最小方案（`data-aos` 属性化） |
| 30 | [element-plus/element-plus](https://github.com/element-plus/element-plus) | 组件库 | 27,798 | MIT | Vue3 生态 B 端首选；暗色变量与国际化 |
| 31 | [recharts/recharts](https://github.com/recharts/recharts) | 图表 | 27,618 | MIT | 声明式组合式 React 图表 API |
| 32 | [quasarframework/quasar](https://github.com/quasarframework/quasar) | 组件库 | 27,207 | MIT | 一套代码全平台（SPA/PWA/桌面/移动） |
| 33 | [marmelab/react-admin](https://github.com/marmelab/react-admin) | 模板后台 | 26,954 | MIT | 后台 CRUD 组件化（Resource/List/Show 抽象） |
| 34 | [feathericons/feather](https://github.com/feathericons/feather) | 图标 | 26,011 | MIT | 24×24 stroke 图标黄金标准（本站图标同规格手绘） |
| 35 | [simple-icons/simple-icons](https://github.com/simple-icons/simple-icons) | 图标 | 25,973 | CC0-1.0 | 3000+ 品牌 SVG 图标，公有领域 |
| 36 | [lucide-icons/lucide](https://github.com/lucide-icons/lucide) | 图标 | 24,878 | ⚠️ license 识别为 NOASSERTION（项目声明 ISC） | feather 社区续作，最全 stroke 图标体系 |
| 37 | [vant-ui/vant](https://github.com/vant-ui/vant) | 组件库 | 24,385 | MIT | 移动端电商组件规范（SKU 选择器/地址编辑等业务组件） |
| 38 | [tailwindlabs/heroicons](https://github.com/tailwindlabs/heroicons) | 图标 | 23,857 | MIT | Tailwind 官方图标，24/20/16 三刻度 |
| 39 | [react-bootstrap/react-bootstrap](https://github.com/react-bootstrap/react-bootstrap) | 组件库 | 22,602 | MIT | Bootstrap 组件的 React 重实现 |
| 40 | [jlmakes/scrollreveal](https://github.com/jlmakes/scrollreveal) | 动效 | 22,479 | ⚠️ 仓库无 LICENSE 文件 | 声明式滚动显现；商用前需联系作者确认 |
| 41 | [palantir/blueprint](https://github.com/palantir/blueprint) | 组件库 | 22,126 | ⚠️ license 识别为 NOASSERTION（项目声明 Apache-2.0） | 数据密集桌面端组件（表格虚拟滚动/日期范围选择） |
| 42 | [tabler/tabler-icons](https://github.com/tabler/tabler-icons) | 图标 | 21,925 | MIT | 5800+ stroke 图标，与 Tabler 后台同一设计语言 |
| 43 | [vueComponent/ant-design-vue](https://github.com/vueComponent/ant-design-vue) | 组件库 | 21,673 | ⚠️ license 识别为 NOASSERTION（项目声明 MIT） | Ant Design 的 Vue 实现（Templafy 起源、社区维护） |
| 44 | [microsoft/fluentui](https://github.com/microsoft/fluentui) | 组件库 | 20,312 | ⚠️ license 识别为 NOASSERTION（项目声明 MIT） | 微软 Fluent 2 React 实现；跨平台令牌体系 |
| 45 | [resend/react-email](https://github.com/resend/react-email) | 邮件组件 | 19,813 | MIT | 邮件组件化：组件 → 兼容各客户端的 HTML 邮件 |
| 46 | [lin-xin/vue-manage-system](https://github.com/lin-xin/vue-manage-system) | 模板后台 | 19,613 | MIT | 轻量中文后台模板，学习成本最低 |
| 47 | [radix-ui/primitives](https://github.com/radix-ui/primitives) | 无头组件 | 19,365 | MIT | 无头组件事实标准；focus 管理与键盘交互教科书（shadcn 底座） |
| 48 | [antfu/unocss](https://github.com/antfu/unocss) | CSS 底座 | 18,974 | ⚠️ license 识别为 NOASSERTION（项目声明 MIT） | 按需原子 CSS 引擎；attributify 模式 |
| 49 | [framework7io/framework7](https://github.com/framework7io/framework7) | 组件库 | 18,762 | MIT | 类原生移动 UI（Swipeout/ActionSheet 手势组件最全） |
| 50 | [tusen-ai/naive-ui](https://github.com/tusen-ai/naive-ui) | 组件库 | 18,567 | MIT | 全量 TypeScript；CSS-in-Vars 主题定制彻底 |

## 遗珠名单（51–60，差一线之遥）

uikit/uikit 18,536 · sweetalert2/sweetalert2 18,100 · satnaing/shadcn-admin 15,612 · soybeanjs/soybean-admin 15,051 · primefaces/primevue 14,455 · plouc/nivo 14,106 · formkit/auto-animate 13,926 · ant-design/ant-design-mobile 12,058 · mui/base-ui 11,079 · douyinfe/semi-design 10,404

## 排除记录（口径透明）

| 仓库 | Star | 排除原因 |
|---|---|---|
| picocss/pico | 16,861 | 已 archived（2026-10 确认） |
| shoelace-style/shoelace | 13,832 | 已 archived（后继为 Web Awesome，未上榜） |
| htmlstream/preline | — | 仓库路径失效未定位（REST 搜索限额），未计入 |

## 实测勘误（供后续引用）

- Bootstrap 正本在 `twbs/bootstrap`（不是 getbootstrap org）
- Blueprint 归 Palantir：`palantir/blueprint`
- GSAP 公开仓库为 `GreenSock/GSAP`（Star 28,844，但仓库未标 SPDX 许可，商用需自查其标准许可条款）
- `preline/preline` 与 `htmlstream/preline` 均 404，该项目仓库待重新定位

## 风险标注汇总

1. **animate.css（第 7 名）**：Hippocratic 2.1 许可——禁止一般恶意用途的道德许可，非标准 OSI 开源，企业引入前过法务。本站只借鉴其「动效词表」思想，不引入其代码。
2. **scrollreveal（第 40 名）**：仓库无 LICENSE 文件 = 默认版权保留，不可直接商用。本站不使用。
3. **GSAP（第 27 名）**：Star 高但许可文件未标 SPDX；GSAP 现为 Webflow 所有、标准许可「免费但需注册」。借鉴思想不抄代码。
4. **foundation/yeti（第 25 名）**：已更名且低维护，作历史参考位保留，不入推荐列表。

## 复现方式

```bash
gh api graphql -f query='{ r0: repository(owner:"twbs", name:"bootstrap"){ stargazerCount } ... }'
# 或逐仓 REST：
gh api repos/twbs/bootstrap --jq '.stargazers_count'
```

数据文件：`result.tsv`（本目录）；采集脚本思路见方法论页（网站 `#/method`）。
