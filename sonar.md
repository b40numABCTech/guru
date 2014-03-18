Sonar
=====

*Preserve Stack Trace

```sh
try
{
   ...
}
catch (Exception e)
{
     throw new FooException(e);
}
```
