# Agent Card — LFAI WORLD 공장 (장비 이력 카드 · 러너가 매 회전 다시 씀)

| 항목 | 값 |
|---|---|
| Name | lfai-world · t1 12공정 공장 |
| Version | 엔진 0.9.1 · 레시피 recipe.json |
| Owner | 계정 주인 |
| Autonomy | A2 — 사람 승인(관문 04) 후 공개 |
| Models | 낭독 edge-tts ko-KR-InJoonNeural · 영상 HyperFrames · 카드 Chrome 헤드리스 (AI 열쇠 없음) |
| Tools | 플러그: [{"name":"owner-voice","station":"voice","opts":{"model":"parksy_rvc","pitch":0},"version":2,"route":"switch","switch":"lfai-world/admin-switch"},{"name":"law-gate","station":"gate-check","opts":{"strict":false,"rules_version":1},"route":"switch","switch":"lfai-world/admin-switch"},{"name":"music-bgm","station":"bgm","opts":{"style":"warm","target_lufs":-20.0},"route":"switch","switch":"lfai-world/admin-switch"}] |
| Data access | 서랍 12개 + 본사(비공개) · 공개는 05 웹 책 · 프로필 |
| Known failure modes | 불량 상위: 없음 |
| Eval summary | 자동 합격 4/4 · 사람 OK 0/0 판정 |
| Last evaluated | 2026-10-31 12:30 KST (run 41164512343) |
| Budget | 이번 달 334/2000분 (16.7%) · 월말 예상 16.7% · 기기 0.0분(0원) |
| Rollback | t1-12-mirror 릴리스 mirror-20261031-122944 (최근 5개 보관) |
| Incident contact | 계정 주인 · 텔레그램 보고 |
