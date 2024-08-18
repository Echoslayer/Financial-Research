---
title: 筆記常用Prompts
draft: false
tags:
---

```
我現在有一個字典，幫我將它轉換為方便在obsidian顯示的表格：
```

```
字典程式部分：


我現在有一些字典以及對應值，幫我將它們結合，並將其轉換為一個obsidian顯示的表格，表格包含三個column(實際名, 中文名, 對應值)
另外，investment_models的部分也幫我轉換為表格併入，以下是investment_models部分例子：
investment_models = Investment_Models("simple_win_lose", 0.6, 20, -20, random_invest_rate=False)
實際名, 中文名, 對應值
investment_models, 利率模型, simple_win_lose
investment_models_params, 利率輸入值, (0.6, 20, -20, random_invest_rate=False)
```

```
程式：


我現在有一段python程式method，我想把他化為Obsidian的文檔建議格式如下：
## 利率模型名稱: 
中文名字:
簡短描述:
輸入:
輸出:

```

```
程式:


請幫我補充程式的注釋部分，格式請對比其他部分

```
