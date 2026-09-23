# 김준한 프로필 웹페이지 (GitHub Pages)

국립공주대학교 기계공학전공 **김준한** 님의 모던 미니멀 단일 페이지 프로필 웹사이트입니다.

## 🚀 특징
- **순수 웹 기술**: 외부 라이브러리(Bootstrap, jQuery 등)나 빌드 도구 없이 `index.html`과 `styles.css`만으로 작동합니다.
- **아카데믹 & 모던 엔지니어링 테마**: Byung-Kwan Lee 님의 CV 스타일을 모티브로 하여 간결하고 정갈한 1페이지 포트폴리오로 재구성했습니다.
- **다크 모드 / 라이트 모드**: 우측 상단 토글 버튼을 통해 다크 모드와 라이트 모드를 즉시 전환할 수 있으며, 방문자의 OS 환경설정 및 브라우저 설정을 기억합니다.
- **완전 반응형**: 모바일 스마트폰, 태블릿, PC 모니터 모든 화면 크기에 최적화되어 있습니다.
- **원클릭 이메일 복사**: 이메일 주소 원클릭 클립보드 복사 기능 및 토스트 알림이 내장되어 있습니다.

---

## ✏️ 내용 수정 방법 (글자만 바꾸기)

`index.html` 파일을 텍스트 편집기(VS Code, 메모장 등)로 열어서 다음 부분을 원하는 내용으로 고치시면 됩니다:

1. **이메일 주소**:
   - `your-email@example.com` 검색 후 본인의 실제 이메일로 변경 (`hero-email-link`와 `email-text` 2곳)
2. **GitHub 링크**:
   - `https://github.com/your-username` 검색 후 본인의 GitHub 프로필 주소로 변경
3. **프로필 사진 (선택)**:
   - 본인 증명사진이나 프로필 이미지(예: `profile.jpg`)를 이 폴더에 넣고, `index.html` 내 주석 안내에 따라 `<img src="profile.jpg" ...>` 태그의 주석을 해제하시면 됩니다.
4. **프로젝트 및 활동 내용 (선택)**:
   - `프로젝트 및 활동 (Projects & Activities)` 섹션의 제목, 날짜, 설명을 자유롭게 추가하거나 수정하실 수 있습니다.

---

## 🌐 GitHub Pages 배포 방법

1. GitHub에서 새 저장소(예: `username.github.io` 또는 원하는 이름)를 생성합니다.
2. 이 폴더의 파일들(`index.html`, `styles.css`)을 해당 저장소의 `main` 브랜치에 업로드(또는 git push)합니다.
3. 저장소의 **Settings** &rarr; **Pages** 메뉴로 이동합니다.
4. **Source** 항목을 `Deploy from a branch`로 선택하고 브랜치를 `main` / `/(root)`로 지정한 뒤 **Save**를 누릅니다.
5. 몇 분 후 제공되는 URL(예: `https://username.github.io/`)로 접속하시면 배포된 프로필 페이지를 확인하실 수 있습니다.
