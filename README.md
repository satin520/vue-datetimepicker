移动端日期选择组件，css单位是rem,配合<a href="https://github.com/amfe/lib-flexible">flexible</a>使用更佳


<a href="https://yilianyoumeng.github.io/vue-timepicker/index.html">demo</a>

> 必须在移动端才有效果哦


# 安装及使用

```bash
npm install --install dependencies
```
```bash
npm run dev --serve with hot reload at localhost:8080
```
## 使用

    <data-picker v-model="pickerVal"></data-picker>
    

## prop:

|属性      |  描述                         |
| -------- | :----------:                       |
| maxDate  | 最大日期 默认：2025-12-31     |
| minDate  | 最小日期 默认：2016-01-1      |
| inpClass | 输入框样式class               |
| type     | 1.年月日选择器--'datepicker';2.时间选择器--'timePicker';3.年月日时分--'datetimePicker';4.只有年 --'onlyYM' |

作者qq:1329395802
