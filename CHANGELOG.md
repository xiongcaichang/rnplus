# CHANGELOG

## 0.30.10

- 新增 API `resetTo`
- 修改 `open`、`goto`：通过配置 `replace` 属性为 `true` 可以替换当前页

## 0.30.9

新增 Navigator 动画样式 `FloatFromBottomNoGestures`

## 0.30.8

修正 Navigator 动画样式 `None` 在 iPhone 6s Plus 等机型渲染白屏的 bug

## 0.30.7

新增 Navigator 动画样式 `None`

## 0.30.5

- `rnx_internal_onHide` 和 `rnx_internal_onHide` 参数修正

## 0.30.4

- 修正首页自动触发一次 `deactived` 的 bug
- 修正 `close` 页面时会触发当前页 `actived` 和前一页面 `deactived` 的 bug

## 0.30.3

- 修正 backTo 无法携带参数的 bug

## 0.30.2

- 修复 PView 使用 Redux 后 `onBackPressed()` 失效的 bug