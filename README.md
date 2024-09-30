<h1 align="center">Todo List</h1><h3 align="center">구글 로그인 및 DB연동을 통한 Modal 기능 구현</h3>

## 프로젝트 소개

이 프로젝트는 구글 로그인 기능 및 DB연동을 통한 Modal 기능 구현을 목적으로 하고 있습니다.

- 이 Repository에서는 **백엔드**에 관한 내용만 담고 있습니다.
- 백엔드 서버: <https://taskbackend.aiccchant.com>-현재 인스턴스 중지

## 시작 가이드

- Requirements
  1. node.js 20.15.1
  2. npm 10.7.0
  3. postgreSQL(pgadmin4)

- Installation
```  bash
  1. $ git clone https://github.com/leejh7778/task-backend-cicd.git
  2. $ npm install
  3. $ npm run dev
```

- 백엔드포트는 기본적으로 8080 에서 실행됩니다.

## Stacks 🐈


### Environment
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)
![Node.JS](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white")
![AWS](https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white")

### Config
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)

### Development
![Html](https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white")
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white)


## 엔드포인트

- 일정 조회: https://taskbackend.aiccchant.com/get_tasks
- 일정 등록: https://taskbackend.aiccchant.com/post_task
- 일정 삭제: https://taskbackend.aiccchant.com/delete_task
- 일정 수정(완료여부만): https://taskbackend.aiccchant.com/update_completed_task
- 일정 수정(내용): https://taskbackend.aiccchant.com/update_task

## 주요기능

- 구글 기반 로그인
- DB와 연동하여 일정 등록 및 수정/삭제/조회
