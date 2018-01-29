###  Array.fill()
> ES6为Array增加了fill()函数，使用制定的元素填充数组，其实就是用默认内容初始化数组。该函数有三个参数。
```javascript
	arr.fill(value, start, end)
```
参考链接： https://www.cnblogs.com/kongxianghai/p/7542056.html

### Set
>  ES6 提供了新的数据结构 Set。它类似于数组，但是成员的值都是唯一的，没有重复的值。

>   数组去重
```javascript
	const unique = (arr) => {
	     return Array.from(new Set(arr));
	}
```
