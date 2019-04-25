# 必学十大经典排序算法

## 专业术语介绍

### 稳定排序
```
如果a原本在b的前面,且a==b,排序之后a仍然在b的前面,则为稳定排序
```

### 非稳定排序
```
如果a原本在b的前面,且a==b,排序之后a可能在b的前面,则为非稳定排序
```

### 原地排序
```
原地排序就是指在排序过程中不申请多余的存储空间,只利用原来存储待排数据的存储空间进行比较和交换的数据排序
```

### 非原地排序
```
需要利用额外的数据来辅助排序
```

## 时间复杂度
```
一个算法执行所消耗的时间
```

### 空间复杂度
```
运行完一个算法所需的内存大小
```


## 十大排序
### 选择排序
- 思想
```
首先,找到数组中最小的那个元素,其次,将它和数组的第一个元素交换位置(如果第一个元素就是最小元素那么他就和自己交换).
其次,在剩下的元素中找到最小的元素,将它与数组的第二个元素交换位置,如此往复,直到将整个数组排序
```


## 选择排序