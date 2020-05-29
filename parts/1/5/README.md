Created the Dockerfile in the repository and used that, tagged it and did the following:
- docker run samip5/ubuntu-test sh -c 'echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://helsinki.fi;'


Output:
```bash
Input website:
Searching..
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   231  100   231    0     0   4358      0 --:--:-- --:--:-- --:--:--  4358
<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>301 Moved Permanently</title>
</head><body>
<h1>Moved Permanently</h1>
<p>The document has moved <a href="http://www.helsinki.fi/">here</a>.</p>
</body></html>
```
