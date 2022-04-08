# HashMap

1. 如果一个类的 equals 方法重写了，那么 hashCode 方法必须重写。并且如果 equals 方法返回为 true，hashCode 返回的值必须一样。
   equals 方法返回 true 表示两个对象相同，在同一个单向链表上比较。 
   那么对于同一个单向链表上的节点来说，他们的哈希值都是相同的。所以 hashCode 方法的返回值也应该相同。

2. 放在 HashMap 集合 key 部分的，以及放在 HashSet 集合中的元素，需要同时写 hashCode 方法和 equals 方法


