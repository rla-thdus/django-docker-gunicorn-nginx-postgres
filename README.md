# 실행 방법
### 1. 환경 변수 파일을 만들어 값을 채워준다.
```bash
cp .env.example .env
```
ex) 아래와 같이 넣어주면 된다.
```text
POSTGRES_NAME=postgres
POSTGRES_USER=postgres
POSTGRES_PASSWORD=postgres
POSTGRES_HOST=db
POSTGRES_PORT=5432
```

### 2. docker-compose를 구동시키면 된다.
```bash
docker-compose up -d
```

## 실행 됐다면 아래 주소에 접속 했을 때 해당 화면을 볼 수 있다.
```text
http://localhost
```
![](screen.png)
