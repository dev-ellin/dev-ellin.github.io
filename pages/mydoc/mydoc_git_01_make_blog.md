---
title: Github 블로그 만들기 (github.io)
tags: [git, github, blog]
keywords: git, github, blog, 블로그
last_updated: Sep 22, 2023
summary: 'GitHub Pages 서비스를 이용해 무료로 블로그를 만들어봅시다 !'
sidebar: mydoc_sidebar
permalink: mydoc_git_01_make_blog.html
folder: mydoc
---

## 준비사항

- 깃허브 계정
  깃허브 블로그를 만들기 위해서는 **깃허브 계정**이 필요합니다.
- Ruby & Jekyll
  - ruby 버전 확인
  <div style="background-color: rgb(50, 50, 50); color: rgb(255,255,255); padding: 20px;">&#36; ruby -v</div>
  - jekyll 설치
  <div style="background-color: rgb(50, 50, 50); color: rgb(255,255,255); padding: 20px;">&#36; gem install jekyll bundler</div>

## Reporisoty 생성

- Repository name을 [usename].github.io 형태로 아래와 같이 작성하세요.

![create_repo](../../images/git/1_1.png)

- 생성 완료시 아래와 같이 보입니다.

![create_repo_done](../../images/git/1_2.png)

## Jekyll Theme 준비

- 원하는 테마를 찾아서 zip 파일로 다운 받습니다.
  ![prepareTheme](../../images/git/1_3.png)

- zip 파일 내에 파일과 폴더를 전체 복사해서 원격 repo와 연결된 프로젝트에 붙여넣기 합니다. <br/> 겹치는 파일은 모두 새로운 파일로 대체(replace)하시면 됩니다.
  ![copyandpaste](../../images/git/1_4.png)

## 블로그 실행

- 아래 명령어를 순차 입력합니다.

<div style="background-color: rgb(50, 50, 50); color: rgb(255,255,255); padding: 20px;">&#36; bundle install <br/>&#36; bundle exec jekyll serve</div>

- 아래와 같이 보이면, http://127.0.0.1:4000에서 테마 적용한 웹페이지를 확인할 수 있습니다.

![copyandpaste](../../images/git/1_5.png)
