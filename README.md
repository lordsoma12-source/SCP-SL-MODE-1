# SCP-SL-MODE-1
내가 바로 SCP 다에 대한 C# EXILED 버전 코드
# SCP:SL EXILED Plugin - SCP Abilities

## 📦 프로젝트 내용
- SCP:SL EXILED 플러그인으로 SCP 능력을 적용
- 구현 SCP: 018, 207, O-207, 500, 2176 등
- 능력 상태 추적, 이벤트 훅, 명령어 API 포함

## ⚙️ 설치 방법
1. EXILED 설치 후 서버 `Plugins` 폴더 확인
2. 빌드된 DLL 파일을 `Plugins` 폴더에 넣기
3. 서버 재시작

## 🛠 개발 & 빌드
- .NET 6 / Visual Studio 2022 추천
- EXILED v3+ 기준 API 사용
- Ability 구현 시 `Abilities` 폴더 참고

## 🔧 기능 추가
- 새로운 SCP 능력은 `Abilities` 폴더에 추가
- `EventHandlers.cs`에 이벤트 훅 등록

## ✅ GitHub 업로드 체크리스트
- [x] `.gitignore` 포함
- [x] 프로젝트 폴더 구조 확인
- [x] README.md 포함
- [x] DLL 빌드 후 Plugins 폴더에 넣기
