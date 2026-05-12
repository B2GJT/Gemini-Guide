# Gemini 3.0 설정법 가이드

## 개요

기존 PPT 형태로 배포하던 Gemini 3.0 설정 매뉴얼을 수강생 가독성 향상을 위해 웹 페이지로 전환한 프로젝트입니다.

- **대상:** Gemini를 업무에 활용하려는 직장인 및 수강생
- **목적:** PPT 배포 방식의 한계를 벗어나 언제 어디서나 URL로 접근 가능한 가이드 제공

---

## 페이지 구성

단계별 흐름에 따라 스크린샷과 함께 안내합니다.

| 단계 | 내용 |
|------|------|
| 1 | Gemini Flash / Pro 모드 설정하기 |
| 2 | Google Workspace 앱 연동하여 답변 받기 |
| 3 | 이미지 생성, Canvas 기능 사용하기 |
| 4 | 설정 - 시스템 설정 |
| 5 | Gemini에게 저장하도록 요청한 정보 메뉴 확인 |
| 6 | Google Workspace 앱 연동 확인 및 켜기 |
| 7 | 대답 재작성 및 Docs 내보내기 & Gmail 초안 작성 |

- **디자인:** Mintlify 스타일 기반 단일 HTML 파일 (외부 프레임워크 없음)
- **구조:** 상단 네비바 + 좌측 목차 사이드바 + 본문

---

## 파일 구조

```
Gemini-Guide/
├── gemini-guide.html   # 가이드 본문
├── image.png           # Step 1 - 모드 설정 화면
├── image 1.png         # Step 2 - Google Workspace 앱 연동 화면
├── image 2.png         # Step 3 - 이미지 생성 및 Canvas 화면
├── image 3.png         # Step 4 - 시스템 설정 화면
├── image 4.png         # Step 5 - Gemini 요청 사항 메뉴 화면
├── image 5.png         # Step 6 - Workspace 앱 연동 확인 화면
└── image 6.png         # Step 7 - Docs 내보내기 & Gmail 초안 화면
```

---

## 수강생 배포 방법

GitHub Pages를 통해 URL을 생성하고 수강생에게 공유합니다.

### 수강생 공유 URL

```
https://b2gjt.github.io/Gemini-Guide/gemini-guide.html
```

---

## 업데이트 방법

스크린샷 교체나 내용 수정이 필요한 경우:

- **이미지 교체:** 해당 이미지 파일을 같은 이름으로 덮어쓴 후 push
- **본문 내용 수정:** `gemini-guide.html` 수정 후 push
- push 후 수 분 내에 배포 URL에 자동 반영됩니다.
