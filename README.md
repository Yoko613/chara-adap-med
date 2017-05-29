# 自适应长度水平居中

### `文字长度不固定，在界面水平居中展示`
```
<div class="out">
  <div class="in">XXXX</div>
</div>
```
    * css样式写法
```
.out {
    position: relative;
    float: left;
    left: 50%;
}
.in {
    position: relative;
    left: -50%;
}   
```
** 简单几行代码就实现了，自适应居中方式，pc，手机端都适配！
    

