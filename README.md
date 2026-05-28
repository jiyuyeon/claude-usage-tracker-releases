# Claude Usage Tracker — Downloads

macOS 메뉴바 앱.

## 📦 다운로드

➜ **[최신 릴리스 (v0.1.3+)](https://github.com/jiyuyeon/claude-usage-tracker-releases/releases/latest)**

### ⚠️ 본인 Mac 칩 확인 후 받으세요

본인 Mac 칩 확인 방법: **사과 메뉴 () → 이 Mac에 관하여**

| Mac 종류 | 받을 파일 |
|---|---|
| **Apple Silicon** (M1/M2/M3/M4 칩) | `Claude.Usage.Tracker-x.x.x-arm64.dmg` ← 파일명에 **`-arm64`** 포함 |
| **Intel Mac** | `Claude.Usage.Tracker-x.x.x.dmg` ← 파일명에 **`-arm64` 없음** |

**잘못 받으면 앱이 안 열립니다** (네이티브 모듈 호환성 문제).

## 설치

1. 본인 Mac 칩에 맞는 `.dmg` 다운로드
2. `.dmg` 더블클릭 → Claude Usage Tracker 아이콘을 **Applications 폴더로 드래그**
3. Applications에서 앱 실행

### ⚠️ 첫 실행 — Apple 보안 경고 통과

이 앱은 Apple 코드 서명이 없어서 macOS가 처음에 실행을 막습니다. **한 번만** 다음 절차를 거치면 됩니다:

1. 앱을 더블클릭하면 **"'Claude Usage Tracker'을(를) 열지 않음"** 경고가 뜸 → **완료** 누름
2. **시스템 설정** 열기 → **개인정보 보호 및 보안** 선택
3. 페이지를 아래로 스크롤 → "**'Claude Usage Tracker'을(를) 사용하지 못하도록 차단됨...**" 메시지 옆 **"그래도 열기"** 버튼 클릭
4. Mac 비밀번호(또는 Touch ID) 입력
5. 다시 열기 대화 상자에서 **열기** 클릭
6. 이제 앱이 정상 실행됩니다. 다음부터는 평소처럼 더블클릭해서 실행 가능.

## 사용법

- 첫 실행 시 **claude.ai 로그인 창**이 자동으로 뜸 → 한 번만 로그인
- 로그인 후에는 메뉴바 우측 상단에 작은 아이콘이 생김
- 부팅 시 자동 실행됨, 백그라운드에서 15분마다 claude.ai 사용량 수집
- 메뉴바 아이콘에 현재 세션 % 라이브 표시
- 메뉴바 아이콘 클릭 → **대시보드 열기**로 차트/통계 확인
- 대시보드 우상단 **스크린샷 저장** 버튼으로 보고서용 PNG 저장

데이터는 본인 Mac에만 로컬로 저장됩니다 (`~/Library/Application Support/claude-usage-tracker/`).
