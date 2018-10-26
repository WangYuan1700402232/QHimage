# QHimage
起航实验室图像识别组

**文件夹task1-3**

[c1](https://github.com/QH17/QHimage/tree/master/task1-3/c1) |
[c2](https://github.com/QH17/QHimage/tree/master/task1-3/c2) |
[c3](https://github.com/QH17/QHimage/tree/master/task1-3/c3) 
---- | ----- | ------
图像的读取、写入以及色彩空间的转换 | 图像的滤波操作 | 图像的二值化以及最小外接圆处理

**task1-3中涉及到的函数**

c1              | c2                    | c3 
----            | -----                 | ------
cv2.imread()    | cv2.bilateralFilter() |  cv2.circle()
cv2.imshow()    | cv2.blur()            |  cv2.rectangle()
cv2.cvtColor()  | cv2.boxFilter()       |  cv2.inrange()
cv2.imwrite()   | cv2.MidianBlur()      |  cv2.find_Contours()
---             | cv2.Canny()           |  ---
---             | cv2.erode()           |  ---
