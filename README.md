# naver-gw-kit
Naver 커버로스(kerberos) 인증 및 rlogin을 위한 Gateway 스크립트  
(Forked From https://gist.github.com/odd-poet/3115022)


## Installation
```
curl https://raw.githubusercontent.com/Jinkwon/naver-gw-kit/master/gwk.sh > gwk.sh | chmod 700 gwk.sh
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


### CHANGE LOG
- exec_kinit이 제대로 동작하지 않아 다이렉트로 실행할 수 있도록 수정
