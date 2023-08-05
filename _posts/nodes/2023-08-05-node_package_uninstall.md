---
title: Node.js 패키지 삭제하기
author: DH Kang
date: 2023-08-05
layout: post
---

## 1. 먼저 설치된 패키지 목록 확인
```bash
# 설치된 전역 패키지 확인
npm ls -g --depth=0 

# 현재 디렉토리의 로컬 패키지를 확인
npm ls --depth=0 
```

## 2. 각 패키지 삭제
```bash
# 전역 패키지 삭제
npm uninstall -g <package-name>

# 현재 디렉토리의 로컬 패키지 삭제
npm uninstall <package-name>
```