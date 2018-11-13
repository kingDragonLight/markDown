# markDown

我的第一个markdown学习项目

## 标题Demo

### 标题3

#### 标题4

##### 标题5

=======================标题结束========================

## 段落

赵客缦胡缨，吴钩霜雪明。银鞍照白马，飒沓如流星。
十步杀一人，千里不留行。  
事了拂衣去，深藏功与名。  
一句话后面空两格子并且换行即为一段结束，空一行也会。 空四个格子会高亮。

白马啸西风  

    射雕英雄传  TABLE

## 强调

**这是加粗的文字** __这是加粗的文字__

*这是倾斜的文字* _这是倾斜的文字_

***这是斜体加粗的文字***  ___这是斜体加粗的文字___

~~这是加删除线的文字~~

## 列表

### 无序列表

    无序列表用 - + *  
    任何一种都可以

- 列表内容
  - 二级列表
    - 三级列表1
    - 三级列表2

+ 列表内容
  + 二级列表
    + 三级列表1
    + 三级列表2

* 列表内容

### 有序列表
 会重新排序
1. 列表内容1
    1. 二级列表
4. 列表内容4
2. 列表内容2 
3. 列表内容3 


## 代码

`console.log("arr")`

```
function f1(start) {
    return function f2() {
        start++;
        console.log(start); // 999
    }
}
var first = f1(3);
first();// 4
first();// 5
```

## 表格

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

dog | bird | cat
----|------|----
foo | foo  | foo
bar | bar  | bar
baz | baz  | baz

## git一些命令

- git clone "https://github.com/username/filename"

- git pull 下拉代码

- git add filename.xx

- git commit -m "修改内容"
