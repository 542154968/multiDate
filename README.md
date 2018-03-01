# multiDate

**项目中的场景图**
![项目场景图](https://github.com/542154968/multiDate/blob/master/images/eg.png)

```javascript
// 由于要设置考勤日 需要多选日期 于是自己开发了这个组件 主要还是符合项目中的场景 也很容易扩展 
// 初始化组件时可以设置日期 
// 比如我打开设置日期的弹窗的时候传入（ 一般通过AJAX获取后端传来的 ）日期 
// 就得到了对应日期范围的弹窗
// 通过暴露出的api 获得用户选择的日期 提交给后端
```

**demo**
> 为了演示和项目场景有稍许不一样

```javascript
// 配置参数
/**
* @description时间选择多选 详情参考行政事务考勤报表-考勤设置-编辑考勤日
* @param {String}  date： 2016-05-08 传入的时间默认是今天
* @param {String}  dom： 当前时间范围的最外层dom结构  如 1-31这些div格子的最外层盒子
* @param {String}  itemDom：1-31号div的父级dom
* @param {String}  item：每个号的div结构  
* @param {Array}   defaultDate：这个月的多少多少号是默认选择的
* @param {Function} clickback： 点击div的回调
* @function setDate(date, defaultDate): date: 设置新日期 格式 2016-05-08， defaultDate： 数组 设置新的默认选择日期
* @function getDate() 获得当前选定的几号 然后自己拼上年和月  
* */


```
