# vue-scss
Vue 기반 프로젝트에서 자주 사용하는 scss class 정의
- 개발 환경: Vue

## 디렉토리
```bash
📦vue-scss
 ┣ 📂src
 ┃ ┣ 📂assets           # 프로젝트 정적 자산 데이터가 들어가는 폴더
 ┃ ┃ ┗ 📂scss             # 전역 스타일 scss 모음 폴더
 ┃ ┃ ┃ ┣ 📜app.scss         # 전체 scss를 한번에 import하는 파일
 ┃ ┃ ┃ ┣ 📜_affter.scss     # 기본 초기 스타일 설정 뒤에 적용되는 scss 파일
 ┃ ┃ ┃ ┣ 📜_alignment.scss  # 정렬에 관련된 설정을 하는 scss 파일
 ┃ ┃ ┃ ┣ 📜_fontStyle.scss  # font의 크기와 굵기를 설정하는 scss 파일
 ┃ ┃ ┃ ┣ 📜_position.scss   # position을 설정하는 scss 파일
 ┃ ┃ ┃ ┣ 📜_reset.scss      # font, color, border, list-style 등 기본 스타일을 초기화 하는 scss 파일
 ┃ ┃ ┃ ┗ 📜_spacing.scss    # margin, padding 간격에 대한 설정을 하는 scss 파일
 ┃ ┣ 📜App.vue            # app.scss를 전역으로 호출하는 파일
 ┃ ┗ 📜main.js            # App.vue를 호출하는 파일
...
```
