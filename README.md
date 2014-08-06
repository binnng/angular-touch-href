angular-touch-href
==================

angular应用中，移动设备上，页面跳转采用touch事件触发，响应更快。

原理是扩充了angular自带的`ngHref`指令。

使用：

```javascript
App = angular.module "myAngularApp", [
  "ngTouchHref"
]
```
