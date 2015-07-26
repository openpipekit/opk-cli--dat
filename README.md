# OPK CLI: Dat 

A CLI to push data from a pipe to a dat dataset. Contains support for streams.

Example:
```
> ./opk-cli--dat/install
> echo "42" | opk-cli--dat/push 
> echo "44" | opk-cli--dat/push 
> dat export -d data
{"d":"42"}
{"d":"44"}
```

Credits:
R.J. Steinert

License: GNU AFFERO GENERAL PUBLIC LICENSE 
