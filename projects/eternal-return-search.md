---
layout: project
title: Eternal Return Search
kicker: SELECTED WORK
subtitle: Match history and player statistics viewer
status: DATA / SERVICE
tags: [Node.js, Express, SQLite, API, Stats]
overview: "이터널 리턴 닉네임을 검색해 최근 전적과 통계를 확인하는 서비스입니다. 게임 API 데이터를 화면에 맞는 형태로 가공하고, 계정 / 저장 기능을 위한 로컬 데이터 계층을 함께 구성했습니다."
features:
  - "일반 / 랭크 / 코발트 전적 조회"
  - "캐릭터 아이콘과 경기 기록 시각화"
  - "유저 통계와 플레이 기록 요약"
  - "Express 기반 API 서버"
  - "SQLite를 이용한 계정 / 개인화 데이터 저장 구조"
flow: "Nickname → Game API → Backend Normalize → Stats Model → Match History UI"
---
외부 게임 API를 그대로 보여주기보다 **필요한 데이터만 가공해 서비스 형태로 제공하는 과정**을 보여주는 프로젝트입니다.
