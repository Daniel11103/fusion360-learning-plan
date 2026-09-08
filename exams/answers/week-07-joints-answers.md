# 第 7 周参考答案：装配与运动

## 学：概念题

1. Ground 固定组件；Rigid 不允许相对运动；Revolute 只允许绕一条轴旋转；Slider 只允许沿一条轴移动。
2. Joint Origin 的位置确定旋转中心或滑动起点，方向确定运动轴。
3. Motion Link 用比例驱动多个 Joint；Contact Set 用于检测或限制几何接触，两者不是同一概念。

## 练：评分要点

盒体固定；盖板使用 Revolute；轴线正确；限位为最大 `110°`；Drive Joint 开合时无明显穿透。

## 考：评分要点

滑块沿导轨移动 `60 mm` 并有限位；两个旋转组件分别建立 Revolute；Motion Link 比例 `1:2`；能说明哪个 Joint 被驱动、哪个跟随。

## 思：参考方向

可能原因包括 Joint 类型错误、Joint Origin 选错、轴线方向反了、组件初始位置错误、限位设置错误或几何间隙不足。应先检查 Joint 类型和原点，再检查方向、限位和碰撞。
