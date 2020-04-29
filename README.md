# Kureq

HTTP request library

easy to use!

## Quick start

install dependency

```
./path/to/kpm.exe
```

## example

Request

```
var request: \src\request@Request :: #\src\request@Request
do cui@print(request.get("http://www.yahoo.co.jp"))
```

Result

```
HTTP/1.1 301 Redirect
Date: Fri, 10 Jan 2020 07:17:26 GMT
Connection: keep-alive
Via: http/1.1 edge1527.img.bbt.yahoo.co.jp (ApacheTrafficServer [c s f ])
Server: ATS
Cache-Control: no-store
Location: https://www.yahoo.co.jp:443/
Content-Type: text/html
Content-Language: en
Content-Length: 1




```

## info

No verb other than GET supported yet.

Update: POST and HEAD are supported now but these are experimental.
