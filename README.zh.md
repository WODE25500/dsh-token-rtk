# dsh-token-rtk

**Input redundancy pruning — drop repeated/redundant tokens before they reach the model.** — 一个 DeepSeek Harness (dsh) skill,四层省 Token 家族的第 rtk 层。

输入冗余剪枝——在送进模型前砍掉重复/冗余 token。剪掉啰嗦日志、重复告警、整份文件粘贴、信号周围的噪音,只为需要的信号付费。

> 家族:[dsh-token-skills](https://github.com/WODE25500/dsh-token-skills) 包含全部四层 — handoff、rtk、headroom、caveman。

## 安装

    dsh plugin --profile web add dsh-token-rtk

然后调用 skill: `dsh-token-rtk`.

## 上游

基于/引用 [https://mintlify.wiki/rtk-ai/rtk/faq](https://mintlify.wiki/rtk-ai/rtk/faq)。本仓库是 DSH 适配 — 一个薄 skill,不重造引擎。

## 许可

MIT

