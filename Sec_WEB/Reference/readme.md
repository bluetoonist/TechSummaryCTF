# Reference 
<h2>TOC</h2>
&nbsp;&nbsp;&nbsp;&nbsp; 1. X-Forwarded-For<br>

## X-forwareded-for
```
현재까지 거쳐온 서버의 IP에 대한 정보를 가지고 있음, IP 필터링 우회를 위해 사용할 수도 있는 것으로 보임

Example >>
curl -H "X-Forwarded-For:127.0.0.1" -XGET http://DNS
```