Mockito
=======

* doNothing() : only void methods 

```sh
    doNothing().
    doThrow(new RuntimeException())
    .when(mock).someVoidMethod();
```
