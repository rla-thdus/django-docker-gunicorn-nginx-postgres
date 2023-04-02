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
SECRET_KEY=
```

### 2. SECRET_KEY를 생성 한다.
50 글자로 이뤄진 SECRET KEY를 만들어서 넣어주면 된다. 그냥 임의로 50글자 넣어도 되지만 [여기서](https://djecrety.ir/) 시크릿 키를 만들어 사용할 수 있다. 

### 3. docker-compose를 구동시키면 된다.
```bash
docker-compose up -d
```

## 실행 됐다면 아래 주소에 접속 했을 때 해당 화면을 볼 수 있다.
```text
http://localhost
```
![](screen.png)
