排序
====

指明对结果的排序方法。

- 数组中元素的参数：

  property(字符串类型)：排序的属性名

  order(字符串类型)：排序方法，"ASC"表示升序，"DESC"表示降序，默认"ASC".

.. note:: 

  属性的值必须是可排序的。

  如果属性的值只是单个字符串，则只需指定参数property，自动按升序排序，例如{"property":"title"}。

  结果对属性的出现次序进行排序。

