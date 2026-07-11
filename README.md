# ScriptureTyping Releases

ScriptureTyping의 Windows 설치 파일과 자동 업데이트 파일을 배포하는 저장소입니다.

> 이 저장소에는 프로그램 소스 코드가 포함되어 있지 않습니다.  
> 일반 사용자는 **Releases**에서 설치 파일만 내려받으면 됩니다.

---

## ScriptureTyping 소개

ScriptureTyping은 성경 말씀을 읽고, 입력하고, 학습할 수 있도록 만든 Windows 데스크톱 프로그램입니다.

주요 기능은 다음과 같습니다.

- 성경 말씀 타이핑
- 말씀 학습 및 게임
- 오늘의 암송
- 설교 메모 작성 및 저장
- 다크 모드와 라이트 모드
- 프로그램 자동 업데이트

---

## 다운로드 및 설치

1. 아래의 **Releases** 페이지로 이동합니다.
2. 가장 최근 버전을 선택합니다.
3. `Assets`를 펼칩니다.
4. `ScriptureTyping-win-Setup.exe`를 내려받습니다.
5. 내려받은 설치 파일을 실행합니다.

[Releases 페이지에서 다운로드하기](https://github.com/antcraft159/ScriptureTyping-Releases/releases)

> 일반 사용자는 `.nupkg`, `releases.win.json` 등의 파일을 내려받을 필요가 없습니다.  
> `ScriptureTyping-win-Setup.exe`만 설치하면 됩니다.

---

## 베타 버전 안내

현재 배포되는 버전은 정식 출시 전 **베타 버전**입니다.

베타 버전에서는 다음과 같은 문제가 발생할 수 있습니다.

- 일부 기능이 변경될 수 있습니다.
- 예상하지 못한 오류가 발생할 수 있습니다.
- 저장 형식이나 화면 구성이 바뀔 수 있습니다.

중요한 설교 메모나 자료는 별도로 백업하는 것을 권장합니다.

---

## 자동 업데이트

ScriptureTyping은 실행 중 새 버전을 확인할 수 있습니다.

새 버전이 발견되면 프로그램에서 업데이트를 내려받고, 재시작 후 새 버전을 적용합니다.

자동 업데이트를 사용하려면 반드시 `ScriptureTyping-win-Setup.exe`로 설치해야 합니다.

> Visual Studio에서 직접 실행하거나 `dotnet publish` 결과물을 직접 실행한 경우에는  
> 설치된 프로그램으로 인식되지 않아 자동 업데이트가 작동하지 않을 수 있습니다.

---

## Windows 보안 경고

설치 파일을 처음 실행할 때 Windows SmartScreen 경고가 표시될 수 있습니다.

이 경우 다음 순서로 실행할 수 있습니다.

1. `추가 정보`를 누릅니다.
2. `실행`을 누릅니다.

코드 서명 인증서가 적용되기 전까지 일부 PC에서 해당 경고가 표시될 수 있습니다.

---

## 배포 파일 설명

Release의 `Assets`에는 다음과 같은 파일이 포함될 수 있습니다.

| 파일 | 설명 |
|---|---|
| `ScriptureTyping-win-Setup.exe` | 일반 사용자가 실행하는 설치 파일 |
| `ScriptureTyping-버전-full.nupkg` | Velopack 자동 업데이트용 전체 패키지 |
| `ScriptureTyping-버전-delta.nupkg` | 이전 버전에서 변경된 부분만 포함한 업데이트 패키지 |
| `releases.win.json` | Velopack이 새 버전을 확인할 때 사용하는 정보 파일 |

일반 사용자는 설치 파일만 내려받으면 됩니다.

---

## 오류 제보

오류를 발견한 경우 이 저장소의 **Issues**에 아래 내용을 포함하여 남겨 주세요.

- 사용 중인 ScriptureTyping 버전
- Windows 버전
- 오류가 발생한 기능
- 오류가 발생하기 전 수행한 작업
- 오류 화면 또는 메시지

[오류 제보하기](https://github.com/antcraft159/ScriptureTyping-Releases/issues)

---

## 지원 환경

- 운영체제: Windows 10 이상
- 권장 환경: Windows 11 64비트
- 인터넷 연결: 설치 파일 다운로드 및 자동 업데이트 시 필요

---

## 저장소 용도

이 저장소는 아래 용도로만 사용됩니다.

- ScriptureTyping 설치 파일 배포
- 베타 및 정식 버전 배포
- Velopack 자동 업데이트 파일 제공
- 버전별 변경 사항 안내
