---
layout: post
title:  2주차때 배운내용
date:   2022-03-09 00:46:45 +0900
categories: jekyll update
---

# Vscode 기능창

window : `[Ctrl] + shift + p`
mac : `[cmd] + shift + p`

# Git vs Github

* Git : 버전관리시스템 : 저장소
* Github: git -> 온라인 저장소 : 협업툴 
* Github pages : web hosting : 도메인 무료 (Geykll)

# 구조

**구조 스테이징 - 깃허브 저장소**

# Git 명령어

`git ` git 명령어 목록

## 저장소 초기화  
`git init[directory]`   스테이징 초기화  
`git clone[repositoty] ` 깃허브 저장소 into a new directory(내컴) 복제  

## 버전 관리 (업데이트)
`git add [file...]`  스테이징에 업로드   
> git hub . 명령어는 모든 파일 업데이트  

<<<<<<< HEAD
`git commit -m [message]`  업데이트 메모  
`git push ` 컴 -> 깃허브 저장소 업로드
`git pull' 깃허브 저장소 -> 컴 다운로드
=======
`git commit -m [message]`  스테이징 파일  -> 버전 업데이트 업데이트 메모  
`git push ` : 로컬 저장소 -> 온라인 저장소 업로드
 
## 상태 
`git status`  
`git log`

## 오류해결 방법

```
warning: LF will be replaced by CRLF in _config.yml.
The file will have its original line endings in your working directory
```

`git config --global core.autocrlf true`





