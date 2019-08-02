---
sidebar: auto
sidebarDepth: 2
---
# es6新增的方法

- Array.prototype.copyWithin(target, start = 0, end = this.length)

- 数组实例的copyWithin方法，在当前数组内部，将指定位置的成员复制到其他位置（会覆盖原有成员），然后返回当前数组。也就是说，使用这个方法，会修改当前数组。

- target（必需）：从该位置开始替换数据。如果为负值，表示倒数。
  start（可选）：从该位置开始读取数据，默认为 0。如果为负值，表示倒数。
  end（可选）：到该位置前停止读取数据，默认等于数组长度。如果为负值，表示倒数。



- Array.from(类数组，ck)

- Array.of()用于将一组值，转为数组

- 扩展运算符

- fill填充  会改变原数组 填充一个数组

- flat(num)//拉平数组  默认值是1
