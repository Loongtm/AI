# TradingView 脚本运行说明（看不到底部 Pine Editor 时）

你这张截图里是在 `cn.tradingview.com`，并且你在“搜索工具或功能”里输入了英文 `pine editor`，结果为空。
这种情况很常见，通常是 **中文界面关键词不匹配** 或 **当前站点/布局不支持 Pine 编辑器入口**。

## 先做这 4 步（按顺序）
1. 先确认已登录 TradingView 账号。
2. 在顶部搜索框不要输入英文，改搜：
   - `Pine 脚本编辑器`
   - `脚本编辑器`
   - `Pine 编辑器`
3. 如果仍然没有结果，切换到国际站：`https://www.tradingview.com/chart/`（不要用 `cn.` 子域名）。
4. 进入后再看底部面板是否出现：`Pine Editor / Strategy Tester / Trading Panel`。

## 方法 1：通过底部面板打开（最稳）
1. 把鼠标移到图表最底边（时间轴上方）。
2. 若看到可拖动边缘，向上拖展开底部面板。
3. 在底部标签中点击 `Pine Editor`（中文可能显示“Pine 脚本编辑器”）。

## 方法 2：通过顶部“更多/布局”恢复面板
1. 点击右上角 `…`（更多）或布局相关菜单。
2. 找到“显示底部面板/重置布局”选项并启用。
3. 底部面板恢复后再打开 Pine Editor。

## 方法 3：你当前页面如果属于“简化图表/经纪商图表”
- 一些简化页面只支持看盘和下单，不开放 Pine 编辑。
- 请改用 **Supercharts（完整图表）** 页面：
  - `https://www.tradingview.com/chart/`

## 能看到编辑器后，怎么运行脚本
1. 打开 Pine Editor。
2. 粘贴 `tradingview_ai_entry_tp_sl.pine`。
3. 点击“保存”。
4. 点击“添加到图表”。
5. 因为脚本是 `strategy(...)`，结果在“策略测试（Strategy Tester）”查看。

## 仍然没有 Pine Editor？
请把下面 3 张截图发我，我直接按你的界面标注：
1. 顶部工具栏完整截图（包含右上角菜单）。
2. 底部区域完整截图（时间轴以下有没有可展开栏）。
3. 浏览器地址栏截图（确认是否 `cn.tradingview.com` 还是 `www.tradingview.com`）。
