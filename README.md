# Version Compare 工具

版本对比工具

## 安装

```bash
apmjs install --save @searchfe/user-agent
```

## 例子

```javascript
var compare = require('@searchfe/version-compare');

compare(1, 2); // -1
compare([1,2 ], [1, 3]); // -1
compare('1.2.3', '1.4.1'); // 1
compare('1.1.1', '1.1.1'); // 0
compare('1.2.3', [1, 2, 3]); // Wrong Params.

```
