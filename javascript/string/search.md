# search()

## 语法

```ts
search(regexp: RegExp | substr: string): number;
```

## 描述

 方法用于检索字符串中指定的子字符串，或检索与正则表达式相匹配的子字符串。

- 如果没有找到任何匹配的子串，则返回 -1。

## 示例

```js
let str="Visit Runoob!"; 
str.search("Runoob"); // 6
```