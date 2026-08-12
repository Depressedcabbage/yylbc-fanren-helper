# 人物肖像图片放置说明

将人物图片放入此目录，文件名与下表"文件名"列一致即可自动匹配。

## 支持的格式
- `.webp`（推荐，体积小质量好）
- `.png`（备选）
- `.jpg`（备选）

## 图片规格建议
- 尺寸：400×520（竖版 10:13）或 600×600（正方形）
- 格式：WebP 优先，PNG 备选
- 背景：深色/透明，让 CSS 渐变叠加层自然融合

## 人物与文件映射表（40 张）

| 人物 | 文件名 | 卡片位置 |
|------|--------|----------|
| 韩立 | `hanli.webp` | 全宽主角卡 |
| 南宫婉 | `nangongwan.webp` | 道侣 |
| 大衍神君 | `dayanshenjun.webp` | 师尊 |
| 紫灵 | `ziling.webp` | 红颜知己 |
| 银月 | `yinyue.webp` | 红颜知己 |
| 墨大夫 | `modafu.webp` | 师尊 |
| 元瑶 | `yuanyao.webp` | 红颜知己 |
| 厉飞雨 | `lifeiyu.webp` | 挚友 |
| 青元子 | `qingyuanzi.webp` | 挚友 |
| 李化元 | `lihuayuan.webp` | 师尊 |
| 令狐老祖 | `linghulaozu.webp` | 师尊 |
| 宝花 | `baohua.webp` | 敌人 |
| 鲲鹏 | `kunpeng.webp` | 敌人 |
| 天澜圣女 | `tianlanshengnv.webp` | 人界 |
| 墨彩环 | `mocaihuan.webp` | 人界 |
| 陈巧倩 | `chenqiaoqian.webp` | 人界 |
| 冰凤 | `bingfeng.webp` | 挚友 |
| 极阴祖师 | `jiyinzushi.webp` | 敌人 |
| 玄骨上人 | `xuangushangren.webp` | 敌人 |
| 风希 | `fengxi.webp` | 敌人 |
| 乾老魔 | `qianlaomo.webp` | 敌人 |
| 马良 | `maliang.webp` | 敌人 |
| 古或今 | `guhuojin.webp` | 终极BOSS |
| 蟹道人 | `xiedaoren.webp` | 挚友 |
| 轮回殿主 | `lunhuidianzhu.webp` | 盟友 |
| 莫简离 | `mojianli.webp` | 挚友 |
| 石穿空 | `shichuankong.webp` | 挚友 |
| 慕沛灵 | `mupeiling.webp` | 名义侍妾 |
| 寒骊上人 | `hanlishangren.webp` | 敌人 |
| 齐云霄 | `qiyunxiao.webp` | 挚友 |
| 付天华 | `futianhua.webp` | 配角 |
| 金光上人 | `jinguangshangren.webp` | 敌人 |
| 云露老祖 | `yunlulaozu.webp` | 师长 |
| 骷髅 | `kulou.webp` | 敌人 |
| 红粉 | `hongfen.webp` | 敌人 |
| 温天仁 | `wentianren.webp` | 敌人 |
| 圭灵 | `guiling.webp` | 盟友 |
| 洞天鼠王 | `dongtianshuwang.webp` | 妖王 |
| 昆吾三老 | `kunwusanlao.webp` | 师长 |
| 妍丽 | `yanli.webp` | 挚友 |

## 未提供图片的降级方案
未放置图片的角色自动退回纯 CSS/SVG 原创意象肖像，
不会出现破损图片图标（`onerror="this.style.display='none'"`）。

## 生效方式
放入图片后刷新页面即可，无需修改任何代码。
卡片顶部命牌区和弹窗详情区都会同步更新。
