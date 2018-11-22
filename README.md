# deepDisTouchMove.js
在ios浏览器中，修复元素在touchmove时，导致页面或者元素层被拉动的bug

### 调用方式
new disTouchMove({</br>
&nbsp;&nbsp;&nbsp;&nbsp;element: '.nomove',</br>
&nbsp;&nbsp;&nbsp;&nbsp;direction: 'vertical'</br>
})

### 参数说明
  element: 接受css的class和id,以及html元素标签, (body)默认</br>
  direction: （可选）横向：landscape 垂直：vertical(默认)</br>
