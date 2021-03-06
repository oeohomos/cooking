# CHANGELOG

## [v0.5.0] 2016.6.12
- 用 ES6 重构

## [v0.4.9] 2016.6.10
- 新增 template 支持传入数组


## [v0.4.8] 2016.6.05
- 修复 不能省略 `.json` 后缀的问题
- 修复 watch 时 format 参数无效
- 修复 chunk 的 `hash` 应该用 `chunkhash`

## [v0.4.7] 2016.6.02
- 新增 权限错误会有提示，去掉了之前 `禁止使用 sudo` 的方式，支持使用 `sudo` 执行

## [v0.4.6] 2016.6.01 🎁
- 修复 CommonChunkPlugin 传 names 参数无效的问题
- 修复 未设置 devServer.publicPath 时应该采用 publicPath 选项的值
- 新增 build 时支持 `--output-public-path` 选项

## [v0.4.5] 2016.5.24
- 修复 extractCSS 的 hash 值
- 修复 插件安装目录移到用户目录下(`~/.cooking`)，避免每次升级都需要重新安装依赖

## [v0.4.4] 2016.5.21
- 修复 windows 下无法正常使用 [#30](https://github.com/ElemeFE/cooking/issues/30)
- 修复 锁定 webpack 版本为 0.13.0

## [v0.4.3] 2016.5.19
- 新增 开启 dev server 时默认支持将日志显示在页面上 `derServer: { log: true }`
- 更新 升级 webpack 到 0.13.x

## [v0.4.2] 2016.5.13
- 正式发布
