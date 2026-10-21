# 맞춤법 붕어빵 가게

손님이 말한 문장에 알맞은 낱말이 적힌 붕어빵을 골라 파는 맞춤법 게임입니다. 하트 3개를 다 잃을 때까지 손님이 계속 오고, 갈수록 빨라집니다.

- 놀이 주소: https://dobbi52.github.io/bungeo/
- 저학년 / 고학년 두 단계
- 생각 오락실 통합 로그인으로 순위표(이번 주 / 전체)에 기록이 올라갑니다. 저학년·고학년 통합 순위이고, 고학년 모드는 점수 1.5배입니다.

## 문제 추가
`index.html`의 `QUESTIONS` 목록에 같은 형식으로 한 줄씩 넣으면 됩니다.
`{s:"문장(빈칸은 ___)", a:"바른 낱말", w:"틀린 낱말", tip:"풀이"}`

## 순위표 서버
`server/Code.gs` — 구글 스프레드시트의 Apps Script에 붙여 넣고 웹 앱으로 배포한 뒤, 주소를 `index.html`의 `RANK_API`에 넣습니다.

글꼴: 갈무리(Galmuri) — SIL Open Font License 1.1 (`FONT-LICENSE-Galmuri.txt`)
