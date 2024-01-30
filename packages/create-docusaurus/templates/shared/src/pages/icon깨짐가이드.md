---
title: Custom 정책 적용 시 Icon 깨짐 현상
description : Icon 깨짐 현상 발생 원인과 해결 방법
---

# **Custom 정책 적용 시 Icon 깨짐 현상**

## **Custom 정책명**
DSICON_CUSTOM_ROOT_FOLDER_PATH, DSICON_CUSTOM_PREFIX

 ## **발생 원인**  
 1. 레지스트리에 기본 아이콘이 존재하지 않는다.
 2. 폴더 경로가 일치하지 않는다.

---

## **문제 해결**
1. tfs에 레지스트리 첨부 (ppt, pptx, xlsx)
2. 최신 아이콘 폴더 사용

---

## **패치 모듈**  

DSSCIcon.dll|1.0.1.75;<br>
DSSCIcon64.dll|1.0.1.75;<br>


### <br>**※ 참고 사항**<br>
1. MS Office 설치 시, 레지스트리에 기본아이콘이 존재해야한다.<br>
2. 파일 경로 및 파일명이 최신폴더와 일치해야한다.<br>

tfs 주소 :
<https://sctfs.softcamp.co.kr/tfs/SCTFS2015/Development/_workitems#_a=edit&id=153191>
