# pro07

관공서 환경부 페이지 프로젝트 구현

```
공지사항 테이블
create table board(bid int primary key auto_increment,
title varchar(20) not null,
content varchar(500) not null,
author varchar(20) not null,
regdate datetime default now());
```

```
테이블 만들기
```
