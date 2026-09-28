# 开源与图片致谢

## 代码复用

- [Serkanbyx/travel-planner](https://github.com/Serkanbyx/travel-planner)，MIT，Copyright (c) 2026 Serkan Bayraktar。保留完整许可于 LICENSE-template。复用 package 配置、TypeScript 配置、Tailwind/PostCSS 配置、src/components/ui/dialog.tsx 与 src/lib/utils.ts；替换为北京故事界面，弹窗关闭标签已汉化。没有复用或声称实现其后端服务。
- React（MIT）、Radix UI（MIT）、Lucide（ISC）、Tailwind CSS（MIT）、Vite（MIT）、vite-plugin-singlefile（MIT）通过 npm 使用，完整版本见 package-lock.json。
- 行程地图为本项目绘制的简化 SVG 示意，不是实际道路数据或导航服务。

## 图片

1. `palace.jpg` — **20090528 Beijing Forbidden City 8074.jpg**，Jakub Hałun。来源：https://commons.wikimedia.org/wiki/File:20090528_Beijing_Forbidden_City_8074.jpg 。许可：[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)。原图未修改，界面通过 CSS 裁切展示，封面上覆盖渐变。图像衍生展示按同一许可提供。
2. `beihai.jpg` — **Beihai Park-Qiongdao Island.jpg**，Shizhao。来源：https://commons.wikimedia.org/wiki/File:Beihai_Park-Qiongdao_Island.jpg 。选择 [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/) 许可。原图未修改，界面 CSS 裁切展示。
3. `duck.jpg` — **Peking duck by Mr Wabu in Beijing.jpg**，Mr Wabu。来源：https://commons.wikimedia.org/wiki/File:Peking_duck_by_Mr_Wabu_in_Beijing.jpg 。许可：[CC BY-SA 2.0](https://creativecommons.org/licenses/by-sa/2.0/)。原图未修改，界面 CSS 裁切展示，图像衍生展示按同一许可提供。

餐馆、茶室和小展馆是虚构演示地点，照片用于营造旅行氛围，并非这些地点的实拍。请随作品保留本文件与许可文件。

新版补充：品牌叶片 Logo、通用旅行首页 SVG 插画与编号地图由本项目绘制。界面已改为目的地输入、节奏、兴趣、方案和最终行程的分步流程，Radix 弹窗关闭标签支持中英文。

## Waybloom 命名与功能参考

- 外文名称 Waybloom 由 way + bloom 组合，是本课程作品采用的设计命名；不声称独占或已注册。中文名称保留游余。
- Wanderlog：https://wanderlog.com/ ，参考其预算、行程整理的产品思路。
- TREK：https://github.com/liketrek/TREK ，参考其预算、清单及按需展开模块的思路；未复制其 AGPL 源码。
- 新增费用明细、面对面沟通卡、旅行明信片与 CSS 动效为本项目实现；沿用已采用的 React、Radix、Lucide 组件。


Material 3 视觉改版：参考 https://m3.material.io/ 与 Google 官方主题教程 https://developer.android.com/codelabs/m3-design-theming?hl=en 。采用颜色角色、形状和状态层思路；未复制网站图像或官方组件实现。新版几何旅行拼贴见 src/MaterialArt.tsx，为本项目 SVG。

