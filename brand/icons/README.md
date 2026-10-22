# 디지털 아이콘

확정 기본 로고의 주황색·가느다란 줄기·뾰족한 파형을 5개 파형으로 단순화한 소형 적용형이다. 기본 로고 원본은 ../vectors/에 유지한다.

- favicon.svg / favicon.ico: 브라우저용. ICO는 16·32·48px 포함.
- app-icon.ico: Windows용. 16·24·32·48·64·128·256px 포함.
- app-icon-1024.png: 앱 아이콘 고해상도 원본.
- apple-touch-icon.png: 180px. iOS 홈 화면용.
- icon-192.png / icon-512.png: 웹 앱 기본 아이콘.
- icon-maskable-512.png: 중앙 안전 영역을 확보한 마스킹용.
- symbol-small.svg: 배경 없는 편집 가능 소형 심볼.
- manifest.example.webmanifest: 연결 예시. 서비스의 기존 manifest와 병합하고 start_url·scope는 실제 서비스 경로에 맞춰 설정한다.

현재는 자산 보관만 완료했다. 서비스 서버의 정적 경로·HTML·Electron 빌드 설정에는 별도로 연결해야 한다. 저장소 URL이 아닌 실제 서비스에서 제공하는 URL로 연결한다.
