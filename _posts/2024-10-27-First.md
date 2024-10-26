---
layout: post
title: "GitHub Pages 깃허브 블로그 시작하기"
date: 2024-10-27
categories:
  - blog
tags:
  - GitHub Pages
  - Jekyll
---
# GitHub 블로그 시작하기

- GitHub 계정에 로그인

1. GitHub Pages 생성 
  - Jekyll 테마 선택: [깃허브 테마 페이지](https://github.com/topics/jekyll-theme)블로그 테마중에서 마음에 드는 테마를 선택
  - 선택한 테마의 레포지토리를 fork해오거나 또는 zip파일을 다운받아 수정 후 새로운 레포지토리에 업로드
  - 해당 레포지토리의 이름은 `[사용자명].github.io 로 설정
2. 블로그 설정
  - _config.yml -> 블로그 제목, 설명 등 기본 정보를 수정
    - url: "https://user_ID.github.io" 로 수정하여 블로그 생
    - 
3. 첫 포스트 작성
  - _posts/YYYY-MM-DD-제목.md 형식으로 파일을 만들어 작성
    - 이후 포스트도 _posts 폴더에서 해당양식으로 작성
  - 첫 포스트의 내용을 작성한 뒤 commit changes
    - https://jekyllrb.com/docs/posts/ -> jekyllrb공식문서 포스팅 예시 참조
      ```
      ---
      layout: post
      title: "제목"
      ---
      포스트 내용에 이와같이 명시?
      ```
4. 코드 올리기
  - 마크다운파일 .md로 작성해서 올리기
  - .ipynb 파일을 구글링으로 간편하게 .md로 변환하여 업로드
[GitHub Pages 공식 문서](https://docs.github.com/en/pages)참조
