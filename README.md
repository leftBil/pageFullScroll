### 原生单页全屏滚动
---
#### 1. 引入 `jquery.js` 和 `jquery.mousewheel.js` 

#### 2. 调用mousewheel方法
```    
$(document).mousewheel(function(e,delta){
    //delta为1代表向上滚动，为-1代表向下滚动
    if (delta === 1) {
        console.log("向上滚动");
    }
    if (delta === -1) {
        console.log("向下滚动");
    }
})  
```