## Zwitterion example for quick/easy TypeScript transpilation


- https://github.com/lastmjs/zwitterion
- https://hackernoon.com/zwitterion-transpilation-made-simple-a9baa407b006

## Gotchas: 


on build you might see some errors: 

```
Download and save all .html files from Zwitterion
/bin/bash: line 13: shopt: globstar: invalid shell option name
Download and save all .ts files from Zwitterion
/bin/bash: line 20: shopt: globstar: invalid shell option name
```

solution: on OSX you will have to upgrade to bash 4: http://clubmate.fi/upgrade-to-bash-4-in-mac-os-x/


I also had to change the hardcoded `/bin/bash` reference in zwitterion to my local bash binary. 