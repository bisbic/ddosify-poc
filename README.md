# Sample ddosify uses

## Sample load test
```
ddosify -t https://sample.site
```
## Test 1000 GET requests in 20 seconds with a timeout of 10 seconds
```
ddosify -t https://sample.site -n 1000 -d 20 -m GET -T 10 
```
## More information on: https://hub.docker.com/r/ddosify/ddosify
