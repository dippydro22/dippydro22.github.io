---
layout: project
title: Sora
kicker: SELECTED WORK
subtitle: Community Discord bot
status: BOT / SERVICE
tags: [Discord.js, Commands, Events, Database]
overview: "게임 커뮤니티에서 반복되는 기능을 자동화하기 위해 만든 Discord 봇입니다. 명령어, 이벤트, 데이터베이스 유틸리티를 분리해 여러 기능을 하나의 봇에서 운영할 수 있도록 구성했습니다."
features:
  - "기능별 Command 모듈 분리"
  - "Discord Event 처리 구조"
  - "룰렛 / 파티 / 게임 관련 커뮤니티 기능"
  - "데이터 저장 유틸리티와 공통 로직 분리"
  - "명령어 배포 스크립트와 운영 구조"
flow: "Discord Event / Command → Handler → Feature Module → Database / Utility → Response"
---
기능 개수보다 **명령어와 이벤트를 분리해 커뮤니티 기능을 확장할 수 있게 만든 구조**를 중심으로 정리합니다.
