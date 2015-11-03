# naver-gw-kit
Naver 커버로스(kerberos) 인증 및 rlogin을 위한 Gateway 스크립트  
(Forked From https://gist.github.com/odd-poet/3115022)


## Installation
주의 : gw 서버에서 github서버에 접근이 되지 않을 수 있음. 그때는 raw파일 복사 후 붙여넣기 실행
```
curl https://raw.githubusercontent.com/Jinkwon/naver-gw-kit/master/gwk.sh > gwk.sh | chmod 700 gwk.sh
```

### Usage

Known hosts 추가
```
touch .known_hosts >> server_id.ncl    SERVER_NAME
```

실행
보안상의 이슈로 kinit으로 커버로스 통과 필요
```
kinit
./gwk.sh
```


### CHANGE LOG
- exec_kinit이 제대로 동작하지 않아 다이렉트로 실행할 수 있도록 수정
