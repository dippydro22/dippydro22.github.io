---
layout: project
title: ERTI
kicker: SELECTED WORK
subtitle: Eternal Return analytics playground
status: DATA / API
tags: [Eternal Return, API, Cache, Analytics, Vercel]
overview: "이터널 리턴 전적 데이터를 여러 방식으로 분석해 보여주는 실험형 웹 프로젝트입니다. 플레이 스타일 분석, 궁합, 캐릭터 성향, 랭크 흐름, 플레이 농도 같은 여러 기능을 하나의 서비스로 묶었습니다."
features:
  - "닉네임 기반 전적 조회와 플레이 스타일 분석"
  - "최근 / 과거 전적을 활용한 유저 궁합 계산"
  - "전적 기반 캐릭터 성향 / 페르소나 매칭"
  - "랭크 점수 흐름을 시각적으로 해석하는 분석 화면"
  - "API 429 대응을 위한 요청 간격 제어와 재시도 / cooldown"
  - "결과 캐시와 동일 요청 in-flight 병합"
flow: "Nickname → API Gateway → Rate Limit / Cache → Match Data → Analysis Module → Result UI"
---
기능 수보다 중요한 포인트는 **외부 API 제한 안에서 요청을 안정적으로 처리하고, 여러 분석 화면이 같은 데이터 흐름을 재사용하도록 만든 것**입니다.
