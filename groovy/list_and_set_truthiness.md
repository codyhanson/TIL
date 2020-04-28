4/28/2020
# Today I learned about truthyness of groovy set and list expressions.

```groovy
groovy:000> def a = new ArrayList<long>() ? 1 : 2;
===> 2
groovy:000> def a = new ArrayList<long>([1L]) ? 1 : 2;
===> 1

groovy:000> def a = new ArrayList<long>().toSet() ? 1 : 2;
===> 2
groovy:000> def a = new ArrayList<long>([1L]).toSet() ? 1 : 2;
===> 1
```
