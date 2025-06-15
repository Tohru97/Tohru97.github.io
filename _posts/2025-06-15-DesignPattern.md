---
title: "Tabless에서 적용한 디자인 패턴"
categories:
  - Documentation
---

## 1. 싱글톤 패턴 (Singleton Pattern)
- **AppInstance**
  - 앱의 라이프사이클 관리
  - 전역 매니저들의 생성 지점
  - 애플리케이션의 중앙 제어점 역할

## 2. 상태 패턴 (State Pattern)
- 객체의 상태에 따른 동작을 캡슐화
- 상태 전이 로직을 명확하게 분리
- 새로운 상태 추가가 용이한 구조

## 3. 옵저버 패턴 (Observer Pattern)
- 이벤트 기반 시스템 구현
- 느슨한 결합을 통한 유연성 확보
- UI 업데이트 및 이벤트 처리에 활용

## 4. 오브젝트 풀 패턴 (Object Pool Pattern)
- 메모리 할당 최적화
- 자주 생성/파괴되는 객체의 재사용
- 성능 향상을 위한 객체 캐싱

## 5. 퍼사드 패턴 (Facade Pattern)
- 복잡한 서브시스템을 단순화
- 인터페이스 통합
- 클라이언트 코드의 단순화  
  