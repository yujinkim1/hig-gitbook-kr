---
description: iOS를 위한 디자인을 알아봅니다.
---

# Designing for iOS

## 개요

사람들은 iPhone을 통해 어디서나 연결 상태를 유지하고, 게임을 하고, 미디어를 보고, 작업을 수행하고, 개인 데이터를 추적합니다.

iOS전용 앱이나 게임을 디자인하기 시작할 때, iOS 경험을 구별하는 다음과 같은 기본 장치 특성 및 패턴을 이해하는 것부터 시작하세요. 이러한 특성과 패턴을 사용하여 디자인 결정을 알려면 iPhone 사용자가 높이 평가하는 앱이나 게임을 제공하는 데 도움이 될 수 있습니다.

* **Display.** iPhone은 중간 크기의 고해상도 디스플레이를 가지 있습니다.
* **Ergonomics.** 사람들은 일반적으로 아이폰과 상호작용할 때 한 손이나 양손으로 아이폰을 들고, 필요에 따라서 가로와 세로 방향으로 바꿉니다. 기기와 상호작용하는 동안 시야의 거리는 1피트 또는 2피트에 정도에 지나지 않습니다.
* **Input.** 멀티 터치 [제스처](https://developer.apple.com/design/human-interface-guidelines/inputs/touchscreen-gestures), [화면 키보드](https://developer.apple.com/design/human-interface-guidelines/components/selection-and-input/onscreen-keyboards) 및 [음성](https://developer.apple.com/design/human-interface-guidelines/technologies/siri/introduction) 제어를 통해 사람들은 이동 중에도 작업을 수행하고 의미있는 작업을 수행 할 수 있습니다. 또한 사람들은 종종 앱이 장치의 [가속도계 및 자이로스코프](https://developer.apple.com/design/human-interface-guidelines/inputs/gyro-and-accelerometer)의 [위치](https://developer.apple.com/design/human-interface-guidelines/patterns/accessing-private-data)와 입력을 사용하기를 원하며 [공간 상호 작용](https://developer.apple.com/design/human-interface-guidelines/inputs/spatial-interactions)에 참여하기를 원할 수도 있습니다.
* **App interaction.** 때때로 사람들은 이벤트 또는 소셜 미디어 업데이트를 확인하, 데이터를 추적하거나, 메시지를 보내는 데 1분에서 2분 정도 소비합니다. 다른 때에는 한 시간 이상 웹을 탐색하거나, 게임을 하거나, 미디어를 즐기는 데 한 시간 이상을 소비합니. 사람들은 일반적으로 여러 앱을 동시에 열어 놓고 있으며, 그 사이에서 자주 앱을 전환하는 것을 좋아합니다.
* **System features.** iOS는 사람들이 친숙하고 일관된 방식으로 시스템 및 앱과 상호 작용할 수 있도록 도와주는 몇 가지 기능을 제공합니다.
  * [Widgets](https://developer.apple.com/design/human-interface-guidelines/components/system-experiences/widgets)
  * [Home Screen quick actions](https://developer.apple.com/design/human-interface-guidelines/components/system-experiences/home-screen-quick-actions)
  * [Spotlight](https://developer.apple.com/design/human-interface-guidelines/patterns/searching)
  * [Shortcuts](https://developer.apple.com/design/human-interface-guidelines/technologies/siri/shortcuts-and-suggestions)
  * [Activity views](https://developer.apple.com/design/human-interface-guidelines/components/menus-and-actions/activity-views)

## 모범 사례

최고의 아이폰 경험은 사람들이 가장 중요하게 생각하는 플랫폼과 기능을 통합하고 있습니다. iOS 디자인의 편안함을 느낄 수 있도록 다음과 같은 특징과 기능을 통합하는 방법을 우선시 하세요.

* 최소한의 상호 작용으로 보조 세부 정보와 작업을 검색할 수 있도록 함과 동시에 화면 컨트롤의 수를 제한하여 사람들이 기본 작업 및 콘텐츠에 집중할 수 있도록 지원하세요.
* 장치 방향, 다크 모드 및 동적 유형과 같은 외형 변에 원활하게 적응하여 사람들이 자신에게 가장 적합한 구성을 선택할 수 있도록 하세요.
* 사람들이 일반적으로 장치를 들고 있는 방식을 지원하는 상호 작용을 사용하도록 설정합니다. 예를 들어, 컨트롤이 디스플레이의 중간 또는 하단 영역에 있을 때 사용자가 쉽게 컨트롤을 찾을 수 있으므로 사용자가 살짝 밀어 목록 행에서 뒤로 이동하거나 작업을 시작하게끔 하는 것이 특히 중요합니다.
* 사용자의 허가를 받아 플랫폼 기능을 통해 제공하는 정보를 사용자에게 데이터를 입력하도록 요청하지 않고도 경험을 향상시킬 수 있게 통합하세요. 사용 예로 결제를 진행하거나, 생체 인식 인증을 통해 보안을 제공하거나, 장치의 위치를 사용하는 기능을 제공할 수 있습니다.

## 리소스&#x20;

**관련 자료**

[Apple Design Resources](https://developer.apple.com/design/resources/#ios-apps)

**개발자 문서**&#x20;

[Planning your iOS app](https://developer.apple.com/ios/planning/)

**비디오**

[What's new in UIKit](https://developer.apple.com/videos/play/wwdc2021/10059/)

[What's new in iOS Design](https://developer.apple.com/videos/play/wwdc2019/808/)
