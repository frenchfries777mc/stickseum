Stickseum 사이트 (정적 사이트: 서버 프로그램이 필요 없어요)
=========================================================

모든 파일이 폴더 없이 한 곳에 있어요. 이 파일들을 그대로 GitHub 저장소에 올리면 돼요.

  index.html                 첫 화면 (바로 플레이 / 다운로드 / 버전 목록 / 도움말)
  versions.json              버전 목록 (새 버전을 낼 때 여기에 한 줄 추가)
  Stickseum-v0.1 ~ v0.5.html 각 버전의 게임 파일
  Stickseum-latest.html      최신 버전의 복사본 ("바로 플레이"가 이 파일을 열어요)

[ 올리는 방법: GitHub Pages ]
  1. 저장소 화면에서 Add file > Upload files
  2. 이 폴더를 열고 Ctrl+A(전체 선택)로 파일을 모두 골라 끌어다 놓기 (폴더가 아니라 파일들이에요)
  3. Commit changes
  4. Settings > Pages > Deploy from a branch > main / (root) > Save
  5. 주소:  https://내아이디.github.io/저장소이름/    (1~2분 뒤 열려요, Ctrl+F5로 새로고침)

[ 새 버전을 낼 때 ]
  1. 새 게임 파일을 Stickseum-v0.6.html 처럼 올리기
  2. 같은 내용을 Stickseum-latest.html 로도 덮어쓰기 (같은 이름으로 올리면 교체돼요)
  3. versions.json 맨 위에 새 항목을 추가하고 이전 최신 항목의 "latest" 를 false 로, latest 값과 latestFile 을 바꾸기
     (저한테 새 버전을 알려 주시면 versions.json 까지 고친 파일을 만들어 드려요)

[ 알아 둘 점 ]
  - 친구들이 모두 "바로 플레이" 링크로 들어오면 항상 같은 버전이라 채팅·스킨이 서로 보이지 않는 문제가 생기지 않아요.
  - 진행 상황(골드·스킨 등)은 접속한 사이트 주소마다 따로 저장돼요. 주소가 바뀌면 새로 시작해요.
