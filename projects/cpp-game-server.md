---
layout: project
title: C++ Game Server
kicker: FEATURED PROJECT
subtitle: Multiplayer server architecture study and implementation
status: BUILDING
tags: [C++, TCP, Session, Room, JobQueue]
overview: "C++로 멀티플레이 게임 서버의 기본 구조를 직접 설계하고 구현하는 프로젝트입니다. Session, Player, Room의 책임을 분리하고 Room 단위 JobQueue를 이용해 상태 변경을 순차 처리하는 구조를 목표로 합니다."
features:
  - "Session / Player / Room 역할 분리"
  - "클라이언트 패킷을 서버 권한 기준으로 검증하는 흐름"
  - "Room JobQueue를 통한 Room 상태 변경 직렬화"
  - "TCP 연결부터 비동기 I/O, DB, 부하 테스트까지 단계적으로 확장"
flow: "Client → Session → Packet → Room JobQueue → Game Logic → Broadcast"
---
현재는 서버 구조와 객체 책임을 먼저 정리한 단계입니다. 구현이 진행될 때마다 **TCP 연결, 패킷 처리, 동시성 제어, 성능 측정** 결과를 이 페이지에 순서대로 추가합니다.
