# canvas-demo-1
预览地址
以下解决微信页面下拉问题以及禁止缩放
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
