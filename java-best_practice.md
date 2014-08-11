Java-best practice
==================

* String concatenation

```sh
String[] s = new String[] {"a", "b", "c"};
String joined = StringUtils.join(s, null);
```

The above is faster than using StringBuilder eg.

```sh
new StringBuilder("a").append("b").append("c").toString()
```


