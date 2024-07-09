## 요구사항

- 글을 추가한다.
- 글 목록을 조회한다.
- 글을 조회한다.
    - 글이 없으면 `NotFoundError`가 발생한다.
- 글을 수정한다.
    - 글이 없으면 `NotFoundError`가 발생한다.
- 글을 삭제한다.
- 테스트 코드 작성하기

## ORM

```shell
yarn add @nestjs/typeorm typeorm sqlite3 
```

TypeORM을 설치하고 엔티티(Entity)를 선언한다.

`@Column`의 기본값은 null을 허용하지 않는다.
