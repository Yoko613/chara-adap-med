# 自适应长度水平居中

### `文字长度不固定，在界面水平居中展示`

   * dome写法
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

# 自适应长度垂直水平居中

    * dome写法
```
<div class="warpper">
  我的长度不固定哟
</div>
```
    * css样式写法
```
.warpper {
    position: absolute;
    top: 50%;
    left: 50%;
    padding: 20px;
    color: #fff;
    background: red;
    transform: translate(-50%, -50%);
    -webkit-transform: translate(-50%,-50%);
    -moz-transform: translate(-50%, -50%);

}
```
