## Demo Dyndoc Library

To illustrate `dpm link`

```{bash}
dpm install rcqls/dyndoc-library-demo
dpm link rcqls/dyndoc-library-demo/LibOne LibTest
#or
dpm link rcqls/dyndoc-library-demo/LibTwo LibTest
```
Now depending of using first or second link, the following dyndoc file with content:

```{bash}
[#require]LibTest/tools
[#main]
{#hello]Moi[#}
```

would answer: `hello Moi` or `bonjour Moi`.
