# canvas-demo-1

以下代码解决微信页面下拉问题以及禁止缩放
```
 canvas.addEventListener(
            'touchmove',
            function (evt) {
                if (!evt._isScroller) {
                    evt.preventDefault()
                }
            },
            { passive: false }
        )
```
