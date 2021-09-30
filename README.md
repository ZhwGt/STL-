# STL 算法中常用操作整理

### 关联容器
关联容器：
```cpp
set, map, unordered_map, unordered_set, multiset, multimap, unordered_multimap, unordered_multiset. 
```
对于它们常用操作：
```cpp
[]:容器中若无关键字，自动插入关键字，对应的值是默认类型。
count：统计关键字的数量
find：查找是否有关键字
insert：插入pair
erase：删除关键字和值
upper_bound：最后一个关键字的迭代器
lower_bound：第一个关键字的迭代器
equal_range：first是lower_bound, second是upper_bound
```
