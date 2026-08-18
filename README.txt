월별 자금 흐름 PWA

구성:
- index.html : 기존 모바일 자금관리 앱
- manifest.json : 홈 화면 설치/PWA 설정
- sw.js : 오프라인 캐시
- icons/ : 앱 아이콘

사용 방법:
1. 이 폴더 전체를 개인 GitHub 저장소에 업로드합니다.
2. GitHub Pages를 켭니다.
3. 발급된 https 주소를 PWABuilder에 입력합니다.
4. Android 패키지 생성 기능으로 APK/AAB를 만듭니다.

주의:
- 데이터는 앱/브라우저의 localStorage에 저장됩니다.
- 기기 간 자동 동기화는 아직 지원하지 않습니다.
