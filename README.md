## cauin-post-alerts

중앙인 새 글 알림이

## 사용법

### 1. 텔레그램 봇 생성

BotFather로부터 텔레그램 봇을 생성하고 해당 봇의 토큰을 받아 온다.

### 2. 파일 생성

`info.txt` 파일을 `cauin-post-alerts.py` 파일과 동일한 경로에 생성한다.
그리고 텍스트 파일 각 줄마다 자신의 중앙인 아이디와 패스워드, 텔레그램 봇 토큰을 입력한다. 예시는 아래와 같다.

```
아이디
패스워드
텔레그램 봇 토큰
```

### 3. 실행

```shell
> python cauin-post-alerts.py
```
