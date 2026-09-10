---
layout: project
title: Yachiyo
kicker: SELECTED WORK
subtitle: Character AI with memory and persona
status: AI / FULL STACK
tags: [React, Gemini, Firebase, Memory, Persona]
overview: "캐릭터 설정과 관계성을 유지하며 대화하도록 만든 AI 캐릭터 프로젝트입니다. 단순 프롬프트 호출이 아니라 Persona, 감정 상태, 장기 기억 후보, 에피소드 기억을 분리해 대화 맥락을 유지하는 구조를 실험했습니다."
features:
  - "캐릭터 Persona와 세계관 정보 분리"
  - "대화에서 기억 후보를 추출하고 중요도를 기준으로 저장"
  - "장기 기억 / 에피소드 기억 관리"
  - "관계도와 감정 상태를 대화 컨텍스트에 반영"
  - "API Key를 클라이언트에 노출하지 않는 서버 프록시"
  - "Firebase 기반 사용자 데이터 동기화"
flow: "User Message → Server Proxy → Persona / Memory Context → Gemini → Response → Memory Candidate"
---
AI 모델 자체보다 **캐릭터 상태와 기억을 애플리케이션 구조에서 어떻게 관리할지**를 실험한 프로젝트로 소개합니다.
