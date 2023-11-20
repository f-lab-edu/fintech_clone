# 핀테크 앱 구축

## 프로젝트 목표
- 카카오 페이머니와 같은 핀테크 앱 서비스를 구현하는 것이 목표입니다.

---
## 기술 스택

---
## 프로젝트 아키텍쳐

---
## Use Case

### USER
- 회원 가입
- ID 중복 확인
- 로그인
- 탈퇴
- 계정 상세
- 송금

---
## API

본 API 문서에는 다음과 같은 항목을 기록한다.

- ID: 여러 API 항목들을 구별하는 ID
- URL: 요청 경로 
- Method : request 방식
- Description: 간단한 설명
- Request Payload: 클라이언트가 요청 시 보내는 데이터
- Response Data: 서버가 응답으로 보내는 데이터


# Type Define Sheet
|Name|Description|Item|
|----|-----------|----|
|Example1|Example2|Example3|


# User

1. 로그인 

|ID|URL|Method|Description|Request Payload|Response Data|
|----|-----------|----|---|---|---|
|login|---|---|유저의 아이디와 비밀번호를 확인하는 로그인 페이지로 이동한다.|---|---|

2. 메인

|ID|URL|Method|Description|Request Payload|Response Data|
|----|-----------|----|---|---|---|
|main|---|---|유저의 계좌 잔액과 조회, 송금(이체) 버튼이 있는 메인 페이지로 이동한다.|---|---|

3. 계좌상세

|ID|URL|Method|Description|Request Payload|Response Data|
|----|-----------|----|---|---|---|
|account|---|---|유저의 계좌 상세 페이지로 이동한다.|---|---|

4. 계좌거래내역조회

|ID|URL|Method|Description|Request Payload|Response Data|
|----|-----------|----|---|---|---|
|accountHistory|---|---|유저의 계좌 잔액과 송금(이체) 버튼이 있는 계좌 거래 내역 페이지로 이동한다|---|---|

5. 송금(이체)

|ID|URL|Method|Description|Request Payload|Response Data|
|----|-----------|----|---|---|---|
|remittance|---|---|송금(이체)할 대상 계좌 입력칸과 송금(이체) 금액을 기입하는 칸이 있는 페이지로 이동한다|---|---|

- https://velog.io/@seunghee-ryu/API-%EB%AC%B8%EC%84%9C

---
## ERD
![](https://velog.velcdn.com/images/seunghee-ryu/post/7a665046-b0ae-4798-850f-ae1c0063a82f/image.jpg)


---
