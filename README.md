# chobi — 초등학생도 아는 코드 설명

코드를 초등학생과 비개발자도 이해할 수 있게 쉬운 말과 일상 비유로 풀어 설명해 주는 Claude Code 플러그인이에요.

## 설치

Claude Code에서 아래 두 줄을 차례로 입력하세요.

```
/plugin marketplace add aijinikim/chobi-skill
/plugin install chobi@chobi-marketplace
```

## 사용법

```
/chobi:chobi app.py
/chobi:chobi for i in range(3): print(i)
```

파일 경로를 주거나 코드를 직접 붙여 넣으면 돼요.
플러그인 스킬이라서 명령어 앞에 플러그인 이름(`chobi:`)이 붙어요.

## 설명 형식

1. 🎯 **한 줄 요약** — 이 코드가 하는 일
2. 🧸 **비유로 보기** — 일상 이야기로 비유
3. 👣 **한 걸음씩** — 순서대로 쉬운 설명
4. 📖 **새로 배운 단어** — 용어 = 쉬운 뜻
5. 💡 **한번 생각해 볼까요?** — 이해를 확인하는 질문

## 업데이트

```
/plugin marketplace update chobi-marketplace
```
