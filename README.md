# naver-gw-kit
Naver 커버로스(kerberos) 인증 및 rlogin을 위한 Gateway 스크립트  
(Forked From https://gist.github.com/odd-poet/3115022)


## Installation
```
curl 
chmod 700 gwk.sh
```

### Usage


Known hosts 추가
```
touch .known_hosts >> server_id.ncl    SERVER_NAME
```

실행
```
./gwh.sh
```
