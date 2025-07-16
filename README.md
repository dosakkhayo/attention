# Attention 플러그인

Obsidian에서 폴더 간 파일 이동을 자동화하고, 알림을 제공하는 플러그인입니다.

## 주요 기능

- **tacit 폴더 → attention 폴더 자동 이동**  
  지정한 tacit 폴더의 파일을 열면 attention 폴더로 자동 이동합니다.
- **attention → tacit 폴더 수동 이동(아카이브)**  
  명령어(`보관소 폴더로 이동하기`)로 attention 폴더의 파일을 tacit 폴더로 이동할 수 있습니다.
- **이동 시 알림 표시**  
  각 이동 시점에 맞는 알림을 표시할 수 있습니다(설정에서 켜고 끌 수 있음).
- **폴더 경로 및 알림 설정 지원**  
  플러그인 설정 탭에서 폴더 경로와 알림 표시 여부를 자유롭게 설정할 수 있습니다.

## 설치 방법

1. `manifest.json`, `main.js`, `styles.css`(선택)을 플러그인 폴더에 복사합니다.
2. Obsidian 설정 > 플러그인 > 커뮤니티 플러그인에서 활성화합니다.
3. 설정 탭에서 tacit/attention 폴더 경로를 지정하세요.

## 사용법

- **파일 자동 이동:**  
  tacit 폴더에 있는 파일을 열면 attention 폴더로 자동 이동됩니다.
- **아카이브(수동 이동):**  
  attention 폴더에 있는 파일에서 명령어 팔레트(`Ctrl+P`) → `보관소 폴더로 이동하기` 실행.

## 설정

- tacit 폴더: 파일을 가져올 폴더 경로
- attention 폴더: 파일이 도착할 폴더 경로
- 알림 표시 여부: 각 이동 시 알림 표시 on/off

## Buy Me a Coffee

플러그인 개발자에게 커피 한 잔을 후원해 주세요!  
[![Buy Me a Coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://buymeacoffee.com/dosakkhayo)

---

## 라이선스

MIT License
