# btc-events-2026-chart

SHIB·BTC 모바일 대시보드 + 상세 Plotly 차트 (GitHub Pages).

## Live
https://imsukmin.github.io/btc-events-2026-chart/

## Pages
- `index.html` — 대시보드 (시세 카드, 1년 정규화 차트, 상관 요약, 최근 이벤트)
- `chart.html` — BTC 매크로 이벤트 상세 차트
- `shib.html` — SHIB vs BTC 정규화·롤링 상관 상세 차트

## Data
- 가격: Binance Vision 공개 klines / 24h ticker (브라우저 CORS OK). 실패 시 빌드 시 베이크된 일봉 CSV 스냅샷.
- 이벤트: `events.json`, `events_shib.json` (창작 금지, 인용 소스만)
- 상관: `corr_summary.json`

## Note
알림(±5%/1h 등)은 별도 Grok Bot 루틴. 이 저장소는 웹 UI만.
