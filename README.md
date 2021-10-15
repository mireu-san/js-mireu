# KOREAN
1. 이 프로젝트는 노마드코더 JS 챌린지를 통해 다시 한번 알게 된, 배운 내용을 직접 사용 해 봄으로써 자신의 JS 활용 능력을 최대한 증명 해 보이는 것 입니다.

2. 사용 예정 툴 및 언어: ES6, JS, bootstrap(제거, removed)

# New plan (written by 15th Oct):
- Refactoring the current code once the progression is over.
- ⏳Try benchmarking JS feature I can embed on this project.
- Note: There is no specific API feature I can add here...for now. (maybe clock feature instead? This is DOM API though.)
- ⏳Try adding responsive feature (need to benchmark what INSTANCE I can possibly compose it on my project).
---------------------------------------------------------------
# Installed:
- npm i @popperjs/core

# implemented with :
- https://getbootstrap.com/docs/5.1/getting-started/introduction/ (will not be applied)

# Error note (에러 노트):
## 해결 못함(원인 불명) - 
1. 다른 브라우저 및, 모바일은 정상이나 PC Chrome 브라우저 94.0 ver 에서만 text-align: center; 가 적용이 안 됨.


# 설계면 - skeleton
## 1.0 Header
### 1.1 Greeting - title, centre(CSS)
### 1.2 sub titlte - " "
### 1.3 link - github, tech blog (button, link)
### 1.4 My blog picture

## 2.0 Body
### 2.1 About me
### 2.2 Skills
### 2.3 Portfolio

## 3.0 Footer
### 3.1 Contact
### 3.2 phone number, email, whatsapp or Kakao link (button, link)
### 3.3 Copyright (centre, css)

# 설계면 - feature
- Note: this is not SPA, this is not React.js! However, smooth scrolling may be possible on vanilla js too. Keep this in mind.

# 낙서장
- 모든 pictures -> CSS 로 -> 모서리 둥글게
- About me 아바타 뒤에, 배경 넣기 (psv? 웹 파일 활용 참고).
- portfolio 부분에 대표작 이미지 3개만 넣기.

## 할 수 있는 것 with JS (component):
- Alerts for dismissing
- Buttons for toggling states and checkbox/radio functionality
- Carousel for all slide behaviors, controls, and indicators
- Collapse for toggling visibility of content
-Dropdowns for displaying and positioning (also requires Popper)
-Modals for displaying, positioning, and scroll behavior
-Navbar for extending our Collapse plugin to implement-responsive behavior
-Offcanvases for displaying, positioning, and scroll behavior
-Toasts for displaying and dismissing
-Tooltips and popovers for displaying and positioning (also-requires Popper)
-Scrollspy for scroll behavior and navigation updates
