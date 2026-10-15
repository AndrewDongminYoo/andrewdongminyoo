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
- 🤖 **Agentic Coding & 개발 하니스 구축:** Claude Code 기반 서브에이전트 오케스트레이션·커스텀 스킬·지식 하니스를 설계해 개발 워크플로우를 자동화하고, [React Native Toolkits](https://rn-toolkits.donminzzi.kr/)와 커밋 제안 도구 [commit-quill](https://github.com/AndrewDongminYoo/commit-quill) 같은 공개 프로젝트로 이어갑니다.
- 📚 **탐구와 공유:** 사용자 데이터 기반으로 UI를 개선하고, 외식업에서 고객과 직접 소통한 경험을 제품 기획의 핵심으로 삼습니다. 요리사 시절 해외 원서로 기본기를 탐구하던 습관을 이어, 공식 문서와 기술 원서를 깊이 파고들어 오픈소스 문서화와 개발자 밋업 발표로 공유합니다 — [Seoul iOS Meetup](https://www.meetup.com/ko-kr/seoul-ios-meetup/events/299603900) · [Flutter Seoul](https://event-us.kr/flutterseoul/event/101034).

## 📱 주요 제품·서비스

직접 기획·개발한 앱과 웹 서비스입니다. 개발 배경과 자세한 구현 과정은 [포트폴리오 프로젝트](https://donminzzi.kr/en/projects)에서 확인할 수 있습니다.

| 프로젝트                          | 설명                                                                                                                                         | 링크                                                                                                     |
| --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| **WarmWake (온음)**               | 어제의 내가 녹음한 음성 메시지로 하루를 시작하는 Flutter 알람 앱                                                                             | [웹사이트](https://warmwake.donminzzi.kr/)                                                               |
| **TODO Slayer (구 QuestKeeper)**  | 할 일을 퀘스트로, 마감을 던전 조우로 표현하는 SwiftUI·SwiftData 기반 iOS 픽셀 RPG 투두 앱. 놓친 퀘스트는 그날의 임시 무덤으로만 남습니다.    | [웹사이트](https://quest.donminzzi.kr/) · [GitHub](https://github.com/AndrewDongminYoo/quest-keeper)     |
| **Prism Defense (프리즘 디펜스)** | 그려서 타워를 소환하고 같은 타워를 합쳐 강화하는 랜덤 병합 타워 디펜스. 게임 엔진·비트맵 에셋 없이 Flutter `CustomPaint`로 렌더링합니다.     | [웹사이트](https://prism-defense.donminzzi.kr/)                                                          |
| **catfood-feeder**                | 사료 라벨·제조사 문서에서 영양 성분을 추출하는 Next.js 앱. 모델이 제시한 수치를 근거 발췌문과 대조하고 서버에서 계산·판정을 다시 수행합니다. | [웹사이트](https://catfood.donminzzi.kr/) · [GitHub](https://github.com/AndrewDongminYoo/catfood-feeder) |

## 🧰 주요 오픈소스·개발 도구

앱 개발의 반복 작업, 네이티브 연동, 에이전트 기반 유지보수를 돕는 도구를 만들고 공개합니다.

| 프로젝트                      | 설명                                                                                                                                                                                         | 링크                                                                                                                                                                                                        |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **React Native Toolkits**     | 에셋 코드젠(`rn-typed-assets`), New Architecture 감사(`rn-newarch-ready`), Figma→NativeWind 코드 생성(`design-to-nativewind`), 에이전트 유지보수 스킬(`rn-agents-kit`)을 묶은 개발 도구 모음 | [웹사이트](https://rn-toolkits.donminzzi.kr/) · [GitHub · rn-agents-kit](https://github.com/AndrewDongminYoo/rn-agents-kit)                                                                                 |
| **Merry · vscode-merry**      | Dart·Flutter의 긴 스크립트를 단축 이름으로 실행하는 매니저와, 스크립트를 탐색·실행하는 VS Code 확장                                                                                          | [pub.dev](https://pub.dev/packages/merry) · [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=DongminYu.vscode-merry-scripts) · [GitHub](https://github.com/AndrewDongminYoo/merry) |
| **portone_flutter_v2**        | PortOne V2 결제 흐름을 Flutter에서 사용할 수 있도록 정리한 패키지                                                                                                                            | [pub.dev](https://pub.dev/packages/portone_flutter_v2) · [GitHub](https://github.com/AndrewDongminYoo/portone_flutter)                                                                                      |
| **react-native-step-counter** | iOS `CMPedometer`와 Android `SensorManager`의 걸음 수 데이터를 통합하는 React Native 네이티브 모듈                                                                                           | [npm](https://www.npmjs.com/package/react-native-step-counter-newarch) · [GitHub](https://github.com/AndrewDongminYoo/react-native-step-counter)                                                            |
| **commit-quill**              | 커밋 메시지와 의미 단위 변경 분리를 제안하는 VS Code 확장. 제안된 파일 경로를 `git status`와 대조해 스테이징 전 중복·누락을 검사합니다.                                                      | [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=DongminYu.commit-quill) · [GitHub](https://github.com/AndrewDongminYoo/commit-quill)                                              |

전체 오픈소스 목록은 [donminzzi.kr/oss](https://donminzzi.kr/oss)에 있습니다.

<img src="assets/divider.svg" style="display:block;margin:20px auto;" width="100%" height="8" alt=""/>

## 📊 코딩 활동 & 통계

**실시간 트래킹 코딩 타임** (2022.10.01 ~ 기록 중)

[![WakaTime 총 코딩 시간](https://wakatime.com/badge/user/9950e5aa-6874-4666-96a4-97dc4da0c644.svg?style=for-the-badge)](https://wakatime.com/@9950e5aa-6874-4666-96a4-97dc4da0c644)

**GitHub 컨트리뷰션 통계** — 갱신: [`AndrewDongminYoo/github-stats-transparent`](https://github.com/AndrewDongminYoo/github-stats-transparent)

![GitHub 기여 개요](https://raw.githubusercontent.com/AndrewDongminYoo/github-stats-transparent/refs/heads/output/generated/overview.svg)
![GitHub 언어별 통계](https://raw.githubusercontent.com/AndrewDongminYoo/github-stats-transparent/refs/heads/output/generated/languages.svg)
