# 第 7 周·第 4 天：Motion Link 与接触

## 今日目标

了解多个 Joint 的联动关系，并认识 Contact Set 的基本用途和限制。

## 课程内容

1. 建立两个旋转组件，分别创建 Revolute Joint。
2. 使用 Motion Link 设置转动比例，例如 `1:2`。
3. 驱动一个 Joint，观察另一个 Joint 的跟随运动。
4. 了解 Contact Set 对防止穿透的作用。
5. 比较约束关系和接触检测的区别。

## 动手练习

制作两个简化齿轮或带轮，让一个转动时另一个按比例转动；如性能允许，再测试 Contact Set。

## 本节重点总结

- Motion Link 表达的是运动比例，不是几何啮合本身。
- Contact Set 计算成本较高，适合必要的接触关系。
- 先保证基础 Joint 正确，再添加联动和接触。

## 视频学习链接

- [YouTube：Fusion 360 Motion Link Contact Set](https://www.youtube.com/results?search_query=Fusion+360+Motion+Link+Contact+Set)
- [Bilibili：Fusion 360 运动链接与接触集](https://search.bilibili.com/all?keyword=Fusion%20360%20运动链接%20接触集)

## 完成检查

- [ ] 建立两个 Joint。
- [ ] 设置并验证 Motion Link 比例。
- [ ] 能说明 Contact Set 的适用场景。
