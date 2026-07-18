# Sauna Crowd Alert

サウナ混雑・ロウリュ通知

## Repository

Recommended repository name: `sauna-crowd-alert`

## Domain candidates

First candidate: `saunacrowd.jp`

Other candidates:

- `saunacrowd.jp`
- `saunaalert.jp`
- `loyly.jp`
- `totonoualert.jp`

## Concept

混雑、ロウリュ、イベント、回数券、深夜営業を通知し、施設送客、物販、宿泊へつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 施設送客
- 回数券
- グッズ
- 宿泊送客
- スポンサー

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
