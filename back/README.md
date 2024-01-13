# 무한쉼터 - 백엔드

## 실행 방법
1. 먼저 `cd back` 명령어를 통해 back 디렉토리로 이동합니다.
2. `.env` 파일로 환경변수 파일을 설정합니다.
    ```
    SERVER_PORT = 5001
    MONGO_URL = "mongodb+srv://*****@cluster0.*****.mongodb.net"
    JWT_SECRET_KEY = *****
    JWT_ALG = "HS256"
    JWT_EXP = "30m"
    KAKAO_RESTAPIKEY = *****
    ```
3. back 디렉토리에서 각자 개발 환경에 맞춰 아래 명령어를 순서대로 입력합니다.
    - npm
        ```
        npm i
        npm run start

        ```
    - yarn
        ```
        yarn
        yarn start
        ```
    - `--watch`모드로 실행할 시 `yarn dev` 또는 `npm dev` 명령어를 입력해줍니다.
4. 터미널에 `정상적으로 연결되었습니다` 문구가 표시되면 http://localhost:5001 로 접속합니다.