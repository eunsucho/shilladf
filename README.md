# Shilla DF · 전략 프로토타입

신라면세점 관련 전략 제안을 작동 가능한 HTML 데모로 모아둔 공간입니다.

🔗 **랜딩:** https://eunsucho.github.io/shilladf/

## 구조

```
index.html         # 랜딩 (6개 전략 카드)
strategy1.html     # 전략 1 프로토타입
strategy2.html     # 전략 2 프로토타입
...
strategy6.html     # 전략 6 프로토타입
```

## 새 전략 추가하는 법

1. `strategyN.html` 파일을 실제 프로토타입으로 덮어쓰기
2. `index.html` 의 해당 카드 `<h3>` / `<p>` 텍스트만 바꿔주기
3. `git add . && git commit -m "..." && git push`
4. GitHub Pages가 1~2분 안에 반영함
