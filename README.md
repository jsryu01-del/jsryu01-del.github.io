# Jisun Ryu — Academic Homepage

첨부된 `CV_Jisun Ryu_26_09_27.pdf`를 바탕으로 제작한 영문 연구자 홈페이지입니다. Psychiatric genetics를 주 연구 분야로 강조하고, 논문 제목과 Read article에 Nature 원문 링크를 연결했습니다.

## 포함 내용

- 이름, 소속, 연구실 및 이메일
- Research interests 5개
- Research experience: 연구실 2곳, 연구 설명 5개
- Publications: 논문 1편, 공동 제1저자 표기
- Education: 학력 3개 및 재학 기간
- 원본 CV PDF 다운로드
- 모바일 대응 레이아웃, 키보드 접근성, 페이지 metadata

원본 CV는 수정하지 않았습니다. 홈페이지에서는 `Nature Genetetics`를 `Nature Genetics`로 정정하고 문법을 다듬었습니다. 박사과정은 `PhD Student / PhD studies`로 표기했습니다.

## 로컬에서 보기

압축을 푼 뒤 `index.html`을 브라우저로 열면 됩니다. 별도 설치나 빌드가 필요하지 않습니다. `Jisun_Ryu_CV.pdf`와 `styles.css`를 `index.html`과 같은 위치에 유지하세요.

## GitHub Pages 게시

1. GitHub에서 본인 계정의 저장소를 준비합니다. 개인 홈페이지의 기본 주소를 사용하려면 저장소 이름을 `YOUR_USERNAME.github.io`로 지정합니다. `YOUR_USERNAME`은 실제 GitHub 사용자명으로 바꿉니다.
2. 이 폴더 안의 `index.html`, `styles.css`, `.nojekyll`, `Jisun_Ryu_CV.pdf`를 저장소의 최상위에 올립니다. 폴더 자체를 한 단계 더 감싸 올리지 않습니다.
3. 저장소의 **Settings → Pages**에서 게시 source를 **Deploy from a branch**, branch를 **main**, folder를 **/(root)**로 설정하고 저장합니다.
4. 게시 완료 후 Pages 화면의 **Visit site**로 확인합니다. 게시되기까지 시간이 걸릴 수 있습니다.

기존 홈페이지 저장소가 있다면 기존 파일을 먼저 확인하고 통합해야 합니다. 이 패키지는 계정이나 저장소를 생성하지 않으며, 아직 온라인 게시가 완료된 상태는 아닙니다.

공식 문서:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 내용 수정

- 본문·논문·경력·이메일: `index.html`
- 색상·글꼴·레이아웃: `styles.css`
- 다운로드할 CV: `Jisun_Ryu_CV.pdf`

모든 asset 경로는 상대 경로로 설정되어 개인 사이트와 프로젝트 사이트에서 사용할 수 있습니다. 외부 폰트, 추적 코드, 별도 서버 또는 JavaScript 의존성이 없습니다.
