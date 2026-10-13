# 搜狗输入法去广告

针对 **搜狗输入法**（`com.sohu.inputmethod.sogou`）的 LSPosed / Xposed 广告拦截模块。

拦截广告页面、广告控件与广告请求域名，全部按运行期类名 / 域名判断，
不 hook 广告 SDK 内部实现，因此 SDK 换版本或动态加载插件都不会让模块失效。

- 应用 ID：`io.github.q307334735.SogouNoAd`
- 作用域：`com.sohu.inputmethod.sogou`
- 源码与问题反馈：https://github.com/q307334735/SogouNoAd

## 安装

1. 在 LSPosed 管理器里安装本模块（见 Releases）。
2. 启用模块，并在**作用域**里勾选「搜狗输入法」。
3. 强制停止搜狗输入法后重新打开。

## 说明

本仓库是 LSPosed 官方模块仓库的发布容器，仅承载 release。
源码与完整文档见 https://github.com/q307334735/SogouNoAd 。