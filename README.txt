ARENA CLASH 사이트 (정적 사이트: 서버 프로그램이 필요 없어요)
==========================================================

이 폴더를 그대로 인터넷에 올리면 됩니다. 폴더 안:
  index.html        첫 화면 (바로 플레이 / 다운로드 / 버전 목록 / 도움말)
  versions.json     버전 목록 (새 버전을 낼 때 여기에 한 줄 추가)
  files/            게임 파일들 (ArenaClash-v0.5.html 등, ArenaClash-latest.html 은 최신 버전의 복사본)

[ 올리는 방법 - 가장 쉬운 것부터 ]

1) Netlify Drop (가입 없이도 가능, 1분)
   - https://app.netlify.com/drop 을 열고, 이 폴더(arena-site) 또는 arena-site.zip 을 끌어다 놓기
   - 바로 https://무작위이름.netlify.app 주소가 생겨요. (가입하면 주소 이름을 바꾸고 계속 유지할 수 있어요)

2) GitHub Pages (무료, 주소가 영구적, 새 버전 올리기도 편해요)
   - GitHub에서 새 저장소를 만들고 이 폴더의 내용을 올리기
   - Settings > Pages > Branch 를 main / (root) 로 선택 → https://아이디.github.io/저장소이름/

3) Cloudflare Pages (무료)
   - dash.cloudflare.com > Workers & Pages > Create > Pages > Upload assets 에 이 폴더를 올리기

[ 새 버전을 낼 때 ]
  1. 새 게임 파일을 files/ArenaClash-v0.6.html 처럼 넣기
  2. 같은 내용을 files/ArenaClash-latest.html 로도 덮어쓰기 ("바로 플레이"가 항상 최신을 열도록)
  3. versions.json 의 versions 맨 위에 새 항목을 추가하고, 이전 최신 항목의 "latest" 를 false 로, latest 값과 latestFile 을 새 것으로 바꾸기
  4. 폴더를 다시 올리기 (Netlify Drop은 같은 사이트에 다시 끌어다 놓으면 덮어써요)

[ 알아 둘 점 ]
  - 친구들이 모두 "바로 플레이" 링크로 들어오면 항상 같은 버전이라 채팅·스킨이 서로 보이지 않는 문제가 생기지 않아요.
  - 진행 상황(골드·스킨 등)은 접속한 사이트 주소마다 따로 저장돼요. 주소가 바뀌면 새로 시작해요.
  - 파일로 직접 열어도(index.html 더블클릭) 버전 목록과 링크가 작동해요.
