# fresh-setup
For fresh setup of a dev linux machine:

curl and pipe into bash.  
default mysql is root with blank password  
Should be idempotent.  
This is only tested on Ubuntu(v15) but theoretically will work on other debian systems.

``` 
curl https://raw.githubusercontent.com/nkiermaier/fresh-setup/master/raw/apt-installs.sh | bash
```


```
curl https://raw.githubusercontent.com/nkiermaier/fresh-setup/master/raw/dev-installs.sh | bash
```

