# subject1 · 웹디자인 · 웹퍼블리싱 포트폴리오

HTML과 CSS만으로 제작한 개인 포트폴리오 사이트입니다.  
학원 실습 과제를 분석해 학습 과정과 성장 흐름 중심으로 구성했습니다.

## 파일 구조

```text
subject1/
├─ index.html          # 포트폴리오 메인 페이지
├─ subjects.html       # 기존 과제 목록 페이지 (수정하지 않음)
├─ css/
│  └─ style.css        # 포트폴리오 스타일
├─ 01_basic/           # HTML 기초 과제
├─ 02_name_anchor/     # 네임 앵커 과제
├─ 03_text/            # 텍스트 태그 과제
├─ 04_nested_list/     # 중첩 목록 과제
└─ README.md
```

## 페이지 구성

| 영역 | 설명 |
|------|------|
| Hero | 포트폴리오 소개, 기술 배지, 코드 장식 |
| About | 자기소개·학습 계기·목표 (2열 편집형 레이아웃) |
| Learning Journey | 8단계 학습 타임라인 |
| Skills | 학원 학습 기술 / 포트폴리오 신규 적용 기술 구분 |
| Code Preview | HTML·CSS 코드 조각 시각 요소 |
| Works | 대표 과제 6개 + 전체 과제 링크 |
| Contact | 연락처 안내 |

## 로컬에서 확인

브라우저에서 `index.html` 파일을 직접 열거나, 아래 명령으로 간단한 서버를 실행할 수 있습니다.

```bash
cd subject1
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000` 으로 접속합니다.

## GitHub Pages 배포

1. 변경 사항을 커밋하고 `main` 브랜치에 푸시합니다.
2. GitHub 저장소 **Settings → Pages** 로 이동합니다.
3. **Source** 를 `Deploy from a branch` 로 선택합니다.
4. **Branch** 를 `main`, 폴더를 `/ (root)` 로 설정 후 **Save** 합니다.
5. 몇 분 후 `https://사용자아이디.github.io/subject1/` 에서 확인합니다.

## 직접 수정할 내용

`index.html` 에서 아래 placeholder 문구를 본인 정보로 바꿔 주세요.

- `[이름 입력 필요]`
- `[한 줄 소개 입력 필요]`
- `[자기소개 입력 필요]`
- About 영역의 `[내용 입력 필요]`
- Contact 영역의 `[이메일 입력 필요]`, `[GitHub 주소 입력 필요]`

## 사용 기술

### 학원에서 학습한 기술
- HTML5 기본 마크업 (제목, 문단, 목록, 정의 목록, 텍스트 태그, 네임 앵커)
- CSS 기본 (요소·id·자손 선택자, 색상, 여백, 행간, 링크 스타일)

### 포트폴리오에서 새롭게 적용한 기술
- Flexbox, CSS Grid, 미디어쿼리
- CSS 변수, position: sticky
- hover, focus, transition, transform
- ::before, ::after, CSS 그라데이션
- scroll-behavior: smooth

- JavaScript 미사용

## 참고

- 과제 원본 파일은 `subjects.html` 및 각 폴더에서 확인할 수 있습니다.
- 외부 이미지, 외부 폰트, 외부 라이브러리는 사용하지 않았습니다.
