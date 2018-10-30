# css-pseudo-element-practice-2
偽元素操作練習，順便練練CSS物件旋轉動畫、模擬擠壓效果等等


參考、修改自https://www.oxxostudio.tw/articles/201502/css-bounce.html


方塊初始不轉，每運動25%轉動45度，因為是來回轉，所以在50%時角度要從90度開始扣回


在50%時方塊右下的角會觸地，所以做一個凹陷的效果，用border-bottom-right-radius


觸牆時也有擠壓效果，調整一下width和height就好


陰影：寫一個扁平的長方形，用border-radius調整成扁橢圓


初始>方塊觸地：調整橢圓的height
