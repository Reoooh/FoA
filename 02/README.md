# 2nd [divide & conquer]

**二分查找 递归**

`binsearch_recursion`

> 将取值会在递归调用中变化的变量设为递归例程的参数：
>
> > 降低递归例程表述的混乱程度
> >
> > 减少消耗的计算资源
>
> 尾递归：
>
> >在递归调用后不执行操作，可以轻松生成迭代版本。去掉递归调用生成的栈后，能够节省大量内存，且迭代执行速度快于递归，无需维护栈。

**合并排序**

`mergesort`

> *merge*两路合并表示将两个有序数组合并为一个有序数组

`mergesort_inplace`

> 原地排序使用的空间仅限于输入内容的存储空间，调用*merge*时不会创建数组的第二副本

**快速排序**

`quicksort`

**Strassen矩阵乘法**

`strassen`

`strassen_rebuild`

> require 'matrix'

