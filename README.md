## 功能说明

    ios Safari浏览器,从一个无法滚动的元素上touchmove
    到另一个可滚动的元素区域内,
    并且快速松开前者的touchmove同时快速触发后者的滚动,
    此时不能正常滚动的问题.

## 调用方式

    new disTouchMove({</br>
        element: '.nomove',
        direction: 'vertical'
    })

## 参数说明

    element: 接受css的class和id,以及html元素标签, (body)默认
    direction: （可选）横向：landscape 垂直：vertical(默认)
