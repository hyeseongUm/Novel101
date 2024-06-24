# 📖 소설 연재 사이트

## 🔎 프로젝트 소개
- 웹 소설 작가를 위한 연재 공간입니다.
- 이곳에서 소설을 연재하여 본인의 작품에 대한 독자 반응도를 체크할 수 있습니다.
- 응원이 일정 이상되었을 경우 다음 회차를 무료로 열람할 수 있습니다.
- 독자(회원)들은 자신이 응원하는 작품을 홍보하여 무료로 열람할 수 있습니다.

<br>

## 📅 개발기간
`2024.02.05` ~ `2024.02.16` <strong>(12일) </strong>

<br>

## 💦 작업관리
- `Notion` 으로 DB 쿼리 및 일정관리를 하였습니다.
- 주간 회의를 통한 진행 상황등은 `Notion`의 일정표에 기록해두었습니다.

  <a href="https://www.notion.so/87055257b31948e7bb3cc6e2ae50aeee"> DB쿼리문 & 일정 & 회의 관리</a>

<br>

## 👉 팀원 구성 및 역할 분담

<div align="center">
  
| **정운만** | **박건우** | **엄혜성** | **최성재** | **이규휘** |
| -------- | -------- | -------- | -------- | -------- |
| - 메인페이지 기능 구현<br>- 관리자페이지 유저관리 | - 소설 관련 기능 구현<br>- 소설 연재 등록<br>- 소설 뷰어<br>- 소설 좋아요 등록<br>- 소설 조건부 오픈 | - 소설 회차 댓글 작성<br>- 이벤트 페이지 CRUD  | - 홍보 게시판 CRUD <br>- 자유 게시판 CRUD | - 회원가입<br>- 로그인 기능 구현<br>- 1:1 문의<br>- 공지사항 등록 |

</div>
<br>

## ⚙ 개발환경
- FrontEnd : `jQuery` `JavaScript` `HTML5` `CSS`
- BackEnd : `Java` `JSP`
- Database : `MariaDB`

<br>

## 주요 기능

### 유저 기능
| 회원가입 |로그인 |
| ----- | ----- | 
|<img src="https://github.com/hyeseongUm/Novel101/assets/155358391/83dc0b28-f0ed-4f4d-970b-d7339d9be40d" width="470" height="400">|  <img src="https://github.com/hyeseongUm/Novel101/assets/155358391/9a5822fe-03b6-4f58-bf18-185c8551c0c6" width="470" height="400"> |
| 메인페이지</br><img src="https://github.com/hyeseongUm/Novel101/assets/155358391/14699ef8-3390-433d-a6b5-aabe3c2ecd27" width="470" height="400"> | 소설등록</br><img src="https://github.com/hyeseongUm/Novel101/assets/155358391/b05aa8a1-0c48-4892-8e79-df5cb3bfa005" width="470" height="400"> |
| 댓글</br><img src="https://github.com/hyeseongUm/Novel101/assets/155358391/cd793d5c-f321-497e-bff8-60da357f4ed3" width="470" height="400"> | 좋아요 10개 이상 다음 회차 공개</br><img src="https://github.com/hyeseongUm/Novel101/assets/155358391/4f6e1f85-b830-44c3-85e8-b045df84ae44" width="470" height="400"> |
| 게시판 CRUD</br><img src="https://github.com/hyeseongUm/Novel101/assets/155358391/effe59f8-a3e2-4db6-9611-e146de96404b" width="470" height="400"> |


### 관리자 기능

<br>

## Git-Hub 브랜치
- 빠른 개발을 위하여, Git-Hub 브랜치 전략을 사용하였습니다.
- 학원이라는 특성상, 바로 육성으로 커뮤니케이션을 진행할 수 있고, git push의 주기도 동일하게 할 수 있어 PR Convention은 따로 지정하지 않았습니다.
- Main 브랜치에 바로 적용하는 것이 아닌, 통합 후 새로운 Branch를 만들어 PR을 받고 충돌을 방지 및 해결 하는 방식으로 진행했습니다.

<br>

## Code Convention

||Class|Method|Variable|DB|
|:-:|:-:|:-:|:-:|:-:|
|Case|Pascal Case|camel Case|camel Case|snake_case
|Rule|명사|동사+명사|형용사+명사 or 명사|테이블명_명사|

