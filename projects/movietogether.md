---
layout: project
title: MovieTogether
kicker: FEATURED PROJECT
subtitle: Shared playback room service
status: SERVER / STATE
tags: [Node.js, Express, Room, Sync, State]
overview: "각자 사용하는 OTT에서 같은 영화를 보면서 재생 상태를 맞출 수 있도록 만든 Room 기반 서비스입니다. 서버가 Room과 참가자 상태를 관리하고 Host의 재생 상태를 기준으로 다른 참가자가 같은 시점을 따라가도록 구성했습니다."
features:
  - "Room 생성과 참가자 입장 / 퇴장 관리"
  - "Host 권한 검증과 공용 재생 상태 제어"
  - "서버 timestamp를 이용한 재생 위치 계산"
  - "비활성 참가자 및 오래된 Room 정리"
  - "인원 / 재생시간 / Room 생명주기 제한"
flow: "Host Action → Server State Update → Room State → Participant Poll / Sync → Local Player"
---
실제 영상 파일을 서버가 스트리밍하는 서비스가 아니라, **Room의 공용 재생 상태를 서버에서 관리하고 참가자들이 그 상태를 기준으로 동기화**하는 구조입니다.
