# Change Log

### 0.2.5

- [+] 当 schema 为 js 对象时，支持`ui:disabled`、`ui:readonly`、`ui:hidden`和`ui:options`的值为函数表达式。用法为 `"ui:disabled": (value, rootValue, formData) => value === "a"`
- [+] 列表组件添加了 `hideDelete` 属性（`ui:options`），详见文档的 UISchema 部分

### 0.2.4

- [!] 文档 Demo 展示效果优化
- [+] Fusion 体系支持按需加载

### 0.2.3

- [+] 新增 Proptypes to Json Schema 工具
- [!] 解决 Fusion 下时间选择系列问题

### 0.2.1

- [!] 官方 demo 提速，文档梳理到稍微好用

### 0.2.0

- [!] 优化打包构建脚本，减少包大小
- [+] 放出对应的 [Demo 效果](https://alibaba.github.io/form-render/docs/demo/index.html)
- [!] 使用时候不需要再引入 antd 或者 fusion 的 css

### 0.1.5

- [+] array type 支持使用 `uniqueItems` 字段校验列表中元素是否重复。`uniqueItems` 接受 boolean 和 string 类的值
- [!] fix 了 array 类样式展示空白过多的问题

### 0.1.4

- [!] 建议用户使用 default 赋予列表 item 值，不再强制显示一个元素

### 0.1.3

- [+] 列表会默认显示一个 item
- [+] hidden 表达式现在支持取顶层 `formData` 的值，例如`'ui:hidden':'formData.a.b.c == "xxx"'`
- [!] 修复了列表最后一个 item 无法删除

### 0.1.0

- [+] 对外开源的第一个版本
