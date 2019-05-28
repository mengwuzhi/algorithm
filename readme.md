#JavaScript算法课学习笔记
---
##1.环境搭建
- ES6
- [JEST](https://jestjs.io/zh-Hans/)
- [NPM](https://www.npmjs.com/)
- [GIT](https://git-scm.com/)

### 如何使用源码
1.拷贝源码：git clone 源码地址 leetcode

2.master分支：环境搭建原始内容 git checkout master

3.dev分支：所有源码 git checkout dev

### 关于设备
1.Windows
&emsp;&emsp;Node\Atom\Git bash
2.Mac
&emsp;&emsp;Node\Atom\Item2

学习git地址：https://git.imooc.com/coding-315/leetcode.git


### Atom插件与配置
1.es6-javascript
2.javascript-snippets
3.platform IDE terminal










##test.markdown流程图测试

```flow
st=>start: 开始
op=>operation: My operation
cond=>condition: Yes or No?
e=>end: 结束
st->op->cond
cond(yes)->e
cond(no)->op
```




 ```flow
    st=>start: 开始
    e=>end: 登录
    io1=>inputoutput: 输入用户名密码
    sub1=>subroutine: 数据库查询子类
    cond=>condition: 是否有此用户
    cond2=>condition: 密码是否正确
    op=>operation: 读入用户信息

    st->io1->sub1->cond
    cond(yes,right)->cond2
    cond(no)->io1(right)
    cond2(yes,right)->op->e
    cond2(no)->io1
    

 ```