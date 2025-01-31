# 나만의 아고라 스테이츠 만들기

## 구현해야 할 기능 목록

### 📌 Bare Minimum Requirement 기능

- [x] ✨ 디스커션 나열 기능

  - `agoraStatesDiscussions` 배열의 데이터를 화면에 나열해야 한다.

- [x] ✨ 디스커션 추가 기능

  - `section.form__container`에 새로운 질문을 추가할 수 있는 입력 폼을 제작한다.
  - 아이디, 본문을 입력하고 버튼을 누르면 화면에 새로운 질문이 추가되어야 한다.
  - 새롭게 추가한 질문도 `agoraStatesDiscussions` 배열의 데이터에 쌓여야 한다.

- [x] 🎨 CSS 요구사항

  - 질문 리스트를 화면 중앙에 배치한다.
  - 적절한 색 조합, 디자인을 참고하여 나만의 아고라 스테이츠를 꾸민다.

- [x] 🚀 Github Page 배포

  - Github Page 배포기능을 이용하여 누구나 볼 수 있게 실제 배포한다.

- [x] 🚀 미션 레파지토리에 PR 보내기
  - 주어진 PR 형식에 맞춰서 PR을 보낸다.

### 📌 Advanced Challenge 기능

- [x] ✨ 현지 시간 적용 기능

  - 샘플 시간을 잘 변형하여, 현지 시간에 맞게 표현한다. (실제 현시간 적용)

- [x] ✨ 페이지네이션 기능

  - 한 페이지에 10개씩 디스커션이 화면에 출력되어야 한다.
  - 다음 페이지로 넘어갈 수 있어야 한다.
  - 이전 페이지로 돌아올 수 있어야 한다.
  - 이전, 다음 페이지가 없다면 현재 페이지를 유지해야 한다.

- [x] ✨ 디스커션 유지 기능

  - 새롭게 추가되는 디스커션이 페이지를 새로고침해도 유지되도록 한다. (LocalStorage에 데이터저장)

- [x] ✨ 답변 렌더링 기능
  - 질문에 답변이 있는 경우, 답변도 화면에 렌더링 한다. (형식은 자유)

### 📌 추가 기능 구현

- [x] ✨ 디스커션 추가시 이미지 선택 기능

  - 디스커션을 새롭게 등록할 때 이미지를 선택하여 등록할 수 있다.

- [x] ✨ 검색 기능 구현 (추후 추가 구현)

  - 제목 혹은 이름 검색 시 일치하는 질문 목록들을 화면에 출력한다.

- [x] ✨ notice와 질문 분리

  - 공지사항과 질문을 분리하여 화면에 출력할 수 있다. (형식은 자유)

- [x] ✨ top 버튼 기능 구현

  - top 버튼 클릭시 화면의 최상단으로 이동한다. (부드러운 이동)

- [x] ✨ 페이지네이션 추가 기능

  - 페이지에 출력되는 최대 디스커션 초과시 자동적으로 페이지 생성
  - 가장 마지막 페이지는 나머지 디스커션 출력
  - ex. 51개의 디스커션 등록시 전체 페이지 수는 6페이지 (6페이지엔 1개의 디스커션 출력됨)
  - ex. 100개의 디스커션 등록시 전체 페이지 수는 10페이지 (10페이지엔 10개의 디스커션 출력됨)

- [x] 🎨 CSS 애니메이션 적용하기
  - 애니메이션 혹은 transition을 적용하여 부드러운 화면 출력을 제공한다.
