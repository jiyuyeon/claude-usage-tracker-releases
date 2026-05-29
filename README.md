# Claude Usage Tracker — Downloads

claude.ai 주간 사용량 + Claude Code 사용량을 자동 수집해 통계 대시보드로 보여주는 메뉴바/트레이 앱. **macOS · Windows 지원.**

## 📦 다운로드

➜ **[최신 릴리스](https://github.com/jiyuyeon/claude-usage-tracker-releases/releases/latest)**

### 본인 OS / 칩 확인 후 받으세요

| OS | 받을 파일 |
|---|---|
| **macOS — Apple Silicon** (M1/M2/M3/M4 칩) | `Claude.Usage.Tracker-x.x.x-arm64.dmg` ← 파일명에 **`-arm64`** 포함 |
| **macOS — Intel** | `Claude.Usage.Tracker-x.x.x.dmg` ← 파일명에 **`-arm64` 없음** |
| **Windows x64** | `Claude.Usage.Tracker.Setup.x.x.x.exe` |

**macOS — 본인 Mac 칩 확인 방법**: 사과 메뉴 () → 이 Mac에 관하여. 잘못 받으면 앱이 안 열립니다 (네이티브 모듈 호환성 문제).

---

## macOS 설치

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

## Windows 설치

1. `Claude.Usage.Tracker.Setup.x.x.x.exe` 다운로드 → 더블클릭
2. **SmartScreen 경고**가 뜨면 **추가 정보 → 실행** 클릭 (코드 서명이 없어 처음 한 번만 노출됨)
3. 설치 마법사를 따라 진행 → 시작 메뉴에 **Claude Usage Tracker** 추가됨
4. 실행 시 작업 표시줄 우측 트레이 영역에 아이콘이 나타남. 호버하면 현재 세션 % 표시, 좌클릭으로 대시보드 열기.

---

## 사용법

- 첫 실행 시 **claude.ai 로그인 창**이 자동으로 뜸 → 한 번만 로그인
- 로그인 후 메뉴바 / 트레이에 작은 아이콘 표시
- 부팅 시 자동 실행, 백그라운드에서 15분마다 claude.ai 사용량 수집
- macOS: 메뉴바 아이콘 옆에 현재 세션 % 라이브 표시 / Windows: 트레이 호버 시 표시
- 메뉴바·트레이 아이콘 클릭 → **대시보드 열기**로 차트/통계 확인
- 대시보드 우상단 **스크린샷 저장** 버튼으로 보고서용 PNG 저장
- 헤더 우측 **프로필 칩** 클릭 → 다른 계정 추가 / 등록한 계정으로 전환 / 로그아웃 / 계정 삭제 (v0.2.0+, 최대 3개 보관)

## 데이터 저장 위치

수집된 데이터는 본인 컴퓨터에만 저장됩니다. **앱을 삭제하고 새 버전으로 재설치해도 이 디렉터리는 OS 인스톨러가 손대지 않으므로 데이터가 자동 이월됩니다.**

| OS | 경로 |
|---|---|
| macOS | `~/Library/Application Support/claude-usage-tracker/` |
| Windows | `%APPDATA%\claude-usage-tracker\` |
