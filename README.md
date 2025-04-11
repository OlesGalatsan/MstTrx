# MstTrx
Testing TRX output from `Microsoft.Testing.Platform`.

If I run this from the command line:

```
dotnet test -- --filter-not-namespace 'MstTrx2*'
```

... then it reports a failure and creates a TRX file with no tests in it.
