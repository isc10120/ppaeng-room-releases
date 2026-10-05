# ppaeng-room 설치 안내

설치 파일은 [Releases](https://github.com/isc10120/ppaeng-room-releases/releases/latest)에서 받는다.

| 기기 | 파일 |
|---|---|
| Windows | `ppaeng-room-setup-<버전>.exe` |
| Mac (Apple Silicon: M1 이후) | `ppaeng-room-<버전>-arm64.dmg` |
| Mac (Intel) | `ppaeng-room-<버전>-x64.dmg` |
| Android | `ppaeng-room-<버전>.apk` |

## Windows

1. `.exe`를 실행한다
2. "Windows의 PC 보호" 창이 뜨면 **추가 정보** → **실행**
3. 설치가 끝나면 앱이 열린다. 창을 닫아도 작업 표시줄 오른쪽 트레이에 남아 있다(완전히 끄려면 트레이 아이콘 우클릭 → 종료)

새 버전은 앱이 자동으로 받아 두었다가, 앱을 종료할 때 설치한다.

## Mac

1. `.dmg`를 열고 ppaeng-room을 Applications 폴더로 끌어 넣는다
2. 처음 열 때 "확인되지 않은 개발자" 경고가 뜨면 **시스템 설정 → 개인정보 보호 및 보안** 아래쪽의 **그래도 열기**를 누른다
   - 경고 대신 "손상되었기 때문에 열 수 없습니다"가 뜨면 터미널에서 실행: `xattr -cr /Applications/ppaeng-room.app`
3. 새 버전은 자동으로 설치되지 않는다. 새 `.dmg`를 받아 같은 방법으로 덮어쓴다

## Android

1. 폰 브라우저에서 `.apk`를 받는다
2. 열면 "출처를 알 수 없는 앱" 설치 허용을 묻는다 → 해당 브라우저(예: Chrome)를 **허용**
3. Play 프로텍트가 "확인되지 않은 앱"이라고 하면 **세부정보 더보기 → 무시하고 설치**
4. 새 버전은 새 `.apk`를 받아 설치하면 기존 앱 위에 덮어써진다(데이터 유지)
