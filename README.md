# datetimej
A hack of the datetime latex package to enable dates to be displayed without the year.

If you use

```
\usepackate[shortnoyear]{datetimej}
```

in your latex header then 

```
\formatdate{25}{8}{2015}

```

Will result in dates like "Fri. 25th Jul"