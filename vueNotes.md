## css圆角渐变边框
### 利用padding实现边框效果
```
padding: 9px;
border-radius: 20px;
background-image: linear-gradient(#ffffff, #ffffff), linear-gradient(#66d59f, #2ca3a1);
background-clip: content-box, padding-box;
```
## css设置默认字体（处理iOS数字无字体情况）
```
font-family: FZLTHJW--GB1-0, sans-serif;
```
## route切换后，重置页面滚动位置：
```
scrollBehavior(to, from, savedPosition) {
  if (savedPosition) {
    return savedPosition
  } else {
    return { x: 0, y: 0 }
  }
}
```
