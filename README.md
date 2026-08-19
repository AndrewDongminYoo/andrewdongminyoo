<h1> 안녕하세요, 크로스 플랫폼 앱 개발자 유동민입니다. <img src="assets/greeting-cat.gif" width="35" alt=""> </h1>

**앱을 만들고, 그 앱을 만드는 도구를 만듭니다.**

2022년부터 Flutter · React Native로 iOS/Android 앱을 0→1로 출시해 온 크로스플랫폼 엔지니어 — pub.dev · npm · VS Code Marketplace · Figma Community에 SDK와 개발 도구를 배포합니다.

[![Linkedin Badge](assets/linked-in.svg)](https://www.linkedin.com/in/dongmin-yu-0394a5223/)
[![DevBlog Badge](assets/tistory-blog.svg)](https://cat-minzzi.tistory.com/)
[![KakaoTalk Badge](assets/kakao-talk.svg)](https://open.kakao.com/me/donminzzi)
[![Medium Badge](assets/medium.svg)](https://medium.com/@donminzzi)

🌐 **[donminzzi.kr](https://donminzzi.kr/)** — 포트폴리오 · [기술 글](https://donminzzi.kr/posts) · [오픈소스 전체 목록](https://donminzzi.kr/oss)

## 🛠 Tech Stack

- **Mobile** · Flutter · React Native (New Architecture) · SwiftUI · TypeScript · Python
- **Native** · Swift · Objective-C · Kotlin · Pigeon · TurboModule / Fabric codegen
- **Backend & Infra** · Firebase · Supabase · AWS · GCP · GitHub Actions

## ✨ 핵심 역량

- 🚀 **상용 앱 출시·운영 및 클라우드 인프라:** Flutter·React Native 상용 앱을 App Store·Google Play에 배포·운영하고, AWS·GCP/Firebase·Supabase로 백엔드와 CI/CD를 구축해 안정성과 운영 효율을 높였습니다. 직접 기획·개발해 운영 중인 앱으로는 Flutter로 만든 [WarmWake(온음)](https://warmwake.donminzzi.kr/)·[Prism Defense](https://prism-defense.donminzzi.kr/), 네이티브 iOS로 만든 [TODO Slayer](https://quest.donminzzi.kr/)가 있습니다.
- 🔧 **네이티브 모듈과 타입 안전한 플랫폼 계약:** Swift·Objective-C·Kotlin으로 네이티브 모듈을 직접 구현하고, Pigeon과 TurboModule codegen으로 Dart·TypeScript·Swift·Kotlin에 걸친 타입 안전한 플랫폼 계약을 설계합니다. `react-native-naver-login`(New Architecture TurboModule), `flutter_receipt_scanner`(federated 플러그인), 결제·OCR·센서 모듈을 pub.dev·npm에 배포했습니다.
- 🤖 **Agentic Coding & 개발 하니스 구축:** Claude Code 기반 서브에이전트 오케스트레이션·커스텀 스킬·지식 하니스를 설계해 개발 워크플로우를 자동화하고, 그 접근을 공개 프로젝트로 이어갑니다 — [rn-agents-kit](https://github.com/AndrewDongminYoo/rn-agents-kit) · 음성 에이전트 [JARVIS](https://github.com/AndrewDongminYoo/jarvis-assistant) · 타입세이프 에셋 코드젠 [rn-typed-assets](https://github.com/AndrewDongminYoo/rn-typed-assets) · Figma→RN [design-to-nativewind](https://github.com/AndrewDongminYoo/design-to-nativewind).
- 📚 **탐구와 공유:** 사용자 데이터 기반으로 UI를 개선하고, 외식업에서 고객과 직접 소통한 경험을 제품 기획의 핵심으로 삼습니다. 요리사 시절 해외 원서로 기본기를 탐구하던 습관을 이어, 공식 문서와 기술 원서를 깊이 파고들어 오픈소스 문서화와 개발자 밋업 발표로 공유합니다 — [Seoul iOS Meetup](https://www.meetup.com/ko-kr/seoul-ios-meetup/events/299603900) · [Flutter Seoul](https://event-us.kr/flutterseoul/event/101034).

## 📱 출시한 제품

| 제품                | 설명                                                                                                            | 링크                                                                                                 |
| ------------------- | --------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **WarmWake (온음)** | 시끄러운 알람 대신 어제의 내가 남긴 음성 메시지로 깨우는 Flutter 앱                                             | [웹사이트](https://warmwake.donminzzi.kr/)                                                           |
| **TODO Slayer**     | 마감을 놓치면 픽셀 히어로가 죽는 게임화 할 일 관리 — SwiftUI·SwiftData 네이티브 iOS                             | [웹사이트](https://quest.donminzzi.kr/) · [GitHub](https://github.com/AndrewDongminYoo/quest-keeper) |
| **Prism Defense**   | 그리고(Draw) 합치는(Merge) 랜덤 병합 타워 디펜스 — 게임 엔진·비트맵 에셋 없이 순수 Flutter `CustomPaint` 렌더링 | [웹사이트](https://prism-defense.donminzzi.kr/)                                                      |

## 🧰 오픈소스 & 개발자 도구

| 프로젝트                      | 설명                                                                                                                                | 링크                                                                                                                   |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **portone_flutter**           | 포트원 V2 결제 연동 Flutter 모듈 — 상용 앱 PG 3종 연동 경험을 패키지로 정리                                                         | [pub.dev](https://pub.dev/packages/portone_flutter_v2) · [GitHub](https://github.com/AndrewDongminYoo/portone_flutter) |
| **merry · vscode-merry**      | Dart/Flutter 스크립트 매니저와 VS Code 확장 — pub.dev와 VS Code Marketplace에 함께 배포                                             | [pub.dev](https://pub.dev/packages/merry) · [GitHub](https://github.com/AndrewDongminYoo/vscode-merry)                 |
| **react-native-step-counter** | 가장 널리 채택된 개인 OSS — iOS CMPedometer와 Android SensorManager를 TurboModule 하나로 통합하고, 센서 없는 기기는 가속도계로 폴백 | [GitHub](https://github.com/AndrewDongminYoo/react-native-step-counter)                                                |
| **rn-agents-kit**             | Audit-first agent skills for React Native — upgrade/migration/hygiene를 자동화하는 공개 하니스                                      | [GitHub](https://github.com/AndrewDongminYoo/rn-agents-kit)                                                            |

전체 오픈소스 목록은 [donminzzi.kr/oss](https://donminzzi.kr/oss)에 있습니다.

<img src="assets/divider.svg" style="display:block;margin:20px auto;" width="100%" height="8" alt=""/>

## 📊 코딩 활동 & 통계

**실시간 트래킹 코딩 타임** (2022.10.01 ~ 기록 중)

[![WakaTime 총 코딩 시간](https://wakatime.com/badge/user/9950e5aa-6874-4666-96a4-97dc4da0c644.svg?style=for-the-badge)](https://wakatime.com/@9950e5aa-6874-4666-96a4-97dc4da0c644)

**WakaTime 최근 7일 통계** — 갱신: [`AndrewDongminYoo/wakatime-svg`](https://github.com/AndrewDongminYoo/wakatime-svg)

<img src="https://raw.githubusercontent.com/AndrewDongminYoo/wakatime-svg/output/generated/languages.svg" width="49%" alt="WakaTime 언어별 통계" />
<img src="https://raw.githubusercontent.com/AndrewDongminYoo/wakatime-svg/output/generated/projects.svg" width="49%" alt="WakaTime 프로젝트별 통계" />

**GitHub 컨트리뷰션 통계** — 갱신: [`AndrewDongminYoo/github-stats-transparent`](https://github.com/AndrewDongminYoo/github-stats-transparent)

<img src="https://raw.githubusercontent.com/AndrewDongminYoo/github-stats-transparent/refs/heads/output/generated/overview.svg" width="49%" alt="GitHub 기여 개요" />
<img src="https://raw.githubusercontent.com/AndrewDongminYoo/github-stats-transparent/refs/heads/output/generated/languages.svg" width="49%" alt="GitHub 언어별 통계" />
