Mockito
=======

Only void methods can doNothing()!
Example of correct use of doNothing():
    doNothing().
    doThrow(new RuntimeException())
    .when(mock).someVoidMethod();
