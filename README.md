# vite를 이용한 포트폴리오 사이트 만들기

## vite를 사용하는 이유

vite는 현대적인 프론트엔드 개발에서 인기 있는 도구입니다.
Vite는 빠른 개발 환경을 제공합니다. 코드 수정 시 빠른 리로딩과 빌드 속도를 통해 개발자들은 생산성을 크게 향상시킬 수 있습니다.또한 모듈 번들링 측면에서 Vite는 ES 모듈을 사용하여 필요한 모듈만 로딩하므로 번들 크기를 최소화하고 웹 애플리케이션의 성능을 최적화합니다. 그리고 Vite는 다양한 프론트엔드 프레임워크를 지원하며, Vue.js, React, Svelte 등의 프레임워크를 채용한 프로젝트에서 유연하게 사용할 수 있습니다.

[vite](https://ko.vitejs.dev/)

# 번들링을 하는 이유

## 구현 기능

- 구글 폰트 적용
- smooth 효과 적용 `https://lenis.studiofreight.com/`
- 자바스크립트 메뉴 클릭 이동 효과 적용
- GSAP를 이용한 가로 효과
- javascript 모듈 기능 적용
- 웹표준 준수를 위한 스킵 메뉴 및 aria, role 적용
- vite 빌드 작업 `npm run build`
- netilfy 배포 작업

## 트러블 슈팅

<details>
    <summary>git 업로드 버그</summary>
    
    -git 업로드 설정 403에러 :
    
    git remote set-url origin https://moon411@github.com/mooon411/vite-project2023.git

    git add .
    git status
    git commit -m "수정"
    git push -u origin main

    -> 재로그인 및 신규 토큰 삽입 후 사용자 권한 인증

</details>
