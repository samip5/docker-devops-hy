Using it on aarch64 fails, even with the Dockerfile and other files extracted from default container's filesystem as node for some reason did not work on aarch64, just "aborted (segemention fault".

Commands:
- `docker run -it devopsdockeruh/exec_bash_exercise`
- `docker inspect <returned-container-id>`

```
# cat /var/lib/docker/overlay2/28196e8d4f41af0e0c0e9d3c93f0c4fe023784a0306ed9cb1fd04b8c2daa2895/diff/usr/app/logs.txt
Mon, 27 Apr 2020 06:49:11 GMT
Mon, 27 Apr 2020 06:49:14 GMT
Mon, 27 Apr 2020 06:49:17 GMT
Mon, 27 Apr 2020 06:49:20 GMT
Secret message is:
"Docker is easy"
Mon, 27 Apr 2020 06:49:26 GMT
Mon, 27 Apr 2020 06:49:29 GMT
Mon, 27 Apr 2020 06:49:32 GMT
Mon, 27 Apr 2020 06:49:35 GMT
Secret message is:
"Docker is easy"
Mon, 27 Apr 2020 06:49:41 GMT
```

