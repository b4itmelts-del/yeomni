# 녹기전에 염리점 — 같이 보기

- `public/index.html` : 가게 (게임 화면)
- `public/Meta_B4/index.html` : **가기전에,, Beta ver. 0.01** (최신 녹타이쿤) — 접속: `https://<배포주소>/Meta_B4/`
- `meta/` : 가기전에,, 단독 사이트 (Cloudflare Worker 이름 `meta`, 루트 디렉터리 `meta`) — 접속: `https://meta.b4itmelts.workers.dev`
- `index.js`, `room.js` : 같이 보기 방 서버 (Cloudflare Worker + Durable Object)

접속: `https://<배포주소>/?room=방이름`  (같은 방이름을 쓴 사람끼리 같은 가게에 모입니다)
