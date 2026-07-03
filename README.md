# subject1 · 웹디자인 · 웹퍼블리싱 포트폴리오

HTML과 CSS만으로 제작한 개인 포트폴리오 사이트입니다.  
학원 실습 과제를 분석해 학습 내용 중심으로 구성했습니다.

## 파일 구조

```text
subject1/
├─ index.html          # 포트폴리오 메인 페이지
├─ subjects.html       # 기존 과제 목록 페이지
├─ css/
│  └─ style.css        # 포트폴리오 스타일
├─ 01_basic/           # HTML 기초 과제
├─ 02_name_anchor/     # 네임 앵커 과제
├─ 03_text/            # 텍스트 태그 과제
├─ 04_nested_list/     # 중첩 목록 과제
└─ README.md
```

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

- `[이름을 입력해 주세요]`
- `[한 줄 소개를 입력해 주세요]`
- `[자기소개를 입력해 주세요]`
- About 영역의 `[내용 입력 필요]`
- Contact 영역의 이메일, GitHub 주소, 연락 안내 문구

## 사용 기술

- HTML5
- CSS3 (외부 스타일시트)
- JavaScript 미사용

## 참고

- 과제 원본 파일은 `subjects.html` 및 각 폴더에서 확인할 수 있습니다.
- 외부 이미지, 외부 폰트, 외부 라이브러리는 사용하지 않았습니다.
