# Skibidi War 모드 — 자동 업데이트용 릴리스

이 저장소에는 **모드 jar 파일만** 올라옵니다(소스 코드 없음).

## 처음 한 번만 (새 PC)
1. [최신 릴리스](https://github.com/muichilolove00810-boop/skibidi-war/releases/latest)에서 `skibidiwar-*.jar`를 받아 게임의 `mods` 폴더(CurseForge 프로필 → 폴더 열기 → `mods`)에 넣습니다.
2. 게임을 한 번 켭니다. 그러면 PC 시작프로그램에 **스키비디 업데이터**가 자동으로 등록됩니다.

## 그 다음부터
- PC에 로그인할 때마다 최신 릴리스를 확인해 바뀐 경우 jar를 교체합니다(게임이 켜져 있으면 끈 뒤에).
- 게임 안 메인 메뉴에도 새 버전 안내가 뜨고, 게임을 끄면 바로 업데이트됩니다.
- 끝나면 "스키비디 워 모드가 업데이트됐어요" 알림이 뜹니다.

## 되돌리기 / 끄기
- 되돌리기: `powershell -ExecutionPolicy Bypass -File "%LOCALAPPDATA%\SkibidiWar\updater\skibidi_updater.ps1" -Rollback`
- 기록: `%LOCALAPPDATA%\SkibidiWar\updater\updater.log`
- 자동 업데이트 끄기: `시작프로그램` 폴더(`Win+R` → `shell:startup`)에서 `스키비디 업데이터` 바로가기를 지웁니다.