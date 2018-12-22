## 12-18
今天看了泛型 以及1.8的stream特性·
>泛型方法 <T>里中的T是类型参数，(T t)中的T是参数化类型
```
public <T> T method(T t){
}
```
## 12-22
list集合中有 fail-fast机制，出现集合遍历，改变元素，就会报ConcurrentModificationException
  为什么会报这个错
