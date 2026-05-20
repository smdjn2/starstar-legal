# StarStar — Legal Pages

App Store / Play Console 에 등록할 **개인정보처리방침 / 이용약관 공개 URL** 용 정적 사이트.

## 파일 구조

```
legal/
├── index.html      ← 진입점 (두 문서 링크)
├── privacy.html    ← 개인정보처리방침
├── terms.html      ← 이용약관
├── style.css       ← 공통 스타일 (라이트/다크 자동 대응)
└── logo.svg        ← StarStar 로고
```

## GitHub Pages 호스팅 (10분, 무료)

가장 간단한 무료 호스팅. 도메인이 필요 없음.

### 1) 새 GitHub 저장소 만들기
- https://github.com/new
- 저장소 이름: `starstar-legal` (또는 원하시는 이름)
- **Public** 선택 (Pages는 무료 plan에서 public 만 됨)
- "Create repository" 클릭

### 2) 이 `legal/` 폴더 안 파일들을 저장소에 업로드
- 새로 만든 저장소 페이지에서 **"uploading an existing file"** 링크 클릭
- `C:\myclaude\starstar\legal\` 안의 5개 파일 (index.html, privacy.html, terms.html, style.css, logo.svg) **드래그&드롭**
- "Commit changes" 클릭

### 3) Pages 활성화
- 저장소 페이지 상단 **Settings** 클릭
- 왼쪽 사이드바에서 **Pages**
- "Source" → **Deploy from a branch** 선택
- "Branch" → **main** + 폴더 **/ (root)** 선택 → Save
- 1~2분 후 페이지 위에 URL 표시됨 (`https://<username>.github.io/starstar-legal/`)

### 4) URL 확인
- `https://<username>.github.io/starstar-legal/` → 진입 페이지
- `https://<username>.github.io/starstar-legal/privacy.html` → 개인정보처리방침 ← 이게 콘솔 등록용
- `https://<username>.github.io/starstar-legal/terms.html` → 이용약관

### 5) Apple/Google 콘솔에 등록
- **App Store Connect** → 앱 정보 → "Privacy Policy URL" 에 위 privacy.html URL 입력
- **Google Play Console** → 앱 콘텐츠 → "개인정보처리방침" 에 같은 URL 입력

## 미리 보기 (호스팅 전)

브라우저에 `index.html` 더블클릭으로 열면 동작 확인됨.

## 수정 시

- 저장소에서 직접 파일 클릭 → 연필 아이콘 → 수정 → commit
- 자동 재배포 (~1분)
