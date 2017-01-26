---
layout: post
title: "Getting started-github"
date: 2017-01-27 20:34:26
image: '/assets/img/'
description: 'Put your description here.'
main-class: 'jekyll'
color: '#B31917'
tags:
- github
categories:
introduction: 'Put your description here.'
---

# Github
=============

## Github 이란?
Github은 분산 버전 관리 툴인 깃(Git)을 사용하는 프로젝트를 지원하는 웹호스팅 서비스이다.

## Github 용어 설명
 * Commit : 
 * Staging area : 

## Github 설치 (Ubuntu)
 > $ sudo apt-get install git-core

## Github 프로젝트 생성, 관리
** 1. Github 홈페이지에서 "New repository" 생성. **

** 2. Local repo.의 원하는 위치에서 다음 command 사용. **
   Repository의 URL은 github 웹사이트에서 찾아 볼 수 있다.
 > $ git clone __*Repository URL*__

** 3. 프로젝트를 수정하였다면, 다음 명령들을 순서대로 진행한다. **
 * Commit 상태 확인.
 > $ git status
 * Commit에 추가.
 > $ git add .
 * Commit 실행.
 > $ git commit -m "__*Message*__"
 * 서버에 업로드.
 > $ git push __*Repository Name*__ master

** 4. 추가적인 유용한 명령어들. **
 * Staging area와 현재 수정된 내용의 차이를 확인
 > $ git diff __*File Name*__
 * 현재 까지의 모든 변경 내용을 확인
 > $ git log

## Markdown 편집기 (Haroopad)
Markdown 표시 내용을 바로 확인 할 수 있는 텍스트 에디터이다.

[하루패드 공식 홈페이지](http://pad.haroopress.com/user.html)
