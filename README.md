从postcss-jingoal代码库Fork而来，由Jingoal成都团队维护

## 用途
自动解决 
* 渐变 
* 透明
* css背景透明
* css3值前缀
* css3属性前缀
* inline-block 兼容
## 针对ie兼容解决方案
```
.dd .ie10{
    
}
// 转换后的代码
.ie10 .dd {
    
}
// 只要匹配到.ie7 .ie7.ie8  .ielte9 这种, 都会自动提升到前面  后面的额数字可以自定义

```