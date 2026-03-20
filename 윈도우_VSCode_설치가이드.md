# 윈도우에 Visual Studio Code 설치 가이드

## 1. 다운로드

1. 공식 사이트 접속: https://code.visualstudio.com/
2. **Download for Windows** 버튼 클릭
   - 안정 버전(Stable): 일반 사용 권장
   - 설치 파일: `VSCodeSetup-x64-*.exe`

## 2. 설치

1. 다운로드한 `.exe` 파일 실행
2. 설치 마법사 진행:
   - **사용권 계약** → 동의 후 다음
   - **설치 위치** → 기본값 유지 권장
   - **시작 메뉴 폴더** → 기본값 유지
   - **추가 작업 선택** (권장 옵션):
     - [x] 바탕 화면 아이콘 만들기
     - [x] PATH에 추가 (명령 프롬프트에서 `code` 명령 사용 가능)
     - [x] "Code로 열기" 작업을 Windows 탐색기 파일 컨텍스트 메뉴에 추가
     - [x] "Code로 열기" 작업을 Windows 탐색기 디렉터리 컨텍스트 메뉴에 추가
3. **설치** 클릭 → 완료 후 **마침**

## 3. 설치 확인

명령 프롬프트(CMD) 또는 PowerShell에서:
```cmd
code --version
```

## 4. 기본 확장 프로그램 설치 (권장)

VS Code 실행 후 Extensions(확장) 탭(`Ctrl+Shift+X`)에서 설치:

| 확장 프로그램 | 용도 |
|---|---|
| Korean Language Pack | 한국어 UI |
| Prettier | 코드 포맷터 |
| GitLens | Git 연동 강화 |
| ESLint | JavaScript 린터 |

## 5. 한국어 설정

1. `Ctrl+Shift+P` → `Configure Display Language` 검색
2. `ko` (한국어) 선택 → VS Code 재시작

## 6. winget으로 설치 (선택사항)

PowerShell 관리자 권한으로 실행:
```powershell
winget install Microsoft.VisualStudioCode
```

---

**공식 문서**: https://code.visualstudio.com/docs/setup/windows
