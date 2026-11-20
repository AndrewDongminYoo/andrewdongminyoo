<h1> 안녕하세요, Flutter 중심 모바일 개발자 유동민입니다. <img src="assets/greeting-cat.gif" width="35" alt=""> </h1>

**앱을 만들고, 그 앱을 만드는 도구를 만듭니다.**

2022년부터 iOS·Android 앱을 출시하고 운영해 왔습니다.
Flutter를 주력으로 React Native 앱도 개발하며, Swift·Kotlin으로 결제·OCR·센서 등 네이티브 기능을 연결합니다.
앱 개발 중 마주친 문제를 SDK와 개발 도구로 풀어 pub.dev·npm·VS Code Marketplace·Figma Community에 배포합니다.

🌐 **[포트폴리오](https://donminzzi.kr/)** · [기술 글](https://donminzzi.kr/posts) · [오픈소스 전체 목록](https://donminzzi.kr/oss)

## 📱 주요 제품·서비스

직접 기획·개발한 앱과 웹 서비스입니다.
개발 배경과 구현 과정은 [포트폴리오 프로젝트](https://donminzzi.kr/projects)에서 확인할 수 있습니다.

| 프로젝트                          | 설명                                                                                                                                                                 | 링크                                                                                                 |
| --------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| **WarmWake (온음)**               | 녹음한 음성으로 하루를 시작하는 Flutter 알람 앱. 알람 코어를 플러그인으로 분리하고 플랫폼별 지원 범위와 실행 준비 상태를 앱에서 확인하도록 설계했습니다.             | [웹사이트](https://warmwake.donminzzi.kr/)                                                           |
| **TODO Slayer (구 QuestKeeper)**  | 할 일을 퀘스트로 표현하는 iOS 투두 앱. SwiftUI·SwiftData로 구현하고, 계정 없이 할 일 데이터를 기기에 보관합니다.                                                     | [웹사이트](https://quest.donminzzi.kr/) · [GitHub](https://github.com/AndrewDongminYoo/quest-keeper) |
| **Prism Defense (프리즘 디펜스)** | 같은 타워를 합쳐 강화하는 타워 디펜스 게임. 게임 엔진 없이 Flutter `CustomPaint`로 렌더링하고, 시뮬레이션을 Flutter에 의존하지 않는 Dart 코드로 분리해 테스트합니다. | [웹사이트](https://prism-defense.donminzzi.kr/)                                                      |
| **catfood-feeder**                | 사료 라벨·제조사 문서에서 영양 성분을 추출하는 Next.js 앱. 모델이 제시한 수치를 근거 발췌문과 대조하고 서버에서 계산·판정을 다시 수행합니다.                         | [GitHub](https://github.com/AndrewDongminYoo/catfood-feeder)                                         |

## 🧰 주요 오픈소스·개발 도구

앱 개발의 반복 작업, 네이티브 연동, 에이전트 기반 유지보수를 돕는 도구를 만들고 공개합니다.

| 프로젝트                      | 설명                                                                                                                                                                  | 링크                                                                                                                                                                                                        |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **portone_flutter_v2**        | 기존 Flutter 패키지가 지원하지 않던 V2 결제 연동을 위해 개발·배포한 커뮤니티 패키지. 앱에 타입 안전한 결제 SDK 연동을 구현했습니다.                                   | [pub.dev](https://pub.dev/packages/portone_flutter_v2) · [GitHub](https://github.com/AndrewDongminYoo/portone_flutter)                                                                                      |
| **React Native Toolkits**     | 에셋 코드젠·New Architecture 점검·Figma 코드 생성을 돕는 도구 모음. `rn-agents-kit`은 에이전트가 프로젝트를 변경하기 전에 상태와 의존성을 점검하는 스킬을 제공합니다. | [웹사이트](https://rn-toolkits.donminzzi.kr/) · [GitHub · rn-agents-kit](https://github.com/AndrewDongminYoo/rn-agents-kit)                                                                                 |
| **Merry · vscode-merry**      | Dart·Flutter의 긴 스크립트를 단축 이름으로 실행하는 매니저와, 스크립트를 탐색·실행하는 VS Code 확장                                                                   | [pub.dev](https://pub.dev/packages/merry) · [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=DongminYu.vscode-merry-scripts) · [GitHub](https://github.com/AndrewDongminYoo/merry) |
| **react-native-step-counter** | iOS·Android의 걸음 수 데이터를 단일 API로 제공하는 React Native 모듈. 걸음 센서가 없는 Android 기기에서는 가속도계로 대체합니다.                                      | [npm](https://www.npmjs.com/package/react-native-step-counter-newarch) · [GitHub](https://github.com/AndrewDongminYoo/react-native-step-counter)                                                            |
| **commit-quill**              | 커밋 메시지와 의미 단위 변경 분리를 제안하는 VS Code 확장. 제안된 파일 경로를 `git status`와 대조해 스테이징 전 중복·누락을 검사합니다.                               | [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=DongminYu.commit-quill) · [GitHub](https://github.com/AndrewDongminYoo/commit-quill)                                              |

## 🛠 기술 스택

- **앱 개발** · Flutter · React Native (New Architecture) · SwiftUI
- **언어** · Dart · TypeScript · Swift · Kotlin · Objective-C · Python
- **플랫폼 연동** · Pigeon · TurboModule / Fabric codegen
- **백엔드·인프라** · Firebase · Supabase · AWS · GCP · GitHub Actions

## 📚 탐구와 공유

요리사로 일하며 고객과 직접 소통했던 경험을 제품을 만드는 데 이어가고 있습니다.
해외 원서로 기본기를 탐구하던 습관은 공식 문서와 기술 원서를 읽고, 개발 중 배운 내용을 오픈소스와 발표로 공유하는 일로 이어졌습니다.

- **2026.11 · Flutter Korea** · [안 되는 건 안 된다고 말하는 플러그인](https://flutter-korea.github.io/2026-flutter-korea/flutter/): WarmWake의 알람 코어를 분리하며 플랫폼의 지원 범위·준비 상태·적용 결과를 표현한 세 가지 계약을 소개했습니다.
- **2025.04 · Flutter Seoul** · [Trunk는 시작일 뿐: Flutter 개발 환경 자동화 실전기](https://event-us.kr/flutterseoul/event/101034)
- **2024.03 · Seoul iOS Meetup** · [Elevating Code Quality with Trunk Check](https://www.meetup.com/ko-kr/seoul-ios-meetup/events/299603900)

[![Linkedin Badge](assets/linked-in.svg)](https://www.linkedin.com/in/dongmin-yu-0394a5223/)
[![DevBlog Badge](assets/tistory-blog.svg)](https://cat-minzzi.tistory.com/)
[![KakaoTalk Badge](assets/kakao-talk.svg)](https://open.kakao.com/me/donminzzi)
[![Medium Badge](assets/medium.svg)](https://medium.com/@donminzzi)

[![Animated isometric island grown from public GitHub activity, with palms, sea animals and visitors in translucent water](https://raw.githubusercontent.com/AndrewDongminYoo/github-island/output/island.svg)](https://github.com/AndrewDongminYoo/github-island)
