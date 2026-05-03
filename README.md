# 창원 더박스 (THE BOX 창원) 홈페이지

깃헙(GitHub Pages)에 그대로 올려서 무료로 운영할 수 있는 정적 홈페이지입니다.

## 폴더 구조

```
changwon-thebox-github/
├── index.html              ← 메인 페이지
├── favicon.svg             ← 탭 아이콘
├── opengraph.jpg           ← 카카오톡/페이스북 공유 시 미리보기 이미지
├── consultation/
│   └── index.html          ← 무료 상담 신청 페이지
└── photos/                 ← 사용된 사진 13장
```

## 깃헙(GitHub Pages)에 올리는 방법 — 초보자용 단계별 가이드

### 1단계. 깃헙 저장소(Repository) 만들기
1. https://github.com 에 로그인
2. 오른쪽 위 `+` 버튼 → **New repository** 클릭
3. Repository name: `changwon-thebox` (원하는 이름으로)
4. **Public** 선택 (Private이면 GitHub Pages 무료로 못 씀)
5. **Create repository** 클릭

### 2단계. 파일 업로드
1. 저장소 메인 화면에서 **Add file → Upload files** 클릭
2. 이 폴더(`changwon-thebox-github`) **안에 있는 파일·폴더 전부**를 끌어다 놓기
   - ⚠️ 폴더 자체가 아니라 **폴더 내부의 파일들**을 올려야 합니다
   - `index.html`, `favicon.svg`, `opengraph.jpg`, `consultation/`, `photos/` 5개 항목
3. 아래쪽 **Commit changes** 클릭

### 3단계. GitHub Pages 켜기
1. 저장소 화면 위쪽 메뉴에서 **Settings** 클릭
2. 왼쪽 메뉴에서 **Pages** 클릭
3. **Source** 항목에서:
   - Branch: `main`
   - Folder: `/ (root)`
4. **Save** 클릭
5. 약 1~2분 기다리면 위쪽에 주소가 뜸:
   ```
   https://본인깃헙아이디.github.io/changwon-thebox/
   ```

### 4단계. 완료 확인
- 위 주소를 브라우저에 열어서 사이트가 보이면 성공!
- 무료 상담 신청 페이지도 잘 열리는지 클릭해서 확인

## 사진 교체하고 싶을 때
1. `photos/` 폴더에 새 사진 업로드
2. `index.html` 파일에서 바꾸고 싶은 사진 이름을 새 사진 이름으로 변경
3. 저장 후 깃헙에 다시 업로드 → 1~2분 후 자동 반영

## 글자 수정하고 싶을 때
- `index.html` 파일을 깃헙에서 직접 수정 가능
   (저장소에서 파일 클릭 → 연필 아이콘 클릭)

## 도메인 연결 (선택사항)
나중에 `thebox-changwon.com` 같은 자체 도메인을 쓰고 싶으면
Settings → Pages → Custom domain 에서 설정 가능합니다.
