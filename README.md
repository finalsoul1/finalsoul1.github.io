# 권병준 경력기술서

https://finalsoul1.github.io/

이 저장소는 게시용 결과물만 담고 있으며, 직접 수정하지 않습니다.

## 만드는 방식

- 경력 내용은 JSON 파일 하나에 있습니다. Python 스크립트가 이 파일과 HTML 템플릿으로 웹 화면(`resume.html`)과 평문(`career.txt`)을 함께 만듭니다.
- PDF는 따로 만들지 않습니다. 화면의 PDF 저장 버튼이 브라우저 인쇄 창을 열고, 인쇄용 CSS가 메뉴와 장식을 숨겨 A4 문서로 정리합니다.
- 원본 데이터와 스크립트는 비공개 저장소에 있습니다. 그 저장소의 `main`에 push하면 GitHub Actions가 화면을 생성하고, 게시할 파일만 이 저장소에 커밋합니다. GitHub Pages는 이 저장소의 `main`을 그대로 게시합니다.
- 프레임워크와 패키지 없이 HTML, CSS, Python 표준 라이브러리만 씁니다. 섹션 내비게이터에만 짧은 JavaScript를 씁니다.
