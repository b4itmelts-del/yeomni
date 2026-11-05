# 녹기전에 염리점 — 같이 보기

- `public/index.html` : 가게 (게임 화면)
- `public/auto2/index.html` : 염리는 자동영업중,, 2 (자동영업 타이쿤, 최종본) — 접속: `https://<배포주소>/auto2/`
- `index.js`, `room.js` : 같이 보기 방 서버 (Cloudflare Worker + Durable Object)

접속: `https://<배포주소>/?room=방이름`  (같은 방이름을 쓴 사람끼리 같은 가게에 모입니다)
