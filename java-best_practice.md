Java-best practice
==================

* String concatenation

```sh
String[] s = new String[] {"a", "b", "c"};
String joined = StringUtils.join(s, null);

or

new StringBuilder("a").append("b").append("c").toString()
```

The above is faster than using String eg.

```sh
"a"+"b"+"c"
```


